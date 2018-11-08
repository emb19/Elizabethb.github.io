# Elizabethb.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Elizabeth portfolio</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <link rel="stylesheet" href="style.css">
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="50">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#myPage">Elizabeth</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#myPage">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li class="b" data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li class="b" data-target="#myCarousel" data-slide-to="1"></li>
      <li class="b" data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="static/images/church.jpg" alt="New York" width="1200" height="700">
      </div>

      <div class="item">
        <img src="static/images/jumbotron.jpg" alt="Chicago" width="1200" height="700">
      </div>

      <div class="item">
        <img src="static/images/church2.jpg" alt="Los Angeles" width="1200" height="700">
      </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>
</div

<!-- Container (The About Section) -->
<div id="about" class="container text-center">
  <h1>About me</h1>
  <p class="p">My name is Elizabeth. I'm currently a junior at CodeRVA Regional high school.
    I just finished an 8 week internship where I learned how to code in different languages and
    I learned different roles in departments. Some things I enjoy doing during my free time are
    painting/drawing, playing softball, learning new songs on the piano, and participating in
    my church's events.</p>
    <br>

    <h3>Internship</h3>
    <p class="p">During my 8 week internship I learned different roles in departments,
      during my 3 2-week sprints I was a Data Quality Specialist, Quality Assurance Specialist,
      and Network Administrator. I was challenged to learn the responsibilities and
      expectations of each role and help my team complete our given projects with what I knew.
      It was a rough start and we all made mistakes, but in the end we pushed each other to do our best,
      we built each other up instead of tearing each other down. To me this internship was an
      opportunity to see what a real job is like, it helped me realize what jobs I thought I
      liked but didn’t and vice versa. This internship not only helped me further my knowledge about
      computer science/coding but it helped me grow as a person.</p>
      <br></br>

      <h4>Data Quality Specialist</h4>
      <p class="p">My job as a data quality specialist was to make sure there weren't errors in the data in google
        sheets so we got the right numbers when graphing things or getting averages. We would use this
        data to improve the usage of our site. </p>
        <br></br>

      <h4>Quality Assurance (QA)</h4>
      <p class="p">As Quality Assurance I had to make sure that everything worked properly. (no broken links, navbar
        works, no spelling errors etc.) </p>
        <br></br>

      <h4>Network Administrator</h4>
      <p class="p">During my last rotation as Network Admin, my job would’ve been to administer the network by making
        sure we weren't being attacked making sure we had a working network, however we didn't have one
        so I was given the task of writing the policy for our Password management system.</p>

</div>

<!-- Container (Gallery Section) -->
<div id="gallery" class="bg-1">
  <div class="container">
    <h2 class="text-center">Gallery</h2>
    <br>
    <h3>Acrylic pours</h3>
    <img src="static/images/art1.jpg" alt="art" class="responsive">
    <img src="static/images/art2.jpg" alt="art" class="responsive">
    <img src="static/images/art3.jpg" alt="art" class="responsive">
    <img src="static/images/art4.jpg" alt="art" class="responsive">
    <img src="static/images/art5.jpg" alt="art" class="responsive">
    <img src="static/images/art6.jpg" alt="art" class="responsive">
    <img src="static/images/art7.jpg" alt="art" class="responsive">
    <img src="static/images/art8.jpg" alt="art" class="responsive">
    <img src="static/images/art9.jpg" alt="art" class="responsive">

    <h3>Drawings</h3>
    <img src="static/images/art10.jpg" alt="art" class="responsive">
    <img src="static/images/art11.jpg" alt="art" class="responsive">
    <img src="static/images/art12.jpg" alt="art" class="responsive">

    <h3>Photography</h3>
    <img src="static/images/sky2.jpg" alt="art" class="responsive">
    <img src="static/images/sky3.jpg" alt="art" class="responsive">
    <img src="static/images/flower1.jpg" alt="art" class="responsive">
    <img src="static/images/flower2.jpg" alt="art" class="responsive">
    <img src="static/images/flower3.jpg" alt="art" class="responsive">
    <img src="static/images/flower4.jpg" alt="art" class="responsive">
  </div>
</div>

<!-- Container (Contact Section) -->
<div id="contact" class="container">
  <h1 class="text-center">Contact</h1>
  <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdaF2qnQ7OFMWG78oxsqBxn85iEBSAwj7lSF4FMpWhtvsoEgA/viewform?embedded=true"
  width="640" height="891" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
</div>


<!-- Footer -->
<footer class="text-center">
  <a class="up-arrow" href="#myPage" data-toggle="tooltip" title="TO TOP">
    <span class="glyphicon glyphicon-chevron-up"></span>
  </a><br><br>
  <p>Developed in 2018</p>
</footer>

<script>
$(document).ready(function(){
  $('[data-toggle="tooltip"]').tooltip();
  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
    if (this.hash !== "") {
      event.preventDefault();
      var hash = this.hash;

      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){

        window.location.hash = hash;
      });
    }
  });
})
</script>
</body>
</html>
