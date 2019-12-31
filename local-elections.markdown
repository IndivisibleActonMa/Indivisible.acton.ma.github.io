---
title: Elections
date: 2019-12-30 22:56:00 -05:00
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

### Candidate and Campaign Policy and Etiquette

Indivisible Acton welcomes candidates and their staff. In order to assure productive, fair and healthy discourse between campaigns and Indivisible Acton members these policies have been put in place. Please see our [Candidate and Campaign Etiquette and Policy](https://docs.google.com/document/d/1-G3_GKFkz3fC0VDkfGh4DbC820mzi23yyMG1-EqapfE/edit) document.

Any questions or concerns should be directed to the membership coordinator Christine B: christine@indivisibleacton.org.

---
### Important Dates

* **March 3, 2020 - State Primary**

* **March 31, 2020 - State Election**

---

### Special State Election for 37th Middlesex District

Click [HERE](https://www.sec.state.ma.us/ele/elespeif/37middlesexcal.htm){:target="_blank"} for more info

---

