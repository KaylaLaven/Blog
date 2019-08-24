<!DOCTYPE html>
<html>
<head>
  <title>My Blog</title>
  <link rel="stylesheet" type="text/css" href="blog.css">
</head>
<body>

<link href='http://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700,400italic|Source+Code+Pro:400,700' rel='stylesheet' type='text/css'>

<div class="post">
   
  <div class="date">August 24, 2019</div>
  <h2>This Is My Favorite Quote</h2>

  <p class="quote">
  "Dimming someone else's light won't make yours shine any brighter."-ANON
  </p>

  <p>Bresaola short ribs pastrami, beef ribs spare ribs kielbasa ham tongue kevin landjaeger chicken ball tip. Pork chop beef kevin strip steak, chicken pork belly pastrami ham hock flank shoulder chuck turkey ribeye andouille ball tip. Leberkas ham ham hock pork loin. Filet mignon bacon pancetta leberkas turducken fatback tongue frankfurter jowl. Shoulder tenderloin chicken shank bacon shankle sirloin.</p>

  <p>Pork pig pork loin prosciutto meatball turkey beef ribs ground round. Pork belly salami shank pork chop turducken ribeye swine shoulder tri-tip fatback cupim short loin chuck strip steak. Rump pork chop t-bone.</p>
  <hr>
</div>

<!-- <hr> -->

<div class="post">
  <div class="date">December 11 2015</div>
  <h2>This Is Another Article</h2>

  <p class="quote">
  Bacon ipsum dolor amet capicola strip steak landjaeger, biltong spare ribs rump cow ground round andouille sirloin pork. Short ribs pig prosciutto swine. Flank turducken turkey rump, leberkas shoulder bresaola ham hock tail drumstick corned beef. Venison pork chop beef jowl short ribs.
  </p>

  <p>Shankle beef ribs tongue strip steak flank landjaeger capicola hamburger chuck pancetta kevin. Sirloin landjaeger chicken, bresaola brisket swine short ribs turkey short loin ball tip porchetta ham hock. Capicola frankfurter jowl short loin. Kevin flank hamburger, beef venison shankle short loin bresaola frankfurter</p>

  <p>Bresaola short ribs pastrami, beef ribs spare ribs kielbasa ham tongue kevin landjaeger chicken ball tip. Pork chop beef kevin strip steak, chicken pork belly pastrami ham hock flank shoulder chuck turkey ribeye andouille ball tip. Leberkas ham ham hock pork loin. Filet mignon bacon pancetta leberkas turducken fatback tongue frankfurter jowl. Shoulder tenderloin chicken shank bacon shankle sirloin.</p>
</div>

</body>
</html>

<!-- css-->
@import url(https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700);

body {
  width: 80%;
  border: 20px solid #bdc3c7;
  font-family: 'Source Sans Pro', sans-serif;
  padding: 20px;
  margin: 20px auto;
  max-width: 700px;
}

.post {
  margin-bottom: 20px;
}

.date {
  color: #3498db;
  letter-spacing: 0.2rem;
  text-transform: uppercase;
}

.quote{
  border-left: 5px solid #bdc3c7;
  padding-left: 5px;
}

h2 {
  font-size: 2.0rem;
  font-weight: bold;
  color: #2c3e50;
}

hr{
    border: 0;
    height: 0;
    border-top: 1px solid rgba(0, 0, 0, 0.1);
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
}

