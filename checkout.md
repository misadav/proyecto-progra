<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Gameshop</title>
    <link href="css/bootstrap.min.css" rel="stylesheet" />
    <link href="css/General.css" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
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
                        <li><a href="index.html">Home</a></li>
                        <li><a href="shop.html">Shop page</a></li>
                        <li><a href="single-product.html">Single product</a></li>
                        <li><a href="cart.html">Cart</a></li>
                        <li class="active"><a href="checkout.html">Checkout</a></li>
                        <li><a href="#">Category</a></li>
                        <li><a href="#">Others</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div> <!-- Area del navigation bar -->


    <div class="titulo-shop">
        <!-- Titulo -->

        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="shop-titulo text-center">
                        <h2>Checkout</h2>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- Titulo -->




    <div class="single-product-area">
        <div class="botones-abajo"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="single-sidebar">
                        <h2 class="sidebar-title">Search Products</h2>
                        <form action="">
                            <input type="text" placeholder="Search products...">
                            <input type="submit" value="Search">
                        </form>
                    </div>

                    <div class="single-sidebar">
                        <h2 class="sidebar-title">Products</h2>
                        <div class="thubmnail-recent">
                            <img src="img/product1.jpg" class="recent-thumb" alt="" style="width:47px;height:42px;">
                            <h2><a href="">PBT KEYCAPS</a></h2>
                            <div class="product-sidebar-price">
                                <ins>$299.00</ins> <del>$199.00</del>
                            </div>
                        </div>
                        <div class="thubmnail-recent">
                            <img src="img/product16.jpg" class="recent-thumb" alt="" style="width:47px;height:42px;">
                            <h2><a href="">NOBLECHAIRS EPIC</a></h2>
                            <div class="product-sidebar-price">
                                <ins>$350</ins> <del>$255.00</del>
                            </div>
                        </div>
                        <div class="thubmnail-recent">
                            <img src="img/product14.jpg" class="recent-thumb" alt="" style="width:47px;height:42px;">
                            <h2><a href="">RAZER NAGA PRO</a></h2>
                            <div class="product-sidebar-price">
                                <ins>$250</ins> <del>$199.00</del>
                            </div>
                        </div>
                    </div>

                    <div class="single-sidebar">
                        <h2 class="sidebar-title">Recent Posts</h2>
                        <ul>
                            <li><a href="">LOGITECH G502</a></li>
                            <li><a href="">COOLING RGB</a></li>
                            <li><a href="">PURE BASE 500DX</a></li>
                        </ul>
                    </div>
                </div>



                <div class="col-md-8">
                    <div class="product-content-right">
                        <div class="woocommerce">
                            <div id="customer_details" class="col2-set">
                                <div class="col-1">
                                    <div class="woocommerce-billing-fields">
                                        <h3>Billing Details</h3>
                                        <p>
                                            <label>Country</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>First Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Last Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Company Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Address</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Town / City</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>County</label>
                                            <input type="text" placeholder="">
                                        </p>



                                    </div>
                                </div>

                                <div class="col-2">
                                    <div class="woocommerce-shipping-fields">
                                        <h3>Ship to a different address?</h3>
                                        <p>
                                            <label>Country</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>First Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Last Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Company Name</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Address</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>Town / City</label>
                                            <input type="text" placeholder="">
                                        </p>

                                        <p>
                                            <label>County</label>
                                            <input type="text" placeholder="">
                                        </p>
                                    </div>

                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="footer-top-area">
        <!-- Footer  Area -->
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
                            <li><a href="#">Gaming Mouse</a></li>
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





</body>
</html>