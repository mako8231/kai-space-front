<template>
    <div class="container-fluid">
        <!--Sub Navbar-->
        <div id="title-header" class="row">
            <img class="logo" src="../assets/pictures/logo-brand.png" alt="">
        </div>
        <!--Main Navbar-->
        <div id="nav-header" class="row">
            <nav class="navbar navbar-expand-lg">
                <div class="container-fluid justify-content-end">
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                    </button>
                    <!--Forum options -->
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <div class="navbar-nav container">
                            <li class="nav-item">
                                <a class=" nav-link home-nav" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                                <a  class="nav-link forum-nav" href="#">Forum</a>
                            </li>
                            <li class="nav-item">
                                <a  class="nav-link latest-nav" href="#">Latest Art</a>
                            </li>
                            <li class="nav-item">
                                <a  class="nav-link booru-nav" href="#">Imageboard</a>
                            </li>
                        </div>
                    </div>
                </div>
                <div class="container-fluid justify-content-lg-end justify-content-sm-center justify-content-xm-start">
                     <form class="">
                        <button class="button-login btn btn-outline-secondary me-2" type="button"><i class="login-icon"></i>Log-in</button>
                        <button class="button-login btn btn-outline-secondary me-2" type="button"><i class="register-icon"></i>Register</button>
                        <button class="button-view-profile btn btn btn-outline-secondary me-2" type="button"><i class="profile-icon"></i>View Profile</button>
                        <!--If the authenticated user has mod/admin privileges-->
                        <button class="button-admin-dashboard btn btn btn-outline-secondary me-2" type="button">Admin Dashboard</button>
                        
                    </form>
                </div>
            </nav>
        </div>
    </div>

</template>