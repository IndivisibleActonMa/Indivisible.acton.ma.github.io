---
title: Elections
date: 2019-12-30 22:56:00 -05:00
---

---

<p id="demo">
</p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 20 2021 12:00");

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
  test1.innerHTML = days + "d " + hours + "h " + minutes + "m " + seconds + "s left until 12p Jan 20, 2021!";
  
  
  // If the count down is over, write some text 
  if (t < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "The biggest threat to our democracy is indifference.";
  }
},500);
</script>

Barack Obama, Sep 7, 2018  

---

### MA Elections 

Even though elections are over, the Legislature is still in session.  

Please check out our priority bills [HERE](https://docs.google.com/spreadsheets/d/1hVWycjVbyL6-bYayLP04o3N2-o3l9Yh0n9RtEIFKFK0/edit#gid=0).

---

### Candidate and Campaign Policy and Etiquette

Indivisible Acton welcomes candidates and their staff. In order to assure productive, fair and healthy discourse between campaigns and Indivisible Acton members these policies have been put in place. Please see our [Candidate and Campaign Etiquette and Policy](https://docs.google.com/document/d/1-G3_GKFkz3fC0VDkfGh4DbC820mzi23yyMG1-EqapfE/){:target="_blank"}  document.

Any questions or concerns should be directed to the membership coordinator [Christine B](mailto:christine@indivisibleacton.org).  

### Social Media Policy for the Primaries

Click [HERE](https://docs.google.com/document/d/1k-N7qZ5fBR2wRGOcRI8ZJxQGbO5CfsXbZlZSKHm4N18){:target="_blank"} to see Indivisible Acton-Area's social media policy for the primaries.  


