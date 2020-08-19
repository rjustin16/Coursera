<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Responsive Layout</title>
<style>
  body {
    background-color: gray;
  }

  #box1 {
    background-color: blue;
    overflow: auto;
    box-sizing: border-box;

  }
  #box2 {
    background-color: white;
    box-sizing: border-box;
    border: solid yellow 5px;
    margin-top: 0px
    color:white;
  }
  #box3 {
    background-color: yellow;
    border: solid teal 5px;
    margin-top: 0px
  }
  #box4 {
    background-color: red;
    border: solid black 5px;
    margin-top: 0px

  }
/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  float: right; 
  color: black;
  border: 5px black;
  font-size: 25px

}

p {
  border:1px black;
  background-color: yellow
  box: solid black;
  margin-left: 5px;
  margin-right: 5px;
  font-family: Helvetica;
  color: white;
  padding: % ;
  align-self: auto 
  text-anchor: left;
  text-align: left;
}
h2{
  text-align: center;
}
.row {
  width: 100%;
  align-content: center;

}



/********** Large devices only **********/
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    border: 1px solid black;
    height: 300px;
    background-color: blue;
    overflow: auto;
    padding: 10px 10px 10px 10px;
    margin-top: 10px
    margin-right: 3px;
    margin-left: 3px;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 33%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** Medium devices only **********/
@media (min-width: 992px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid black;
    height: 150px;
    background-color: blue;
    overflow: auto;
    padding: 10px 10px 10px 10px;
    margin-top: 3px
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
    margin-right: 2px:
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}
/********** Small devices only **********/
@media (min-width:100px) and (max-width: 991px){.col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12{ float-left;
border: 1px solid black;
height: 150px;
background-color: blue;
overflow: auto;

}
.col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33%;
  }
  .col-sm-5 {
    width: 41.66%;
  }
  .col-sm-6 {
    width: 100%;
    margin-top: 5px
  }
  .col-sm-7 {
    width: 58.33%;
  }
  .col-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }
}
</style>
</head>
<body>
<h2>Zoids Wild</h2>
<div class="row">
  <div class="col-lg-3 col-md-6 col-sm-6"> 
    <div> 
       <div>
        <h1 id="box2">Freedom</h1>
      </div>
      <p>Team Freedom is led by Arashi and his Wild Liger. He is initally a novice zoid hunter with a goal to adventure. During his time he battles with the Death Metal Empire and fights for the freedom of zoids.</p>
    </div>
   </div>
  <div class="col-lg-3 col-md-6 col-sm-6">
    <div>
      <div>
        <h1 id="box3">Supreme</h1>
      </div>
      <p>Team Supreme is led by Bacon. He is well known as a famous, powerful, Zoid Hunter. Initially he seeks the Wild Liger, before meeting Arashi. While not strictly   a resistance force, Team Supreme oppose the Death Metal empire. Their goal is to search for the "Great Ancient Treasure Z".</p>
    </div>
  </div>
  <div class="col-lg-3 col-md-12 col-sm-6">
      <div>
      <div>
        <h1 id="box4">Death Metal</h1>
      </div>
      <p>The Death Metal Empire is lead by Gallagher. They seek to revive Zoids and use them as weapons for world conquest. Gallagher's right-hand man is Rakkyo, and below that there are the Four Heavenly Kings: Drake, Truffle, Caviar, Foiegras. The majority of their forces are comprised of Raptors who are piloted by the Z Boys.</p>
    </div>
  </div>

</div>

</body>
</html>
