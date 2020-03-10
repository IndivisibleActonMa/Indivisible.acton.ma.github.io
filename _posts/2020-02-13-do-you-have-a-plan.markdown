---
title: Do You Have A Plan?
date: 2020-02-13 07:33:00 -05:00
is featured: true
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
  test1.innerHTML = days + "d " + hours + "h " + minutes + "m " + seconds + "s left until Nov 3, 2020!";
  
  
  // If the count down is over, write some text 
  if (t < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "Let's Get Out and VOTE!!!";
  }
},500);
</script>

---  


### Make a plan to WIN in 2020!

* Check out our *new* mini-website [Win 2020 Personal Monthly Election Strategy](https://sites.google.com/view/win2020personalmonthlystrategy/home){:target="_blank}!  

  2020 is a **MUST** win year.  If we take action, we win!!




 
---

