
<html>
<head> 
<H1 style="color:orange;"> Joel Mulongo's Birthday Bash </H1>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
p {
  text-align: center;
  font-size: 60px;
  margin-top: 0px;
  background-image: url('images.png');
}
}
</style>
</head>
<body>

<p id="demo"></p>
👋 <Strong> Guys I Welcome you all to my bash</strong>🎉 to be held at 4js, behind Mountain view mall in Westlands <BR> <BR>
<h3 style="color:green;"> Important to note that we have reservations for 30 adults, I would be delighted with your attendance </h3><BR><BR> <IMG SRC= "happy-birthday-gif.gif"> <BR>
<Strong>Time </strong>🕘 21:00 to After Midnight🕔<BR> <BR>
<Strong>Exact Venue Location </strong>📌👇 <BR> <BR>
<Strong>Google Maps </strong>
<div style="width: 100%"><iframe width="100%" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=100%25&amp;height=300&amp;hl=en&amp;q=Mountain%20view%20mall%20Nairobi%20+(TechOne)&amp;t=k&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"><a href="https://www.maps.ie/distance-area-calculator.html">measure area map</a></iframe></div>
<script>
// Set the date we're counting down to
var countDownDate = new Date("Aug 24 , 2022 00:00:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000); 
</script>

</body>
</html>
