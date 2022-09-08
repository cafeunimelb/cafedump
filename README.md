# cafedump
i wonder if i can store stuff here
a<br>
a<br>
### table of contents
a<br>
a<br>
a<br>
a<br>
a<br>
a<br>
a<br>
[b](#cafedump)<br>
[c](###table-of-contents) 

According to all known laws
of aviation, <br><span id="dots">...</span><span id="more">
there is no way a bee
should be able to fly. <br>
Its wings are too small to get
its fat little body off the ground. <br>
The bee, of course, flies anyway
because bees don't care 
what humans think is impossible. <br>
Yellow, black. Yellow, black. <br>
Yellow, black. Yellow, black. <br></span>

<button onclick="myFunction()" id="myBtn">Read more</button>

#more {display: none;}

function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more";
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less";
    moreText.style.display = "inline";
  }
}
