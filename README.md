# sarahdia.github.io
<!DOCTYPE html>
<head>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <link href="http://www.espn.com/video/sportscenter" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4MY7saZPpGP33YfXUF9vkaule8Tag4uBOYlRxO6X9gQpp4CFmQQ");
      background-size: cover;
      color: orange;
      font-family; Trebuchet MS;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 50px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: rgba(255,0,0,0);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 900px;
      padding: 30px;
      margin: 0 auto;
      color: rgba(255,255,255,1)
    }
    <body>
    background: red;
    @media (max-width: 500px) {
      h1 {
        font-size: 25px;
        padding: 5px;
      }
      li {
        padding: 10px;
        display: black;
      }
    }
    img {
          width: 90;
          border-radius:10
    }
  </style>
</head>
<body>
  <header>
    <img src="https://bsbproduction.s3.amazonaws.com/portals/9843/images/volleyball-art-work.jpg">
    <h1>Sports Review</h1>
    <ul>
      <li><a href="#">Teams</a></li>
      <li><a href="#">Players</a></li>
      <li><a href="#">Scoreboard</a></li>
    </ul>
  </header>
  <article>
    <h2>Volleyball</h2>
    <p> The Jamaica Girls Volleyball team has played against Hillcrest Girls Volleyball team and had scored 52 points winning the game. Click the button below to view the stats.</p>
    <button>Go</button>
  </article>
  <article>
    <h2>Football</h2>
    <p>Join us on our last  home game this Friday! Jamaica will be having their last Varsity football game against Eagle III his is something you won't want to miss!!</p>
    <button>Go</button>
  </article>
  <article>
    <h2>Soccer</h2>
    <p>Shoutout to the boys and girls soccer team they have played a wonderful season this year! They have worked very hard to win the championship and we are proud that they have brought home a beautiful trophy!</p>
    <button>Go</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Entered!");
    });
  </script>
</body>
