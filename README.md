<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>
    the assignment one </title>
</title> 
<style>

/* * {
    position: relative;
    
} */
body {
 margin: 0;
 padding: 0;
 background-color: lightgray;
}
h1 {
    text-align: center;
    margin-top: 50px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

/* h1 {
    margin-bottom: 30px;
}
h2 {
    margin-bottom: 30px;
}
h3 {
    margin-bottom: 30px;
} */

#box1, #box2, #box3 {
        background-color: rgb(100, 31, 31);
        padding: 7px; 
        border: 3px solid goldenrod; 
         margin: 50px;
        /* margin-bottom: 15px; */ 
        width: 300px;
        /* height: 250px; */
        position: relative;
        box-sizing: border-box;
        overflow: hidden; 
        float: left;              
}
span {
    background-color: white;
    float: right;
    text-align: center;
    border: 2px solid black;
    width: 60px;
}

#content {
    background-color:rgb(161, 43, 43);
    color: white;
   
}

/* large devices  */
@media (min-widht: 992px) {
    #box1, #box2, #box3 {
        width: 80%;
    }
}
@media /*TABLET VIEW*/ (min-width: 768px) and (max-width: 991px) {
          #box3 {
              width: 100%;
              height: fit-content;
          }
}

</style>
</head>
<body>
    <h1> The asignment one </h1>
    <!-- <h1> Paragraph 1 </h1> -->
<div id="box1" class="row">
    <div class="col-md-4 col-sm-6 col-xs-12">
        <span>para1</span>
    <div id="content">
        We as people need to be governed with rules, laws and regulations to avoid confusion in our minds
         and to promote harmonization among others. Rule sometimes limit the things that we can do, things
          that can be much enjoyed in the absence of regulations.
    </div>
</div>
</div>


<!-- <h2> Paragraph 2 </h2> -->
<div id="box2" class="row">
    <div class="col-md-4 col-sm-6 col-xs-12">
        <span>para2</span>
    <div id="content">
        Whereas in the country India there are around 1248 laws for the betterment of the society 
        but with all due respect India is one of the most perilous country to live happily, 
        despite having so much restrictions and rules the country experiences highest numbers of chaos and disputes 
        of which some are resolved and most of them are pending. 
    </div>
    </div>
</div>

<!-- <h3> Paragraph 3 </h3> -->
<div id="box3" class="row">
<div class="col-md-4 col-sm-6 col-xs-12">
    <span>para3</span>
    <div id="content">
        This clearly signifies that rules and regulations are based upon mindset one will follow the
         rules and regulations whether it is applied or not whether others are following or not as we know
          that mindsets are not the result of rules and laws, it is the fertile product of ethics, believes, values and healthy norms. 
    </div>
    </div>
</div>

</body>
</html>
