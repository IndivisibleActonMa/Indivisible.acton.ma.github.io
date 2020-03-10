---
title: Countdown
date: 2019-12-30 23:20:00 -05:00
layout: page
---





---

<span style="font-style: Brandon; font-size:2em; color:RoyalBlue">Remove Trump, Flip the Senate and State Houses, Hold the House!!!</span>

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
  var t = countDownDate - now;
    
  // Time calculations for days
  var days = Math.floor(t / (1000 * 60 * 60 * 24));
  var hours = Math.floor((t%(1000 * 60 * 60 * 24))/(1000 * 60 * 60)); 
  var minutes = Math.floor((t % (1000 * 60 * 60)) / (1000 * 60)); 
  var seconds = Math.floor((t % (1000 * 60)) / 1000);  

  // Output the result in an element with id="demo"
  var test1 = document.getElementById("demo");
  test1.style.font = "italic bold 30px arial,serif"; 
  //test1.style.textAlign = "center";
//test1.innerHTML = days + " days left until Nov 3, 2020!";
  test1.innerHTML = days + "d " + hours + "h " + minutes + "m " + seconds + "s until Nov 3, 2020!";
  
  
  // If the count down is over, write some text 
  if (t < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
},500);
</script>

---

Embedding countdown here:

<iframe width="300" height="154" src="https://w2.countingdownto.com/2799792" frameborder="0"></iframe>

---

*Please check the [calendar](http://www.indivisibleacton.org/calendar.html){:target="_blank"} for **NEW Winning Wednesday** postcard events!*

---

Red 4em: <span style="font-family:Papyrus; font-size:4em; color:red">LOVE!</span>

Green 1em: <span style="font-family:Papyrus; font-size:1em; color:green">LOVE!</span>

lime 87 2em: <span style="font-family:Papyrus; font-size:2em; color:lime">LOVE!</span>

Navy 2em:
<span style="font-family:Papyrus; font-size:2em; color:Navy">Make a plan to WIN in 2020!  **Check out our *new* mini-website [Win 2020 Personal Monthly Election Strategy](https://sites.google.com/view/win2020personalmonthlystrategy/home){:target="_blank}!**</span>

### End of test