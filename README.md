<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Arena</title>
    <!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css">
    <link rel="stylesheet" href="style.css">
       <link rel="shortcut icon" href="img/download.png" type="image/x-icon">
    <script src="jquery.js"></script>
    <script>
        $(document).ready(function(){
            $("#gt").hover(function(){
                $("#equ").slideDown(1000)

            });
        });

        $(document).ready(function(){
            $("#hm").hover(function(){
                $("#equ").slideUp(1000)

            });
        });

        $(document).ready(function(){
            $("#body4").hover(function(){
                $("#nev").slideDown(1000)

            });
        });
        $(document).ready(function(){
            $("#body4").hover(function(){
                $("#btn4").slideDown(1000)

            });
        });
        
    </script>

</head>
<body>

    <div id="main1">
        <div id="body 1">
           


            <div id="enter">
                <input type="text" placeholder="Enter Your Search" id="search">
              
            </div>

            <h1 id="title">
                Fitness Arena 
            </h1>
            
            
            <div id="nav">
                <button id="hm"><a href="">Home</a></button>
                <button id="gt"><a href="">Gym Equiments</a>
                    <div id="equ">
                        <ol  style= "list-style: none; ">
                            <li><a href="">Dumbells</a></li>
                            <li><a href="">Barbells</a></li>
                            <li><a href="">Weight Lifting Plates</a></li>
                            <li> <a href="">Home Gym</a></li>
                        </ol>
                    </div>
                </button>
                <button><a href="">Machines</a></button>
                <button><a href="boxing.html" target="_blank">Boxing</a></button>
                <button> <a href="">Crossfit</a></button>
                <button> <a href="" >Sale</a>   </button>
             

      

    </div>
    <div id="main2">
        <div id="body2">
            <div id="head">
                <h3 id="title2">
                    GET STARTED<br> WITH YOUR <br> FITNESS JOURNEY
                </h3>
   
            </div>

           

            <div id="form1">

                <h4 style="padding-left: 50px; font-size: 0.6cm; color: #60042C; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">Register Now </h4>

                <label for="">Name</label>
                <input type="text" placeholder="Enter Name">

                <br>
                <br>
                <label for="">Email</label>
                <input type="email" placeholder="Enter email">
                <br>
                <br>

        
                <label for="">Contact</label>
                <input type="number" placeholder="Enter number">
                <br>
                <br>

                <label for="">Address</label>
                <input type="text" placeholder="Enter Address">
        
          
               
                
        
        
             </div>

        </div>
        

       
          
        </div>


        <div id="main3">
            <div id="body3">

                <div class="card" style="width: 18rem; float: left;">
                    <img src="img/plate 1.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Olympics Weight Lifting Plates (Per Kg)</h5>
                      <p class="card-text">1200PKR</p>
                      <a href="#" class="btn btn-primary">Order Now</a>
                    </div>
                  </div>


                  <div class="card" style="width: 18rem; float:left ;">
                    <img src="img/dumbells2.jpg" class="card-img-top" alt="..." style="padding-top: 80px;">
                    <div class="card-body">
                      <h5 class="card-title">Adjustable Dumbells (Per Kg) with Rod</h5>
                      <p class="card-text">600PKR</p>
                      <a href="#" class="btn btn-primary">Order Now</a>
                    </div>
                  </div>

                  <div class="card" style="width: 18rem; float:left ;padding-top: 0px;">
                    <img src="img/homegym.jpg" class="card-img-top" alt="..." style="padding-top: 80px;">
                    <div class="card-body">
                      <h5 class="card-title">Home Gym</h5>
                      <p class="card-text">80000PKR</p>
                      <a href="#" class="btn btn-primary">Order Now</a>
                    </div>

                </div>
                <div class="card" style="width: 18rem; float:left ;padding-top: 0px;">
                    <img src="img/boxing.png" class="card-img-top" alt="..." style="padding-top: 80px;">
                    <div class="card-body">
                      <h5 class="card-title">Boxing Bag</h5>
                      <p class="card-text">8000PKR</p>
                      <a href="#" class="btn btn-primary">Order Now</a>
                    </div>

                </div>


            </div>



        </div>


        <div id="main4" style="margin-top:500px ;">

            <div id="body4">

                <div id="pic1">
                    <div id="bos">
                        <h3 id="nev">You never lose<br> until you actually give up.”<br> -Mike Tyson.</h3>
                          <button id="btn4"><a href="boxing.html">Get Your Boxing Bag Now</a></button>
                    </div>
                    
                </div>
            </div>
        </div>

        <div id="main5">

            <div id="body5">
                <div id="nee">
               <ol>
                <li > <a href="" style="font-weight: bolder;">Need Help ? </a></li>
                <li><a href="">Shipping and Delivery</a></li>
                <li> <a href=""> Tracking</a></li>
                <li><a href="">Quality Assurance</a></li>
                <li><a href="">Weight Tracking</a></li>
               </ol>
            </div>


            <div id="chat">
                <ol>
                 <li > <a href="" style="font-weight: bolder;">Customize Designs </a></li>
                 <li><a href="boxing.html">Make Customize Boxing Bags</a></li>
                 <li> <a href="">Tank Tops</a></li>
                 <li><a href="">Gym Hoodies</a></li>
                 <li><a href="">Gym Bags</a></li>
                </ol>
             </div>

             <div id="con">
                <ol>
                 <li > <a href="" style="font-weight: bolder;">Contact Us </a></li>
                 <li><a href="https://www.whatsapp.com/">Live Chat</a></li>
                 <li> <a href="">Email</a></li>
                 <li><a href="">Contact Number</a></li>
                 <li><a href="">Messages</a></li>
                </ol>
             </div>
             <div id="ema">
                <input type="text" placeholder="Enter Your Email" style="border-radius:5px ;border: 1px solid white;  ">
                <button style="background-color:black ; color: aliceblue; ">
                    Sign Up
                </button>
             </div>
        </div>

        </div>
       

   
    
</body>
</html>
