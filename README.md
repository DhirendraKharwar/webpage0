<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" >
        <!--jQuery library--> 
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
        <!--Latest compiled and minified JavaScript--> 
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Panels in Bootstrap</title>
    <style>
        .container{
            border:2px solod black;
        }
        .jumbotron{
            margin:5px;
        }
        .sitename{
            text-align:center;
        }
    .column_style{
        background-color:#40d7;
        margin-right:5px;
        margin-top:5px;
        border-radius: 2px;
        text-align:center;
        font-size:18px;
    }
        .column_style:hover{
               background-color:#40d789;
               background-random:4px;
               
           }
    .pannel{
        background-color:#ff87;
        border-radius:4px;
        width:100%;
        align-left:20%;
    }
    .pannel-heading{
        background-color:#40d7;
        border-radius:5px;text-align:center;
    }
    .pannel-footer{
        text-align:center;
        background-color:#40f8;
        border-radius:5px;
    }
    .btn{
        font-size:18px;
    }
    h1{
        font-family:Verdana;
    }
    .mySlides{
        border-radius:5px;
    }
     
    </style>
    <body>
        <div class="container">
            <div class="header jumbotron">
                <div class="row">
                    <div class="col-lg-2 col-xs-4 col-md-6 col-sm-6 "><a href="#" ><img src="/watch.jpg" class="img-responsive img-circle logo1" alt="Watch"></a></div>
                    <div class="col-lg-6 sitename "><h1>WELCOME TO CHINCHPADA</h1></div>
                    <div class="col-lg-2 visible-lg visible md"><a href="#" ><img src="/watch.jpg" class="img-responsive img-circle logo2" alt="Watch"></a></div>
                </div>
            </div>
        </div >
        <div class="container">
            <div class="col-lg-2 col-xs-5 column_style">Home</div>
            <div class="col-lg-2 col-xs-5 column_style">About Us</div>
            <div class="col-lg-2 col-xs-5 column_style">E-Gram</div>
            <div class="col-lg-2 col-xs-5 column_style">E-School</div>
            <div class="col-lg-2 col-xs-5 column_style">Help</div>
    
        </div>

        <div class="container ">
            <div class="jumbotron">
                <div class="w3-content w3-section" style="max-width:500px">
  
  <img class="mySlides w3-animate-fading" src="/shirt.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="/watch.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="/shirt.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="/watch.jpg" style="width:100%">
</div>

<script>
    var myIndex = 0;
    carousel();

    function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
        x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 9000);    
    }
</script>
    </div>
</div>



        <div class="container">
            <div class="row row-style">
                <div class="col-xs-6">
                    <div class="pannel pannel-default">
                    <div class="pannel-heading"><h1>Notice Board</div>

                        <div class="pannel-body">
                            <p>Here is all about information</p>
                            <button class="button btn-primary">Demo</button>
                        </div>
                        <div class="pannel-footer"><h4>All information is important for you</h4></div>
                    </div>
            </div>
        </div>
        
        <div class="container">
            <div class="row">
                <div class="col-xs-3">
                    <div class="thumbnail">
                        <a href="#" ><img src="/watch.jpg" class="img-responsive img-rounded" alt="Watch"></a>
                    <input type="submit" value="GRAMSEVAK" class="btn btn-primary btn-block"></div>
                </div>
                <div class="col-xs-3">
                    <div class="thumbnail">
                        <a href="#" ><img src="/watch.jpg" class="img-responsive img-rounded" alt="Watch"></a>
                    <input type="submit" value="SARPANCK" class="btn btn-primary btn-block"></div>
                </div>
                <div class="col-xs-3">
                <div class="thumbnail">
                    <a href="#" ><img src="/watch.jpg" class="img-responsive img-rounded" alt="Watch">
                </a><input type="submit" value="KRUSHISEVAK" class="btn btn-primary btn-block"></div></div>
                <div class="col-xs-3">
                <div class="thumbnail">
                    <a href="#" ><img src="/watch.jpg" class="img-responsive img-rounded ol-xs-6" alt="Watch">
                </a><input type="submit" value="ZP TEACHER" class="btn btn-primary btn-block col-xs-6"></div></div>
                
            </div>
        </div>

    </body>
