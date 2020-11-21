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
                        <li class="active"><a href="single-product.html">Single product</a></li class="active">
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


    <div class="titulo-shop">
        <!-- Titulo -->

        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="shop-titulo text-center">
                        <h2>Single Product</h2>
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
                        <div class="thubmnail-recent">
                            <img src="img/product12.jpg" class="recent-thumb" alt="" style="width:47px;height:42px;">
                            <h2><a href="">CORSAIR CARBIDE</a></h2>
                            <div class="product-sidebar-price">
                                <ins>$150</ins> <del>$115.00</del>
                            </div>
                        </div>
                    </div>

                    <div class="single-sidebar">
                        <h2 class="sidebar-title">Recent Posts</h2>
                        <ul>
                            <li><a href="">LOGITECH G502</a></li>
                            <li><a href="">COOLING RGB</a></li>
                            <li><a href="">PURE BASE 500DX</a></li>
                            <li><a href="">CORSAIR VIRTUOSO</a></li>
                            <li><a href="">LOGITECH G560</a></li>
                        </ul>
                    </div>
                </div>

                <div class="col-md-8">
                    <div class="product-content-right">
                        <div class="product-breadcroumb">
                            <a href="">Home</a>
                            <a href="">Category Name</a>
                            <a href="">PURE BASE 500DX</a>
                        </div>

                        <div class="row">
                            <div class="col-sm-6">
                                <div class="product-images">
                                    <div class="product-main-img">
                                        <img src="img/product11.jpg" style="width:237px;height:232px;">
                                    </div>

                                    <div class="product-gallery">
                                        <img src="img/product11.jpg" style="width:47px;height:42px;">
                                        <img src="img/product11.jpg" style="width:47px;height:42px;">
                                        <img src="img/product11.jpg" style="width:47px;height:42px;">
                                    </div>
                                </div>
                            </div>

                            <div class="col-sm-6">
                                <div class="product-inner">
                                    <h2 class="product-name">PURE BASE 500DX</h2>
                                    <div class="product-inner-price">
                                        <ins>$199.00</ins> <del>$299.00</del>
                                    </div>

                                    <form action="" class="cart">
                                        <div class="quantity">
                                            <input type="number" size="4" class="input-text qty text" title="Qty" value="1" name="quantity" min="1" step="1">
                                        </div>
                                        <button class="add_to_cart_button" type="submit">Add to cart</button>
                                    </form>

                                    <div role="tabpanel" class="tab-pane fade in active" id="home">
                                        <h2>Product Description</h2>
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tristique, diam in consequat iaculis, est purus iaculis mauris, imperdiet facilisis ante ligula at nulla. Quisque volutpat nulla risus, id maximus ex aliquet ut. Suspendisse potenti. Nulla varius lectus id turpis dignissim porta. Quisque magna arcu, blandit quis felis vehicula, feugiat gravida diam. Nullam nec turpis ligula. Aliquam quis blandit elit, ac sodales nisl. Aliquam eget dolor eget elit malesuada aliquet. In varius lorem lorem, semper bibendum lectus lobortis ac.</p>
                                        <p>Mauris placerat vitae lorem gravida viverra. Mauris in fringilla ex. Nulla facilisi. Etiam scelerisque tincidunt quam facilisis lobortis. In malesuada pulvinar neque a consectetur. Nunc aliquam gravida purus, non malesuada sem accumsan in. Morbi vel sodales libero.</p>
                                    </div>

                                </div>
                            </div>
                        </div>


                        <h2>Related Products</h2>

                        <div class="row">
                            <div class="column">
                                <img src="img/product15.jpg" style="width:137px;height:132px;">
                                <h3><a href="">Sony Smart</a></h3>
                                <ins>$700.00</ins> <del>$100.00</del>
                            </div>
                            <div class="column">
                                <img src="img/product8.jpg" style="width:137px;height:132px;">
                                <h3><a href="">Sony Smart</a></h3>
                                <ins>$700.00</ins> <del>$100.00</del>
                            </div>
                            <div class="column">
                                <img src="img/product7.jpg" style="width:137px;height:132px;">
                                <h3><a href="">Sony Smart</a></h3>
                                <ins>$700.00</ins> <del>$100.00</del>
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