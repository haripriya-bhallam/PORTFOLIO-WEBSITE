# PORTFOLIO-WEBSITE
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-secondary">
        <div class="container">
            <a class="navbar-brand logo" text-white href="#">J.</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-link active" id="home" href="#">Home <span class="sr-only">(current)</span></a>
                    <a class="nav-link" id="aboutme" href="#">About me</a>
                    <a class="nav-link" id="project" href="#">Project</a>
                    <a class="nav-link" id="recentblogs" href="#">Recent Blogs</a>
                    <a class="nav-link" id="testimonial" href="#">Testimonial</a>
                </div>
            </div>
        </div>
    </nav>
    <div class="banner-section d-flex flex-column justify-content-center">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-5 order-md-2">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/portfolio-banner-img.png" class="image pt-1" />
                </div>
                <div class="col-12 col-md-7 order-md-1">
                    <h1 class="heading">Hey,I am <span class="span">Jenny</span></h1>
                    <p class="paragraph">I am a Frontend Developer & Mentor.</p>
                    <button class="button">Contact Me</button>
                </div>
            </div>
        </div>




    </div>

</body>

</html>
CASCADING STYLE SHEET (CSS)
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.banner-section {
    background-color: #191a1d;
    height: 100vh;

}

.image {
    width: 100%;

}

.heading {
    color: white;
    font-family: "roboto";
    font-size: 45px;
    font-weight: 500;
}

.paragraph {
    color: #9aa5b1;
    font-family: "roboto";
    font-size: 24px;
    font-weight: 400;
}

.button {
    height: 40px;
    width: 120px;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
    background-color: #4b6cc1;
    color: white;
    border-radius: 8px;
    border-width: 0px;
}

.span {
    color: #4b6cc1;
    font-family: "roboto";
    font-size: 45px;
    font-weight: 500;
}

#home {
    color: white;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
}

#aboutme {
    color: white;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
}

#project {
    color: white;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
}

#recentblogs {
    color: white;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
}

#testimonial {
    color: white;
    font-family: "roboto";
    font-size: 15px;
    font-weight: normal;
}

.logo {
    border-style: solid;
    border-color: #4b6cc1;
    padding-left: 10px;
    padding-right: 10px;
}
