---
title: Thermometer
date: 2019-10-06 21:42:00 -04:00
layout: page
---

[<img src="https://secure.actblue.com/goals/70268.png?size=large&style=dark"/>](https://secure.actblue.com/donate/indivisibleama411742968?refcode=thermometer){:target="_blank"} to donate.

No amount is too small!!  We have work to do!!

Have a nice day!

---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

</style>
</head>
<body>

<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Nov 3 2020 20:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
 
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + " days left";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

</body>
</html>

***More stuff goes here***

**BOLD**

*Italics*
