<!--This code serves as property of Pheletso Mashalane-->
<!-- This code is coded using HTML, CSS, BOOTSTRAP and JS-->
<!--This is a simple web based Portfolio-->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
        Portfolio Resume
    </title>
    <!--Font Awesome-->
    <link rel="stylesheet" href="https://use.fontawesome.com/3e6212cda6.css">
    <link rel="stylesheet" type="text/css" href="style.css">
    <!--Jquery-->
    <script src="https://code.jquery.com/jquery-3.6.0.js" integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    <!-- bootstrap cdn -->
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Arvo&display=swap" rel="stylesheet">
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
</head>


<body>

    <!--header Section-->
    <div class="container-fluid">
        <div class="col-12 col-sm-4 align-items-center">
            <header>
                <div class="user">
                    <img src="assets/background.PNG" class="profilePic">
                    <h3 class="name">Pheletso Mashalane</h3>
                    <p class="post">Statistician | Computer Scientist</p>
                </div>

                <nav class="navbar">
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="about.html">About</a></li>
                        <li><a href="education.html">Education</a></li>
                        <!--<li><a href="#">Contact</a></li>-->
                    </ul>
                </nav>
            </header>
        </div>

        <div class="col-12 col-sm-8 align-items-center">

            <!--Content Section-->

            <div class="containers">
                <section class="home" id="home">
                    <h3 class="name">Welcome</h3>
                    <h3 class="post">My Name is <span> Pheletso T. E. Mashalane</span></h3>
                    <h3 class="post">I am a <span class="typing-text">Computer Sciences Graduate </span></h3>
                    <a href="mailto:mashalaneevanspheletso@gmail.com"><button class="btn-hire">Hire Me</button></a>

                    <div class="share">
                        <a href="tel:0791086533" class="fa fa-phone-square fa-3x"></a>
                        <a href="https://twitter.com/BearPheletso980?t=BbkBzVDX6sSyl5sPI1tM1Q&s=09" class="fa fa-twitter fa-3x"></a>
                        <a href="https://www.linkedin.com/in/evans-mashalane-139638211?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BxuoDE5AGTaSgkO04JXg0%2BQ%3D%3D" class="fa fa-linkedin fa-3x"></a>
                        <a href="https://calvinseabala.github.io/" class="fa fa-globe fa-3x"></a>
                        <a href="mailto:mashalaneevanspheletso@gmail.com" class="fa fa-envelope fa-3x "></a>


                    </div>
                </section>


            </div>


        </div>
    </div>







    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js" integrity="sha512-BdHyGtczsUoFcEma+MfXc71KJLv/cd+sUsUaYYf2mXpfG/PtBjNXsPo78+rxWjscxUYN2Qr2+DbeGGiJx81ifg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.js" integrity="sha512-HkPTAAm+s4i8XlHc0dmKTmR7gEo5W3mwtgRNqOMkYdWAK/OaS89ZwQ2jIOyVx7ZrtCEDxb245+rMjN/mmOj/DQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script>
        var type = new Typed('.typing-text', {
            strings: ['Front-end Developer', 'Data Scientist', 'Web Designer', 'Back-end Developer', 'Networker'],
            typeSpeed: 100,
            loop: true
        })
    </script>
</body>


</html>
