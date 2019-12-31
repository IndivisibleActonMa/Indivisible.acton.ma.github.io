---
title: Countdown
date: 2019-12-30 23:20:00 -05:00
layout: page
---


This is a countdown test!!!


---

<p id="demo">
</p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Nov 3 2020 00:00");

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date
  var now = new Date();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
 
  // Output the result in an element with id="demo"
  var test1 = document.getElementById("demo");
  test1.style.font = "italic bold 30px arial,serif"; 
  //test1.style.textAlign = "center";
test1.innerHTML = days + " days left until Nov 3, 2020!";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
},500);
</script>

---

End of test