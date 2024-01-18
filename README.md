<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darshan founder</title>
    <link rel="stylesheet" href="">
  <style>
    *{
    margin: 0;
    padding: 0;
}

body{
    font-family: sans-serif;

}
.contenar{
    max-width: 1200px;
    margin: auto;
}
.lita{
    display: none;
}

#header{
    display: flex;
    justify-content: space-between;
    padding: 0 29px;
    border-bottom: 1px solid gray;
    height: 60px;
    align-items: center;
    
}
.right-hed{
    list-style: none;
    display: flex;
    gap: 40px;
    
}

.hed .right-hed :hover {
    color: rgb(230, 108, 52);
    transition: 0.10s all;
    
}

/* intro to villas */

.intro_img{
    background-image: url(/responsivewebsit/villasimg/banner-01.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    width: 100vw;


}
.intro-img .b{
    color: rgb(255, 92, 51);
}
.contenar2{
    display: flex;
    height: 100vh;
    align-items: center;
}
.btn{
    font-size: 18px;
    border: 2px solid white;
    display: inline-block;
    padding: 2px 10px;
    

    
}

.intro-txt{
    color: white;
    font-size: 35px;
    
}


/* listt sections che aavdu aa  */

.contenar3{
    display: flex;
    justify-content: space-between;
    gap: 25px;
    padding-top: 100px;
}
.intro-img{
    display: flex;
    flex-direction: column;
    gap: 59px;
}
.intro-img h1{
    font-size: 35px;
}

.menu-bar{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 1rem 3rem;
    background-color: white;
    border: 5px groove rgb(156, 146, 146 ,0.2);
    border-radius: 10px;
    
    
}



.map{
    display: flex;
    gap: 1rem;

}


/* video sectionsin this profect */

.cover-img{
    background-image: url(/responsivewebsit/villasimg/video-bg.jpg);
    width: 100%;
    margin-top: 6rem;
    
}
.contenar4{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 6rem;
    color: white;
}
.cover-txt p {
    color: rgb(255, 92, 51);
}
.cover-txt{
    text-align: center;
    gap: 2rem;
    font-size: 2rem;
}

.img-video{
    position: relative;
    margin-top: -9rem;
    top: 11rem;

}
.img-video img{
    border-radius: 10px;
}



/* tempreture section  */



.tempreture{
    display: flex;
    padding-top: 15rem;
    justify-content: space-around;
}
.t34{
    display: flex;
    gap: 2rem;
    background-color:  rgb(234, 77, 37,0.3) ;
    padding: 1rem 4rem;
    border-radius: 10px;
}

.b{
    color: rgb(255, 92, 51);
    font-size: 2rem;
}


/* find section is started */

.contenar5{
    margin-top: 4rem;

}

.find{
    display: flex;
    justify-content: space-between;
    padding-top: 4rem;

}
.find1{
    display: flex;
    flex-direction: column;
    gap: 1rem;
}
.ba{
    color: rgb(255, 92, 51);
}

.find2{
    display: flex;
    gap: 1rem;
    align-self: flex-end;
}

.find2 .or{
    background-color: rgb(255, 92, 51);
    color: white;
    padding: 0.5rem 2rem;
    border-radius: 5px;
}

.find2 .bl1{
    background-color: black;
    color: white;
    padding: 0.5rem 2rem;
    border-radius: 5px;
}
.find2 .bl2{
    background-color: black;
    color: white;
    padding: 0.5rem 2rem;
    border-radius: 5px;
}


/* map section havethi chalu thai che  */

.contenar6{
    display: flex;
    justify-content: space-between;
    padding-top: 4rem;
    padding-bottom: 4rem;
    
    gap: 2rem;
}
.mapb{
    display: flex;
    flex-direction: column;
    gap: 2rem;
    border: 5px groove rgb(130, 130, 130,0.3);
    padding: 2rem 3rem;
    border-radius: 10px;
    
    

}

.map1{
    display: flex;
    justify-content: space-between;
    gap: 3rem;
    
}

.map1-txt{
    line-height: 2rem;
}

.man{
    background-color: black;
    color: white;
    display: inline-block;
    padding: 0.7rem 2rem;
    border-radius: 45px;
    margin-top: 1rem;
}


/* only text section */

.contenar7{
    display: flex;
    justify-content: center;
    text-align: center;
    padding-top: 4rem;
}

.only-txt{
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
}
.gro{
    color: rgb(255, 92, 51);
}


/* footer sections  */


.contenar8{
    padding: 1rem;
    background-color: black;
    color: white;
    text-align: center;
    margin-top: 5rem;
}


/* media screen sizes abouts */

@media (max-width:550px) {
    html{
        font-size: 42.5%;
    }
    .logo h2,.lita{
        font-size: 3rem;
    }
    .hed .right-hed{
        display: none;
    }
    .lita{
        display: inline-block;
    }

    .intro-txt{
        font-size: 4rem;
    }
    
    .img-apartment img{
        max-width: 100%;
    }

    /* alg secrtion */

    
.contenar3{
    gap: 2px;
    padding-top: 68px;
}
.intro-img{
    
    gap: 3rem;
    
}
.intro-img h1{
    font-size: 2rem;
}
.img img{
    max-width: 100%;
}

.menu-bar{
    display: flex;
    flex-direction: column;
    gap: 3rem;
    padding: 0.5rem 2rem;
    background-color: white;
    
    
}

/* cover section start  */

.img-video img{
    max-width: 70%;
    position: relative;
    top: 8rem;
    left: 50%;
    transform: translate(-50%, -50%);
   
}

/* contenar 6 nivat chea  */

.map-img img{
    max-width: 97%;
}
.contenar6{
    gap: 1rem;
}

.mapb{
    gap: 2rem;
    padding: 1rem 1rem;
    
    
    

}

.map1{
    display: flex;
    justify-content: space-between;
    gap: 1rem;
    
}

.map1-txt{
    line-height: 1rem;
    width: 18rem;
}













    
    


}
  </style>
    <script src="https://kit.fontawesome.com/7a4b62b0a4.js" crossorigin="anonymous"></script>

</head>
<body>
    <header id="header" class="hed">
        <div class="logo">
            <h2>VILLA</h2>
        </div>
        <div class="lita">
            <i class="fas fa-bars"></i>
        </div>
        <div class="right-hed">
            <li>Home</li>
            <li>Properties</li>
            <li>Propety Details</li>
            <li>Contact Us</li>
        </div>
    </header>
     <section class="intro_img">
        <div class="contenar contenar2">
            <div class="intro-txt">
                <p class="btn">Gamph,<span>Gujarat</span></p>
                <h1>HURRY! <br> GET THE BEST <br> VILLA FOR YOU</h1>

            </div>
        </div>

    </section>
    <section>
        <div class="contenar contenar3">
            <div class="img-apartment">
                <img src="/responsivewebsit/villasimg/featured.jpg" alt="">
            </div>
            <div class="intro-img">
                <h1>Best <br> Appartment & <br> seaview</h1>
                <p class="b">Best useful links ?</p>
                <p>Get <b>the best villa</b>  website template in gamph <br> and around for your business. Templemo <br> provides you the best free sofa and fee frez in the <br> workid please tell your frinds about it.
                </p>
                <p>How does this work ?</p>
                <p>Why is villa Agency the best ?</p>
            </div>
            <div class="menu-bar">
                <div class="map">
                    <div class="img"><img src="/responsivewebsit/villasimg/info-icon-01.png" alt="">
                    </div> 
                    <div class="bar-txt">
                        <h3>250 m2</h3>
                        <p>Total filot spoce</p>
                    </div>                   
                </div>
                <div class="map">
                    <div class="img"><img src="/responsivewebsit/villasimg/info-icon-02.png" alt="">
                    </div> 
                    <div class="bar-txt">
                        <h3>Contract</h3>
                        <p>Contract REady</p>
                    </div>                   
                </div>
                <div class="map">
                    <div class="img"><img src="/responsivewebsit/villasimg/info-icon-03.png" alt="">
                    </div> 
                    <div class="bar-txt">
                        <h3>Payment</h3>
                        <p>Payment Process</p>
                    </div>                   
                </div>
                <div class="map">
                    <div class="img"><img src="/responsivewebsit/villasimg/info-icon-04.png" alt="">
                    </div> 
                    <div class="bar-txt">
                        <h3>Safety</h3>
                        <p>24/7 Under Control</p>
                    </div>                   
                </div>
            </div>
        </div>
    </section>
    <section class="cover-img">
        <div class="contenar contenar4">
            <div class="cover-txt">
                <p>IVIDEO VIEW</p>
                <h1>Get Closer View & <br> different Feeling</h1>
            </div>
            <div class="img-video">
                <img src="/responsivewebsit/villasimg/video-frame.jpg" alt="">
            </div>
        </div>

    </section>
    <section class="contenar">
        <div class="tempreture">
            <div class="t34">
                <h1 class="b">34</h1>
                <p>Buildings <br>
                    Finished Now
                </p>
            </div>
            <div class="t34">
                <h1 class="b">12</h1>
                <p>Years <br>Experience
                    
                </p>
            </div>
            <div class="t34">
                <h1 class="b">24</h1>
                <p>Awwards <br> Won 2024
                </p>
            </div>



        </div>
    </section>
    <section class="contenar contenar5">
        <div class="find">
            <div class="find1">
                <p class="ba">I BEST DEAL</p>
                <h1>Find Your Best Deal <br> Right NOw!</h1>
            </div>
            <div class="find2">
                <p class="or">Appartment</p>
                <p class="bl1">Villa House</p>
                <p class="bl2">Penthousoe</p>
            </div>
        </div>

    </section>
     <section class="contenar contenar6">
         <div class="mapb">
             <div class="map1">
                 <p class="darshan">Totol Flot Space</p>
                 <h3>185 m2</h3>
             </div>
             <div class="map1">
                <p class="darshan">Floor number</p>
                <h3>26th</h3>
            </div>
            <div class="map1">
                <p>Number of rooms</p>
                <h3>4</h3>
            </div>
            <div class="map1">
                <p class="darshan">Parking Avalable</p>
                <h3>Yes</h3>
            </div>
            <div class="map1">
                <p class="darshan">Payment Process</p>
                <h3>Bank</h3>
            </div>
         </div>
         <div class="map-img">
             <img src="/responsivewebsit/villasimg/deal-01.jpg" alt="">
         </div>
         <div class="map1-txt">
             <h5>Extra info About Property</h5>
             <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Neque nam aliquid perferendis quis earum consequatur! Repellat facere nihil soluta, optio sunt dolores quaerat rem beatae nisi, debitis vel ex, quibusdam minima voluptates quod libero magni sequi temporibus odit atque? Voluptatum repudiandae optio placeat. Asperiores officia accusamus molestiae impedit minus perferendis?</p>

             <h3 class="man"> Schedule a visit</h3>
         </div>
     </section>
    <section class="contenar contenar7">
         <div class="only-txt">
             <p class="gro">IPROPERES
             </p>
             <h1>We provide The <br> Best Property You <br> Like</h1>
         </div>

     </section>
     <footer class="contenar8">
         <p>Copyright Darshan Agency co.</p>

     </footer>
     -->
</body>
</html>
