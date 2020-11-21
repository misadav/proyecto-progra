<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Gameshop</title>
    <link href="css/bootstrap.min.css" rel="stylesheet" />
    <link href="css/Carrusel.css" rel="stylesheet" />
    <link href="css/General.css" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="js/carruseljs.js"></script>

</head>


<body>

    <div class="area-del-header">
        <!-- Area del header -->
        <div class="container">
            <div class="row">
                <div class="col-sm-6">
                    <div class="logo">
                        <h1><a href="./"><img src="img/logo.png"></a></h1>

                    </div>
                </div>

                <div class="col-sm-6">
                    <div class="carrito-caja">
                        <a href="cart.html">Cart - <span class="monto">$100</span> <i class="fa fa-shopping-cart"></i> </a>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- Area del header -->

    <div class="barra-principal">
        <!-- Area del navigation bar -->
        <div class="container">
            <div class="row">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                </div>
                <div class="navbar-collapse collapse">
                    <ul class="nav navbar-nav">
                        <li class="active"><a href="index.html">Home</a></li>
                        <li><a href="shop.html">Shop page</a></li>
                        <li><a href="single-product.html">Single product</a></li>
                        <li><a href="cart.html">Cart</a></li>
                        <li><a href="checkout.html">Checkout</a></li>
                        <li><a href="#">Category</a></li>
                        <li><a href="#">Others</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div> <!-- Area del navigation bar -->
    <!-- Slideshow container -->
    <div class="slideshow-container">

        <!-- Carrusel con imagenes -->
        <div class="mySlides">
            <a href="single-product.html">
                <img src="img/slider1.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product2.html">
                <img src="img/slider2.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product3.html">
                <img src="img/slider3.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product4.html">
                <img src="img/slider4.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product5.html">
                <img src="img/slider5.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product6.html">
                <img src="img/slider6.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product7.html">
                <img src="img/slider7.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product8.html">
                <img src="img/slider8.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product9.html">
                <img src="img/slider9.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product10.html">
                <img src="img/slider10.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product11.html">
                <img src="img/slider11.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product12.html">
                <img src="img/slider12.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product13.html">
                <img src="img/slider13.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product14.html">
                <img src="img/slider14.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product15.html">
                <img src="img/slider15.jpg">
            </a>
        </div>

        <div class="mySlides">
            <a href="single-product16.html">
                <img src="img/slider16.jpg">
            </a>
        </div>


        <!-- Next and previous buttons -->
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    <br>

    <!-- The dots/circles -->
    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
        <span class="dot" onclick="currentSlide(5)"></span>
        <span class="dot" onclick="currentSlide(6)"></span>
        <span class="dot" onclick="currentSlide(7)"></span>
        <span class="dot" onclick="currentSlide(8)"></span>
        <span class="dot" onclick="currentSlide(9)"></span>
        <span class="dot" onclick="currentSlide(10)"></span>
        <span class="dot" onclick="currentSlide(11)"></span>
        <span class="dot" onclick="currentSlide(12)"></span>
        <span class="dot" onclick="currentSlide(13)"></span>
        <span class="dot" onclick="currentSlide(14)"></span>
        <span class="dot" onclick="currentSlide(15)"></span>
        <span class="dot" onclick="currentSlide(16)"></span>
    </div>


    <div class="iconos-abajo">
        <div class="botones-abajo"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo1">
                        <i class="fa fa-refresh"></i>
                        <p>30 Days return</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo2">
                        <i class="fa fa-truck"></i>
                        <p>Free shipping</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo3">
                        <i class="fa fa-lock"></i>
                        <p>Secure payments</p>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="single-promo promo4">
                        <i class="fa fa-gift"></i>
                        <p>New products</p>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- End promo area -->



    <div class="footer-top-area"> <!-- Footer  Area -->
        <div class="botones-abajo"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-3 col-sm-6">
                    <div class="footer-about-us">
                        <h2><span>Gamerz</span></h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis sunt id doloribus vero quam laborum quas alias dolores blanditiis iusto consequatur, modi aliquid eveniet eligendi iure eaque ipsam iste, pariatur omnis sint! Suscipit, debitis, quisquam. Laborum commodi veritatis magni at?</p>
                        <div class="footer-social">
                            <a href="#"><i class="fa fa-facebook"></i></a>
                            <a href="#"><i class="fa fa-twitter"></i></a>
                            <a href="#"><i class="fa fa-youtube"></i></a>
                            <a href="#"><i class="fa fa-linkedin"></i></a>
                        </div>
                    </div>
                </div>

                <div class="col-md-3 col-sm-6">
                    <div class="footer-menu">
                        <h2 class="footer-wid-title">User Navigation </h2>
                        <ul>
                            <li><a href="#">My account</a></li>
                            <li><a href="#">Order history</a></li>
                            <li><a href="#">Wishlist</a></li>
                            <li><a href="#">Vendor contact</a></li>
                            <li><a href="#">Front page</a></li>
                        </ul>
                    </div>
                </div>

                <div class="col-md-3 col-sm-6">
                    <div class="footer-menu">
                        <h2 class="footer-wid-title">Categories</h2>
                        <ul>
                            <li><a href="#">Keyboards</a></li>
                            <li><a href="#">PC Cases</a></li>
                            <li><a href="#">Headsets</a></li>
                            <li><a href="#">Computers</a></li>
                            <li><a href="#">
                                Mouse</a></li>
                        </ul>
                    </div>
                </div>

                <div class="col-md-3 col-sm-6">
                    <div class="footer-newsletter">
                        <h2 class="footer-wid-title">Newsletter</h2>
                        <p>Sign up to our newsletter and get exclusive deals you wont find anywhere else straight to your inbox!</p>
                        <div class="newsletter-form">
                            <form action="#">
                                <input type="email" placeholder="Type your email">
                                <input type="submit" value="Subscribe">
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- Footer  Area -->





    <script>
        showSlides(20);
    </script>

</body>
</html>