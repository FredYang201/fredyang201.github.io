<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <title>Jinpeng Yang</title>
    
    <link href="../../../css/bootstrap.min.css" rel="stylesheet">
    <link href="../../../css/custom.css" rel="stylesheet">
    <link href="../../../css/carousel.css" rel="stylesheet">

    <style type="text/css">
      h2{
        color: #000;
      }
    </style>
  </head>
      
<body>
  <header>
      <nav class="navbar navbar-expand-sm navbar-dark fixed-top bg-dark">
        <div class='container'>
<!--           <a class="navbar-brand" href="index.html" style="font-size: 40px; margin-left: 20px">Jinpeng Yang</a>
 -->       <nav aria-label="breadcrumb" style="margin-top:16px; margin-left:18px;">
            <ol class="breadcrumb">
              <li class="breadcrumb-item"><a href="../../../index.html">Home</a></li>
              <li class="breadcrumb-item active" aria-current="page">APIs</li>
            </ol>
          </nav>
            <ul class="navbar-nav navbar-right" style="height: 80px;">
            <li class="nav-item active">
              <a class="nav-link" href="../Resume.pdf">
                <figure class="figure text-center">
                  <img class="figure-img img-rounded w-50" src="../../image/resume.svg" alt=""><figcaption class='figure-caption'><span style="color:#fff;">Resume</span></figcaption>
                </figure>
              </a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="https://www.linkedin.com/in/jinpengyang/">
                <figure class="figure text-center">
                  <img class="figure-img img-responsive img-rounded w-50" src="../../image/linkedin.svg" alt="">
                  <figcaption class='figure-caption' style="color:#fff;"><span>LinkedIn</span></figcaption>
                </figure>
              </a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="https://github.com/FredYang201?tab=repositories">
                <figure class="figure text-center">
                  <img class="figure-img img-responsive img-rounded w-50" src="../../image/github.svg" alt="">
                  <figcaption class='figure-caption' style="color:#fff;"><span>Github</span></figcaption>
                </figure>
              </a>
            </li>
          </ul>
        </div>
      </nav>
  </header>

<main role="main">

    <div id="myCarousel" class="carousel slide" data-ride="carousel">
    </div>

  <div class="container" style="padding-top: 40px; padding-left: 30px">
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-5">
          <h2>Snippets</h2>
          <p>The snippets api has: <span style="color:red;">id</span>, <span style="color:red;">title</span>, <span style="color:red;">code</span>, <span style="color:red;">language</span> and <span style="color:red;">style</span> items in each record. It also supports <span style="color:red;">.json</span> or <span style="color:red;">.api</span> format as its suffix_patterns. The permission here has IsAuthenticatedOrReadOnly, which means only admin can edit online. The feasible queries contain <a href="http://fredsnippet.herokuapp.com/snippets/">/snippets/</a>, <a href="http://fredsnippet.herokuapp.com/snippets/.json">/sinppets/.json</a>, <a href="http://fredsnippet.herokuapp.com/snippets/?page=3">/snippets/?page=3</a>, <a href="http://fredsnippet.herokuapp.com/snippets/38/">/snippets/id/</a> and so on.</p>
          <p><a class="btn btn-primary" href="http://fredsnippet.herokuapp.com/snippets/" role="button">Enter in &nbsp;&raquo;</a></p>
        </div>
        <div class="col-md-2"></div>
        <div class="col-md-5">
          <h2>Imdb movies</h2>
          <p>This api provides access to the top 250 movies in IMDB. Each record consists of <span style="color:red;">id</span>, <span style="color:red;">movieId</span>, <span style="color:red;">movie name</span>, <span style="color:red;">release year</span>, <span style="color:red;">rate</span>, and <span style="color:red;">link</span> to the page of movies. It also supports <span style="color:red;">.json</span> or <span style="color:red;">.api</span> format as its suffix_patterns. The feasible queries contain <a href="http://fredimdb.herokuapp.com/movies/">/movies/</a>, <a href="http://fredimdb.herokuapp.com/movies/.json">/moives/.json</a>, <a href="http://fredimdb.herokuapp.com/movies/?page=3">/movies/?page=3</a>, <a href="http://fredimdb.herokuapp.com/movies/detail/17925/">/movies/detail/movieId/</a> and so on.</p>
          <p><a class="btn btn-primary" href="https://fredimdb.herokuapp.com/movies/" role="button">Enter in &nbsp;&raquo;</a></p>
       </div>
    </div>
  <div class="row"><br><br></div>
  <div class="row">
          <div class="col-md-5">
            <h2>NBA players</h2>
            <p>The nba players api has: <span style="color:red;">id</span>, <span style="color:red;">playerName</span>, <span style="color:red;">playerNumber</span>, <span style="color:red;">team</span>, <span style="color:red;">height</span>, <span style="color:red;">weight</span>, <span style="color:red;">birthday</span>, <span style="color:red;">age</span>, <span style="color:red;">years in nba</span>, <span style="color:red;">basketball position</span>, <span style="color:red;">link</span> items in each record. It supports <span style="color:red;">.json</span> or <span style="color:red;">.api</span> format as its suffix_patterns. The feasible queries contain <a href="http://frednba.herokuapp.com/nba/">/nba/</a>, <a href="http://frednba.herokuapp.com/nba/.json">/nba/.json</a>, <a href="http://frednba.herokuapp.com/nba/?page=3">/nba/?page=3</a>, <a href="http://frednba.herokuapp.com/nba/age/24/">/nba/age/24/</a>, <a href="http://frednba.herokuapp.com/nba/year_in_nba/3/">/nba/year_in_nba/3/</a>, <a href="http://frednba.herokuapp.com/nba/position/Guard/">/nba/position/Guard/</a>, <a href="http://frednba.herokuapp.com/nba/team/Utah%20Jazz/">/nba/team/Utah Jazz/</a> and so on.</p>
            <p><a class="btn btn-primary" href="http://frednba.herokuapp.com/nba/" role="button">Enter in &nbsp;&raquo;</a></p>
          </div>
          <div class="col-md-2"></div>
      </div>


    <hr class="featurette-divider">
  </div>
  <!-- FOOTER -->
    <footer class="container">
      <p class="float-right"><a href="#">Back to top</a></p>
      <p>&copy; <a href="#">Jinpeng Yang</a> &middot; <a href="#">Privacy</a> &middot; <a href="#">Terms</a></p>
    </footer> 
 </main>  

    <script src="../../../js/custom.js"></script>
    <script src="../../../js/bootstrap.bundle.min.js"></script>
  </body>
</html>



 