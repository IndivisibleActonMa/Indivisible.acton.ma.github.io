---
title: Thermometer
date: 2019-10-06 21:42:00 -04:00
layout: page
---

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
var hours = Math.floor((t%(1000 * 60 * 60 * 24))/(1000 * 60 * 60)); 
var minutes = Math.floor((t % (1000 * 60 * 60)) / (1000 * 60)); 
var seconds = Math.floor((t % (1000 * 60)) / 1000); 

     
  // Output the result in an element with id="demo"
  var test1 = document.getElementById("demo");
  test1.style.font = "italic bold 30px arial,serif"; 
  //test1.style.textAlign = "center";
test1.innerHTML = days + "d " + hours + "h left until Nov 3, 2020!";
     
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "VOTE!";
  }
}, 60*60*1000);
</script>

---





[<img src="https://secure.actblue.com/goals/70268.png?size=large&style=dark"/>](https://secure.actblue.com/donate/indivisibleama411742968?refcode=thermometer){:target="_blank"} to donate.

No amount is too small!!  We have work to do!!

Have a nice day!

### We Need You

---

<meta name="viewport" content="width=device-width, initial-scale=1">

### WE NEED YOU!




We must ***FLIP the SENATE, KEEP the HOUSE and TAKE BACK the State Legislatures to repair Democracy***.

Please don't wait on the sidelines.  **It's all hands on deck now until election day!**

*Italics*
