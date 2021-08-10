<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500&display=swap" rel="stylesheet">

 <style>
       
      *{
           box-sizing:border-box;
           margin:0;
           padding:0;
           font-family: 'Red Hat Display', sans-serif;
            
       }

       body{
           width:100vw;
           height:100vh;
           background: no-repeat url(file:///C:/Users/richa/OneDrive/Desktop/Challenges/order-summary-component-main/images/pattern-background-desktop.svg);
           background-color: hsl(225, 100%, 94%);
           
       }
         
       
       .card{
           margin: 200px auto;
           background-color:white;
           width: 450px;
           height:fit-content;
           border-radius: 20px;
           box-shadow: 2px 2px 2px 2px hsl(224, 23%, 55%)
           
       }
  
       .hero-image{
    
        width:100%;
        height:30%;
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
       }
        
       .Center-text{

        margin-top: 50px;
        text-align:center;
        padding: 0px 30px 20px 30px;
        font-size: 1.2rem;
        color: hsl(224, 23%, 55%)

       }

       .header{
          padding-bottom: 15px;
          font-size: 30px;
          color: hsl(223, 47%, 23%)
       }
    
       .annualplan-container{
           padding: 20px;
           display:grid;
           grid-template-columns:1fr 2fr 1fr;
           margin: 0 auto;
           background-color:hsl(225, 100%, 98%);
           width:80%;
           height:fit-content;
           border-radius: 20px;
       }

       .music-logo{
           width:80%;
           
       }
    
       .annual-plan-text{
           font-size: 0.6em;
           align-self: center;
           justify-self:start;

       }

       .price{
           font-size:1.7em;
       }

        .change{
            grid-column: 3 / 4;
            font-size: 1.2em;
            align-self: center;
            justify-self: center;
            color:black;
        }

        .change:hover{
            color: blue;
        }

        .proceed-button{
          margin:35px auto 0px auto;
          width: 400px;
          padding: 10px 20px 10px 20px;
          background-color:blue;
          border-radius: 20px;
        }

        .proceed-button:hover{
            background-color: rgb(58, 105, 233);
            cursor:pointer;
        }
        .proceed-button-text{
            color:white;
            text-decoration: none;
            padding-left:110px;
        }

        .cancel-order{
            width: 30%;
            background-color:white;
            margin: 20px auto;
            padding-bottom: 40px;
            padding-left:10px;
        }

        .cancel-order-text{
            text-decoration: none;
        }

        .cancel-order-text:hover{
            font-weight: 800;
        }
 </style>

</head>



<body>

<div class="card">

<img class="hero-image" src="file:///C:/Users/richa/OneDrive/Desktop/Challenges/order-summary-component-main/images/illustration-hero.svg" 
alt="image">
 <div class="center-text-width">

   <div class="Center-text">
    <h1 class="header">Order Summary  </h1>
    <p>You can now listen to millions of songs, audiobooks, 
        and podcasts on any device anywhere you like!</p> 
   </div> 

   <div class="annualplan-container">
     <img class="music-logo" src="file:///C:/Users/richa/OneDrive/Desktop/Challenges/order-summary-component-main/images/icon-music.svg"
        alt="music-logo">
     <div class="annual-plan-text">
      <h1>Annual Plan</h1>
      <p class="price">$59.99/year</p>
     </div>
      <a href="#" class="change"> Change </a>
   </div>

   <div class="proceed-button">
    <a href="#" class="proceed-button-text">Proceed to Payment</a>
   </div>

    <div class="cancel-order">
      <a href="#" class="cancel-order-text">Cancel Order</a>
    </div>

 </div> 
  
</div>
</body>

</html>
