# Owl-Carousel-Slider-Turkce
Owl Carousel Slider Türkçe Kullanımı 
<!DOCTYPE HTML>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <title>Abdullah Zübeyir Yıldız Owl-Carosel SLider Kullanımı</title>
    <link rel="stylesheet" href="assets/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css">
    <link rel="stylesheet" href="assets/owl-slider/owl.carousel.css" />
    <link rel="stylesheet" href="assets/owl-slider/owl.theme.css" />
    <script type="text/javascript" src="assets/owl-slider/jquery-1.11.1.min.js"></script>
    <script type="text/javascript" src="assets/owl-slider/owl.carousel.min.js"></script>
    <script type="text/javascript">
        $(function(){

            $("#referanslarslider").owlCarousel({
                autoPlay:5000, //otomatik yenilenmesi için
                items :6,//başlangıç item sayısı
                itemsDesktop : [1199,4],//boyut değişirse 1199px altı ise boyut 4 item olsun
                itemsDesktopSmall : [979,2]//979 altı ise 2 tane olsun
            });
        })
    </script>
    <style type="text/css">
        #referanslarslider{width:100%;height:100px;margin:auto;}
        #referanslarslider .item img {display: block;/* width: 100% !important; */ /* height: 200px !important; */margin-left: auto;  margin-right: auto;}
        #referanslarslider .item{/* background: #3fbf79; */;margin:5px;margin-left: auto;margin-right: auto;}
    </style>
</head>
<body>

<div id="referanslarslider">
    <div class="item"><a href="#"><img class="img-fluid mx-auto d-block" src="img/logo1.png" alt="Image" /></a></div>
    <div class="item"><a href="#"><img class="img-fluid mx-auto d-block" src="img/logo2.png" alt="Image" /></a></div>
    <div class="item"><a href="#"><img class="img-fluid mx-auto d-block" src="img/logo3.png" alt="Image" /></a></div>
    <div class="item"><a href="#"><img class="img-fluid mx-auto d-block" src="img/logo4.png" alt="Image" /></a></div>
</div>



</body>
</html>
