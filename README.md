<!doctype html>
<html lang="ee">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <meta name="description" content=""> 
        <meta name="author" content="">
        <title>Avaleht</title>
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous"> 
        <!-- minu CSS -->
        <link rel="stylesheet" href="custom.css">
    </head>
    <body>
        <!-- päis -->
    <div class="jumbotron">
        <header class="py-2">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-12 my-3 text-center"><img src="logo2.png" width="50%"></div>              
                </div>          
            </div>
        </header>
        <!-- navigatsioon -->
        <nav class="navbar navbar-expand-lg navbar-light bg-white shadow">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Uued tooted</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Vannitooted</a> 
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink"> 
                            <a class="dropdown-item" href="#">Vannisoolad</a> 
                            <a class="dropdown-item" href="#">Vannipiimad</a> 
                            <a class="dropdown-item" href="#">Vannipommid</a>
                            <a class="dropdown-item" href="list.html">Seebid ja du&scaron;igeelid</a>
                        </div> 
                    </li> 
                    <li class="nav-item dropdown"> 
                        <a class="nav-link" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Kehahooldus</a> 
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink"> 
                            <a class="dropdown-item" href="#">Kehakreemid</a> 
                            <a class="dropdown-item" href="#">Keha&otilde;lid</a> 
                            <a class="dropdown-item" href="#">Kehakoorijad</a> 
                            <a class="dropdown-item" href="#">Deodorandid</a> 
                            <a class="dropdown-item" href="#">K&auml;te ja jalgade hooldus</a>  
                        </div> 
                    </li> 
                    <li class="nav-item dropdown"> 
                        <a class="nav-link" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">N&auml;ohooldus</a> 
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink"> 
                            <a class="dropdown-item" href="#">Puhastus ja toniseerimine</a> 
                            <a class="dropdown-item" href="#">Niisutus ja toitmine</a> 
                            <a class="dropdown-item" href="#">Koorijad ja maskid</a> 
                        </div> 
                    </li> 
                    <li class="nav-item"><a class="nav-link" href="meist.html">Meist</a></li>
                </ul>
                <!-- search -->
                <form class="form-inline m-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Otsi" aria-label="Search">
                    <button class="btn btn-outline-white my-2 my-sm-0" type="submit"><svg class="lnr lnr-magnifier"><use xlink:href="#lnr-magnifier"></use></svg></button>
                </form>
            </div>
            <!-- cart -->
            <a href="cart.html"><button class="btn btn-dark my-2 my-sm-0" type="submit"><svg class="lnr lnr-cart"><use xlink:href="#lnr-cart"></use></svg></button></a>
        </nav> 
    </div>
        <section>
            <!-- breadcrumb -->
            <nav aria-label="breadcrumb" >
                <ol class="breadcrumb bg-white my-2">
                    <li class="breadcrumb-item"><a href="index.html">Avaleht</a></li>
                </ol>
            </nav>
        </section>
        <!--JUMBOTRON!!-->
        <!-- TODO! --->
        <!-- tooted --->
        <section>
            <div class="container">
                <h2 class="h mb-3">TOP</h2>
                <div class="row"> 
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 1</a></h5>
                                <p class="text-muted card-text"> 15.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div> 
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 2</a></h5>
                                <p class="text-muted card-text"> 12.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div> 
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 3</a></h5>
                                <p class="text-muted card-text"> 9.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div> 
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 4</a></h5>
                                <p class="text-muted card-text"> 18.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div> 
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 5</a></h5>
                                <p class="text-muted card-text"> 1.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div>
                    <div class="col-md-4 mb-4"> 
                        <div class="card shadow-sm border-0 h-100 text-center"><a href="#"><img src="soap.png" alt="" class="card-img-top"></a> 
                            <div class="card-body"> 
                                <h5> <a href="#" class="text-dark">Toode 6</a></h5>
                                <p class="text-muted card-text"> 5.99&#8364;</p> 
                                <a role="button" href="#" class="btn btn-outline-dark">Vaata</a>
                            </div> 
                        </div> 
                    </div> 
                </div>
            </div>
        </section>   
        <!-- jalus --->
        <footer class="bg-light">
            <div class="container-fluid">
                <div class="row">
                    <!-- TODO! --->
                    <div class="col-lg-12 text-center"><p>T: +372 55555555<br>meiliaadress@gmail.com<br>Aadress 123, Tartu</p>
                        <a href="#"><img width=3% src="https://icons.iconarchive.com/icons/danleech/simple/256/facebook-icon.png"></a>
                        <a href="#"><img width=3% src="https://icons.iconarchive.com/icons/danleech/simple/256/linkedin-icon.png"></a>
                        <a href="#"><img width=3% src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/2048px-Instagram_logo_2016.svg.png"></a>
                    </div>
                </div>
            </div>
        </footer>       
        <!-- jQuery, Popper.js, Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
        <script src="https://cdn.linearicons.com/free/1.0.0/svgembedder.min.js"></script>
  </body>
</html>
