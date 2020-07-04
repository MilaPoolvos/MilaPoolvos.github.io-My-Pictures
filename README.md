<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    header {
      text-align: center;
      background: url('https://i.imgur.com/vJ2ojYv.jpg');
      background-size: cover;
      color: white;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 70px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 10px;
      background: rgba(149,83,83,0.4);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
    }
    @media (max-width: 500px) {
      h1 {
        font-size: 36px;
        padding: 5px;
      }
      li {
        padding: 5px;
        display: block;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src= https://i.imgur.com/YYE3hge.jpeg>
    <h1>Senna's Blog</h1>
    <ul>
      <li> <a href="https://milapoolvos.github.io"> Home </a> </li>
      <li> <a href="https://milapoolvos.github.io/MilaPoolvos.github.io-About-me/"> About Me </a> </li>
      <li> <a href="https://milapoolvos.github.io/MilaPoolvos.github.io-My-Pictures/"> My Pictures </a> </li>
      <li> <a href="https://milapoolvos.github.io/MilaPoolvos.github.io-Pawums/"> Pawums </a> </li>
    </ul>
  </header>
  <article>
    <a href="#About Me"> About Me </a>
    <h2> About me </h2>
    <p>Marfa church-key kitsch bicycle rights, 8-bit mixtape cardigan gentrify Echo Park. Street art swag brunch, next level roof party Schlitz hella organic keffiyeh selfies. You probably haven't heard of them polaroid hashtag +1, meggings biodiesel Portland High Life cray tumblr retro.</p>
    <button>Like</button>
  </article>
  <article> 
    <a href="#My Pictures"> My Pictures </a>
    <h2>My Pictures</h2>
    <p>chambray you probably haven't heard of them pour-over viral selvage umami skateboard VHS post-ironic selfies. Wes Anderson gentrify fanny pack twee, bicycle rights bitters blog keffiyeh plaid flannel. Tonx irony cliche sustainable mlkshk bitters. Four loko leggings chambray Vice.</p>
    <button>Like</button>
  </article>
  <article>
    <a href="#Pawums"> Pawums </a>
    <h2>Pawums</h2>
    <p>ethical thundercats sustainable locavore quinoa Neutra. Aesthetic tacky sweater single-origin coffee, bicycle rights organic lo-fi street art american apparel ennui four loko ethnic Brooklyn small batch. Forage YOLO polaroid</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
  </script>
</body>
