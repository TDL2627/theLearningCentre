<template>
    <div id="home">
        <div class="relative overflow-hidden">
            <div class="max-w-7xl mx-auto text-center">
                <nav id="nav2">
               
 <a class="homie" href="#">
                    <img class="navpic" src="../assets/hand.png" alt="logo">
                    </a>
                    <a href="#about" class="linky1 font-medium ">About</a>
                    <a href="#gallery" class="linky2 font-medium ">Gallery</a>
                    <a href="#team" class="linky1 font-medium ">Team</a>
                    <a href="#testimonials"  class="linky2 font-medium ">Testimonials</a>
                    <a href="#rules" class="linky1 font-medium ">Rules</a>
                    <a href="#contact" class="linky2 font-medium ">Contact</a>
                  
                      
                </nav>

                <div class="sm:text-center lg:text-left">
                    <div class="intro">
                        <h1 class="
                text-4xl
                tracking-tight
                font-extrabold
                text-gray-900
                sm:text-5xl
                md:text-6xl
              ">
                            <span class="block inline text-pink-500">T</span><span style="color: white" class="
                  block
                  inline
                  animate__animated
                  animate__fadeInDown
                  animate__slow
                  animate__delay-1s
                ">HE</span>
                            <br />
                            <span class="block text-yellow-500 inline">L</span><span style="color: white" class="
                  block
                  inline
                  animate__animated
                  animate__fadeInDown
                  animate__slow
                  animate__delay-2s
                ">EARNING</span><br />
                            <span class="block text-blue-500 inline">C</span><span style="color: white" class="
                  block
                  inline
                  animate__animated
                  animate__fadeInDown
                  animate__slow
                  animate__delay-3s
                ">ENTRE</span><br />
                        </h1>
                    </div>

                    <br />
                    <h3 class="slogan">ADAPTED LEARNING SPECIALIST</h3>

                    <br /><br />

                    <p class="vm">
                        <span class="block inline text-pink-500">VISION : </span><span style="color: white"
                            class="block inline">Inclusive learning for all.</span>
                        <br />
                        <span class="block inline text-blue-500">MISSION : </span><span style="color: white"
                            class="block inline">If I don't learn the way you teach then teach the way I
                            learn.</span>
                        <br />
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style scoped>
#home {
    height: 100vh;
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
        url("../assets/kiddo.jpg");
}

#nav2 {
    position: fixed;
    top: 0;
    left: 0;
    height: 60px;
    padding-top: 20px;
    width: 100%;
    z-index: 123456789;
    background: black;
}

.intro {
    margin-left: 40%;
    margin-top: 10%;
}

.slogan {
    text-align: center;
    color: white;
}
.navpic{
    height: 50px;
    margin: 10px;
}
  a{
    border-radius: 25px;
    text-decoration: none;
  }
  .linky1{
border: 5px solid yellow;
padding: 5px;
color: yellow;
margin: 10px;


  }
  .linky2{
    padding: 5px;
border: 5px solid pink;
color: pink;
margin: 10px;
  }

  .linky1:hover{
    background: yellow;
    color: black;
  }
  .linky2:hover{
    background: pink;
     color: black;
  }
.homie{
 position: fixed;
 top: 0;
 left: 0;
}
.vm{
    text-align: start;
    padding-left:20% ;
}
@media screen and (max-width: 800px) {
    .intro {
        margin: 0;
        margin-top: 45%;
        margin-left: 5%;
        text-align: start;
    }

    #nav2 {
        display: none;
    }
    .vm{
    text-align: start;
    padding-left:5% ;
}
}
</style>