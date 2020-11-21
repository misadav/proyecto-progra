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
                        <li class="active"><a href="cart.html">Cart</a></li>
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
                        <h2>Shopping Cart</h2>
                    </div>
                </div>
            </div>
        </div>
    </div> <!-- Titulo -->




    <div class="single-product-area">
        <!-- Barra de la izquierda -->
        <div class="botones-abajo"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <div class="single-sidebar">
                        <h2 class="sidebar-title">Search Products</h2>
                        <form action="">
                            <input type="text" placeholder="Search products...">
                            <input type="button" value="Search">
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
                </div><!-- Barra de la izquierda -->



                <div class="col-md-8">
                    <!-- Tabla centro -->
                    <div class="product-content-right">
                        <div class="woocommerce">
                            <form method="post" action="#">
                                <table cellspacing="0" class="shop_table cart">
                                    <thead>
                                        <tr>
                                            <th class="product-remove">&nbsp;</th>
                                            <th class="product-thumbnail">&nbsp;</th>
                                            <th class="product-name">Product</th>
                                            <th class="product-price">Price</th>
                                            <th class="product-quantity">Quantity</th>
                                            <th class="product-subtotal">Total</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr class="cart_item">
                                            <td class="product-remove">
                                                <a class="remove" href="#">×</a>
                                            </td>

                                            <td class="product-thumbnail">
                                                <a><img style="width:47px;height:42px;" class="shop_thumbnail" src="img/product1.jpg"></a>
                                            </td>

                                            <td class="product-name">
                                                <a>Ship Your Idea</a>
                                            </td>

                                            <td class="product-price">
                                                <span class="amount">$25.00</span>
                                            </td>

                                            <td class="product-quantity">
                                                <div class="quantity buttons_added">
                                                    <input type="number" size="4" class="input-text qty text" title="Qty" value="1" min="0" step="1">
                                                </div>
                                            </td>

                                            <td class="product-subtotal">
                                                <span class="amount">$25.00</span>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td class="actions" colspan="6">
                                                <div class="coupon">
                                                    <label for="coupon_code">Coupon:</label>
                                                    <input type="text" placeholder="Coupon code" value="" id="coupon_code" class="input-text" name="coupon_code">
                                                    <button type="button">Apply Coupon</button>
                                                </div>
                                                <input type="button" value="Update Cart">
                                                <input type="button" value="Checkout">
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </form>

                            <div class="cart-collaterals">


                                <div class="cross-sells">
                                    <h2>You may be interested in...</h2>
                                    <ul class="products">
                                        <li class="product">
                                            <a>
                                                <img style="width:207px;height:202px;" class="attachment-shop_catalog wp-post-image" src="img/product8.jpg">
                                                <h3>Ship Your Idea</h3>
                                                <span class="price"><span class="amount">$20.00</span></span>
                                            </a>

                                        </li>

                                        <li class="product">
                                            <a>
                                                <img style="width:207px;height:202px;" class="attachment-shop_catalog wp-post-image" src="img/product7.jpg">
                                                <h3>Ship Your Idea</h3>
                                                <span class="price"><span class="amount">$20.00</span></span>
                                            </a>

                                        </li>
                                    </ul>
                                </div>


                                <div class="cart_totals ">
                                    <h2>Cart Totals</h2>

                                    <table cellspacing="0">
                                        <tbody>
                                            <tr class="cart-subtotal">
                                                <th>Cart Subtotal</th>
                                                <td><span class="amount">$25.00</span></td>
                                            </tr>

                                            <tr class="shipping">
                                                <th>Shipping and Handling</th>
                                                <td>Free Shipping</td>
                                            </tr>

                                            <tr class="order-total">
                                                <th>Order Total</th>
                                                <td><strong><span class="amount">$25.00</span></strong> </td>
                                            </tr>
                                        </tbody>
                                    </table>
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
                            <li>
                                <a href="#">
                                    Mouse
                                </a>
                            </li>
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