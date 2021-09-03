<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="TP STudi création d'un site static avec Bootstrap." />
  <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <!-- Libs CSS -->
  <link rel="stylesheet" href="assets/css/libs.bundle.css" />

  <!-- Theme CSS -->
  <link rel="stylesheet" href="//assets/css/theme.bundle.css" />
  <link href="assets/css/main.css" rel="stylesheet" />

  <title>Blockchain Dev l'Asso</title>
</head>
<body>
  <main>
   <section class="bar">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-12">
            <p class="text-center pt-2">
              Toutes nos meetup peuvent être suivies depuis chez vous
              <a href="" class="lien-message-bar"><span>En savoir plus</span>
              </a>
            </p>
          </div>
        </div>
      </div>
    </section>
    <header class="header-menu">
      <div class="container">
        <!--============ Menu ==========================-->
        <nav class="navbar navbar-expand-lg navbar-light bg-white mx-auto ">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#ftco-nav"
            aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="fa fa-bars"></span> Menu
          </button>
          <div class="collapse navbar-collapse" id="ftco-nav">
            <ul class="navbar-nav ml-auto mr-md-3">
              <li class="nav-item active"><a href="#" class="nav-link">Home</a></li>
              <li class="nav-item"><a href="#" class="nav-link">About</a></li>
              <li class="nav-item"><a href="#" class="nav-link">Work</a></li>
              <li class="nav-item"><a href="#" class="nav-link">Blog</a></li>
              <li class="nav-item"><a href="#" class="nav-link">Contact</a></li>
              <li class="nav-item"><a href="/Pages/login.html" class="nav-link">Connexion</a></li>
            </ul>
          </div>
        </div>
      </nav>
      </div>
    </header>    
<!--==================== Formulaire de Login ============================== -->
    <section class="section-border border-primary">
      <div class="container d-flex flex-column">
        <div class="row align-items-center justify-content-center no-gutters min-vh-100">
          <div class="col-8 col-md-6 col-lg-7 offset-md-1 order-md-2 mt-auto mt-md-0 pt-8 pb-4 py-md-11">

            <!-- Image -->
            <img src="assets/images/illustration-login.png" alt="illustration-login" class="img-fluid">

          </div>
          <div class="col-12 col-md-5 col-lg-4 order-md-1 mb-auto mb-md-0 pb-8 py-md-11">
            
            <!-- Heading -->
            <h1 class="mb-0 font-weight-bold text-center">
              Se connecter
            </h1>

            <!-- Text -->
            <p class="mb-6 text-center text-muted">
              Retouvez l'ensemble de vos Meetup en quelques minutes.
            </p>

            <!-- Form -->
            <form class="mb-6">

              <!-- Email -->
              <div class="form-group">
                <label for="email">
                  Email
                </label>
                <input type="email" class="form-control" id="email" placeholder="name@address.com">
              </div>

              <!-- Password -->
              <div class="form-group mb-5">
                <label for="password">
                  Mot de passe
                </label>
                <input type="password" class="form-control" id="password" placeholder="Enter your password">
              </div>

              <!-- Submit -->
              <button class="btn btn-block btn-primary" type="submit">
                Se connecter
              </button>
            </form> 
          </div>
        </div> <!-- / .row -->
      </div> <!-- / .container -->
    </section>
</footer>
  </main>
  <!--=============== Panneau de gestion des cookies =================-->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/tarteaucitronjs/1.9.3/tarteaucitron.js"
    integrity="sha512-cL0fC89w+H+0KjI9fD6dnM4IHyiapz9tpd9x6SarmL/O4xEGPKBepxZdm0rZXliYplhVQ30DHczX6+mttFm71Q=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  <script>
    tarteaucitron.init({
      "privacyUrl": "",
      /* Privacy policy url */

      "hashtag": "#tarteaucitron",
      /* Open the panel with this hashtag */
      "cookieName": "tarteaucitron",
      /* Cookie name */

      "orientation": "middle",
      /* Banner position (top - bottom - middle - popup) */

      "groupServices": false,
      /* Group services by category */

      "showAlertSmall": false,
      /* Show the small banner on bottom right */
      "cookieslist": false,
      /* Show the cookie list */

      "showIcon": true,
      /* Show cookie icon to manage cookies */
      // "iconSrc": "", /* Optionnal: URL or base64 encoded image */
      "iconPosition": "BottomRight",
      /* Position of the icon between BottomRight, BottomLeft, TopRight and TopLeft */

      "adblocker": false,
      /* Show a Warning if an adblocker is detected */

      "DenyAllCta": true,
      /* Show the deny all button */
      "AcceptAllCta": true,
      /* Show the accept all button when highPrivacy on */
      "highPrivacy": true,
      /* HIGHLY RECOMMANDED Disable auto consent */

      "handleBrowserDNTRequest": false,
      /* If Do Not Track == 1, disallow all */

      "removeCredit": false,
      /* Remove credit link */
      "moreInfoLink": true,
      /* Show more info link */
      "useExternalCss": false,
      /* If false, the tarteaucitron.css file will be loaded */

      //"cookieDomain": ".my-multisite-domaine.fr", /* Shared cookie for subdomain website */

      "readmoreLink": "",
      /* Change the default readmore link pointing to tarteaucitron.io */

      "mandatory": true /* Show a message about mandatory cookies */
    });
  </script>
  <script src="assets/js/vendor.bundle.js"></script>
  
  <script src="assets/js/main.js"></script>
  <script src="https://code.iconify.design/2/2.0.3/iconify.min.js"></script>
  <script src="assets/js/jquery-mini.js"></script>
  <script src="assets/js/boot-mini.js"></script>
</body>

</html>