<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/2e29afbbfe.js" crossorigin="anonymous"></script>
    <link rel="Website icon" href="Hiduribots_-_black_-_Smaller bez pozadi.png">
    <title>Hiduribots</title>
</head>
<body>
    <nav>
        <ul>
            <a href="Hiduribots.html" class="Nadpis"><img src="Hiduribots_-_white_-_smaller-removebg-preview.png" class="Logo">Hiduribots</a>
            <a href="Hiduribots.html" class="Home"><i class="fa-solid fa-house"><span>Home</span></i></a>
            <a href="#Details" class="Details"><i class="fa-solid fa-magnifying-glass"><span>Details</span></i></a>
            <a href="#Gallery" class="Gallery"><i class="fa-solid fa-image"><span>Gallery</span></i></a>
            <a href="#Contact" class="Contact"><i class="fa-solid fa-feather"><span>Contact</span></i></a>
        </ul>
    </nav>
    <h3 style="top: 20%; color: black; position: absolute; left: 40%;">Zde dát obrázek inteligentního týmu</h3>
    <img src="zdedatobrazek2.png" class="zdedatobrazek">
    <section id="Details">
    </section>
    <section>
        <div class="Home-bakcground">
            <h2 class="Nadpis-H">Hiduribots</h2>
            <div class="Info1">
                <h2 class="h21">Team members</h2>
                <p class="p1">
                  <span class="s0">Couches:Nikola Pecková, Kateřina Pechková</span> 
                  <span class="s1">Leaders: Petr Karásek </span>
                  <span class="s2">Programators: Bruno Legeza, Jan Stejskal, Dominik Zajíček, Vojta Policer</span>
                  <span class="s3">Engineer: Petr Holbík, Štěpán Komínek, Kryštof Hudák</span>
                 <span class="s4">Rider: Jakub Konejl, Lukáš Malec</span>
                 <span class="s5">Photograph: Ondřej Sak</span>
                 <span class="s6">PR: Matěj Danyi</span>
                </p>
            </div>
            <div class="Info2">
                <h2 class="h22">Victory points</h2>
                <p class="p2">
                  We are incompetent and we haven't won anything yet...
                </p>
            </div>
            <div class="Info3">
                <h2 class="h23">Radom information 4</h2>
                <p class="p3">Just write some information about the team. 
                  Because I don't remember it because my IQ is lower than a french frie. 
                  If you want pancakes, make them and if you want shampoo, boil it and now let me cook.
                </p>
            </div>
            <div class="Info4">
                <h2 class="h24">About us</h2>
                <p class="p4">
                  Our team was founded 31th of october 2024. Our coach 2024. We are pupils of secondary school ZS&MS Jižní.
                </p>
            </div>
        </div>
    </section>
    <section id="Gallery">
    </section>
    <section>
        <div class="GalleryBackground">
            <h2 class="Nadpis-G">Photo Gallery</h2>
            <div class="gal-31-10-24">
                <h1 class="Nadpis-31-10-24">31.10.2024</h1>
                <div class="slideshow-container">

                    <div class="mySlides fade">
                      <div class="numbertext">1 / 5</div>
                      <img src="photogallery/31-10-24-1.png" style="width:100%">
                      <div class="text"></div>
                    </div>
                    
                    <div class="mySlides fade">
                      <div class="numbertext">2 / 5</div>
                      <img src="photogallery/31-10-24-2.png" style="width:100%">
                      <div class="text"></div>
                    </div>
                    
                    <div class="mySlides fade">
                      <div class="numbertext">3 / 5</div>
                      <img src="photogallery/31-10-24-3.png" style="width:100%">
                      <div class="text"></div>
                    </div>

                    <div class="mySlides fade">
                        <div class="numbertext">4 / 5</div>
                        <img src="photogallery/31-10-24-4.png" style="width:100%">
                        <div class="text"></div>
                      </div>

                      <div class="mySlides fade">
                        <div class="numbertext">5 / 5</div>
                        <img src="photogallery/31-10-24-5.png" style="width:100%">
                        <div class="text"></div>
                      </div>
                    
                    <a class="prev" onclick="plusSlides(-1)">⇦</a>
                    <a class="next" onclick="plusSlides(1)">⇨</a>
                    
                    </div>
                    <br>
                    
                    <div style="text-align:center">
                      <span class="dot" onclick="currentSlide(1)"></span> 
                      <span class="dot" onclick="currentSlide(2)"></span> 
                      <span class="dot" onclick="currentSlide(3)"></span> 
                      <span class="dot" onclick="currentSlide(4)"></span> 
                      <span class="dot" onclick="currentSlide(5)"></span> 
                    </div>
            </div>
        </div>
    </section>
        <script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
<section id="Contact">
</section>
<section>
    <div class="Contact-background">
        <h2 class="Nadpis-C">Contact</h2>
        <a href="mailto:Peckova@zsmsjizni.cz" class="sendmail"><span>Send Email</span></a>
        <h5 class="doesntwork">doesn't work? Write on Peckova@zsmsjizni.cz</h5>
        <a href="https://www.instagram.com/hiduribots/" class="a-fa-instagram"><i class="fa-brands fa-instagram"></i></a>
        <a href="https://www.instagram.com/hiduribots/" class="a-fa-whatsapp"><i class="fa-brands fa-whatsapp"></i></a>
</section>
<section>
    <div class="copyright-background">
        <h4 class="copyright-all-right-reserved">(C) All rights reserved Hiduribots</h4>
        <h5 class="Copyright-email">Peckova@zsmsjizni.cz</h5>
        <h5 class="Copyright-creator">Made by Vlastovka <a href="https://github.com/Vlastovka"><i class="fa-brands fa-github"></i></a><a href="mailto:petrkar371@gmail.com"><i class="fa-solid fa-envelope"></i></a></h5>
        <h5 class="Copyright-assist">Assist Legezar</h5>
        <h6 class="easter-egg">Shadow leader Legezar</h6>
      </div>
</section>
</body>
</html>