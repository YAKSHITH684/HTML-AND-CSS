index.html
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/vr-logo-img.png" class="food-munch-logo" />
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-link active" id="navItem1" href="#">
                        Home
                        <span class="sr-only">(current)</span>
                    </a>
                    <a class="nav-link" id="navItem2" href="#">Products</a>
                    <a class="nav-link" id="navItem3" href="#">Recent Blogs</a>
                    <a class="nav-link" id="navItem4" href="#">Delivery & payments</a>
                </div>
            </div>
        </div>
    </nav>
    <div class="banner-section-bg-container d-flex flex-column justify-content-center">
        <div class="text-center">
            <h1 class="banner-heading"> THE REVOLUTION IN VIRTUAL REALITY</h1>
            <button class="custom-button"> VIEW MORE</button>
        </div>
    </div>
</body>

</html>


#CSS
.food-munch-logo {
    width: 70px;
    height: 50px;
}

#navItem1 {
    color: #323f4b;
    font-family: "Times New Roman";
}

#navItem2 {
    color: #323f4b;
    font-family: "Times New Roman";
}

#navItem3 {
    color: #323f4b;
    font-family: "Times New Roman";
}

#navItem4 {
    color: #323f4b;
    font-family: "Times New Roman";
}

.banner-section-bg-container {
    height: 100vh;
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/vr-banner-bg.png");
    background-size: cover;
}

.banner-heading {
    color: white;
    font-family: "bree serif";
    font-size: 40px;
    font-weight: 300;
    text-align: center;
}

.custom-button {
    width: 130px;
    height: 45px;
    color: white;
    background-color: #1a2137;
    border-width: 0px;
    border-radius: 8px;
    margin-right: 10px;
}



index.html
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="pt-05 pb-05">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="vr-features-section-heading">Features</h1>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/easy-connect-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">Easy to connect</h1>
                        <p class="vr-features-card-description">Instead of viewing a screen in front of them, user are immersed and able to interact with 3D worlds.</p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/vr-capability-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">VR Capability</h1>
                        <p class="vr-features-card-description">Virtual reality (VR) can create an environmental similar to or completely different from the real world.</p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/video-games-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">Video games</h1>
                        <p class="vr-features-card-description"> Ability to recongizehand motion,evolvign interactions and gameplay in VR.</p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/interaction-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">Interaction</h1>
                        <p class="vr-features-card-description">Interaction refers to the<span class="interaction"> natural interactions</span> between the user and the virtual scene.</p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/easy-play-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">Easy to play</h1>
                        <p class="vr-features-card-description">In 360-degree video,the locations of viewers are fixed,viewers are limited to the angles captured by the cameras.</p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="p-3 mb-3 text-center">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/experience-img.png" class="vr-features-card-image" />
                        <h1 class="vr-features-card-title mt-3">Awesome Experience</h1>
                        <p class="vr-features-card-description">Virtual reality(VR) is a simulated experience that can be similar to or completely different from the real world.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>


toursit.css
.vr-features-section-heading {
    color: #1f2933;
    font-family: "Roboto";
    font-size: 26px;
    font-weight: bold;
}

.vr-features-card-image {
    width: 64px;
    height: 64px;
}

.vr-features-card-title {
    color: #1f2933;
    font-family: "Roboto";
    font-size: 22px;
    font-weight: 500;
}

.vr-features-card-descripition {
    color: #7b8794;
    font-family: "Roboto";
    font-size: 16px;
}

.interaction {
    color: #1f2933;
    font-style: italic;
    font-weight: bold;
}
