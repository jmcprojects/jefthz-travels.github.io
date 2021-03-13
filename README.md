<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <link type="text/css" rel="stylesheet" href="/materialize-src/sass/materialize.css" media="screen,projection" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <link rel="stylesheet" href="./../styles/index.css" />
    <title>Jefthz Travels</title>
</head>

<body>
    <!-- ======================================== -->
    <!-- NAV BAR -->
    <!-- ======================================== -->

    <script>
        $(document).ready(function() {
            $(".sidenav").sidenav();
        });
    </script>

    <div class="container navbar-container">
        <nav class="stroke">
            <a href="#" class="sidenav-trigger" data-target="mobile-nav">
                <i class="large material-icons">menu</i>
            </a>

            <div class="nav-wrapper">
                <a href="#" class="brand-logo">
                    <img src="./../icons/jefthz-travels-logo.png" alt="page-logo" />
                </a>
            </div>

            <ul class="right hide-on-med-and-down">
                <li><a class="current" href="./index.html">Home</a></li>
                <li><a href="./destinations.html">Destinations</a></li>
                <li><a href="./adventures.html">Adventures</a></li>
                <li><a href="./about-me.html">About</a></li>
            </ul>
        </nav>
    </div>

    <ul class="sidenav" id="mobile-nav">
        <li><a href="./index.html">Home</a></li>
        <li><a href="./destinations.html">Destinations</a></li>
        <li><a href="./adventures.html">Adventures</a></li>
        <li><a href="./about-me.html">About</a></li>
    </ul>

    <!-- ======================================== -->
    <!-- HOMEPAGE COVER PHOTO -->
    <!-- ======================================== -->
    <div class="valign-wrapper">
        <img src="./../images/homepage-cover-photo.jpg" alt="" class="img-homepage-cover" />
        <div class="homepage-title">
            <p class="text-travel">TRAVEL</p>
            <p class="text-goals">GOALS</p>
            <p class="homepage-tagline">
                <span>Discover</span> the beauty of nature.
            </p>
        </div>
    </div>

    <!-- ======================================== -->
    <!-- HOME BLOG POSTS SECTION -->
    <!-- ======================================== -->
    <div class="home-blog-section">
        <div>
            <div class="page-section-title">
                <h1 class="title-page">FEATURED POSTS</h1>
            </div>
            <div class="row">
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../adventure-blog/bantayan-island.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>BANTAYAN ISLAND</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../destination-blog/cebu-blog-2.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>CAMOTES ISLAND</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../adventure-blog/sumilon-island.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>SUMILON ISLAND</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../adventure-blog/oslob-whale-shark.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>OSLOB WHALE SHARK ENCOUNTER</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../destination-blog/bohol-blog-1.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>BOHOL COUNTRY SIDE</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
                <div class="col l4">
                    <div class="home-blog-wrapper">
                        <a href="./../adventure-blog/mt-manunggal.html">
                            <img src="./../images/blog-sample-image.jpg" alt="" width="100%" height="auto" />
                        </a>
                        <h3>MT. MANUNGGAL</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ======================================== -->
    <!-- TRAVEL EXPERIENCE CONTENT SECTION -->
    <!-- ======================================== -->
    <div class="image-content-wrapper">
        <div class="row">
            <div class="image-content-photo-wrapper">
                <img src="./../images/home-image-content.jpg" alt="" class="responsive-img" />
                <div class="travel-content">
                    <div>
                        <h2>TRAVEL EXPERIENCE</h2>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. Lorem
                            Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ======================================== -->
    <!-- HOME VIDEO POSTS SECTION -->
    <!-- ======================================== -->
    <div class="home-videos-wrapper">
        <div class="page-section-title">
            <h1 class="title-page">TRAVEL VLOGS</h1>
        </div>
        <div class="row">
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/2AtSpxgSj5M?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>BALAMBAN CEBU</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/2AtSpxgSj5M?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>BANTAYAN ISLAND HOPPING</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/2AtSpxgSj5M?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>SAMBOAN FAMOUS WATERFALLS</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/LY4-iOyL6vs?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>SIOMAI SA TISA</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/LY4-iOyL6vs?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>CAMOTES ISLAND HOPPING</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
            <div class="col l4">
                <div class="home-vlogs">
                    <iframe width="100%" height="235px" src="https://www.youtube.com/embed/LY4-iOyL6vs?playlist=QTAMyclHKRk&loop=">
                        https://www.youtube.com/embed/tgbNymZ7vqY
                    </iframe>
                    <h3>LAKE HOLON ADVENTURE</h3>
                    <p>DECEMBER 15, 2020</p>
                </div>
            </div>
        </div>
    </div>

    <a href="#" class="to-top">
        <i class="material-icons">arrow_upward</i>
    </a>
    <script src="./../main.js"></script>

    <!--JavaScript at end of body for optimized loading-->
    <script type="text/javascript" src="js/materialize.min.js"></script>
</body>

<!-- ======================================== -->
<!-- FOOTER SECTION -->
<!-- ======================================== -->
<footer class="page-footer footer-wrapper">
    <div>
        <img src="/icons/jefthz-travels-logo.png" alt="" style="width: 150px; height: auto" />
        <p>Jefthz Travels | Copyright ©2020 | All rights reserved</p>
    </div>
</footer>

</html>
