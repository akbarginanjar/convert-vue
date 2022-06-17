<template>

<nav class="sub_page">
  <div class="hero_area">
    <!-- header section strats -->
    <header class="header_section">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-8">
            <nav class="navbar navbar-expand-lg custom_nav-container ">
              <a class="navbar-brand" href="/">
                <span>
                  BigWing
                </span>
              </a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>

              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <div class="d-flex  flex-column flex-lg-row align-items-center">
                  <ul class="navbar-nav  ">
                    <li class="nav-item active">
                      <router-link class="nav-link" to="/">Home</router-link>
                    </li>
                    <li class="nav-item">
                      <router-link class="nav-link" to="/about">About</router-link>
                    </li>
                    <li class="nav-item">
                      <router-link class="nav-link" to="/service">Services </router-link>
                    </li>
                    <li class="nav-item">
                      <router-link class="nav-link" to="/contact">Contact</router-link>
                    </li>
                    <li class="nav-item">
                      <router-link class="nav-link" to="#"> Login</router-link>
                    </li>
                  </ul>
                  <form class="form-inline my-2 my-lg-0 ml-0 ml-lg-4 mb-3 mb-lg-0">
                    <button class="btn  my-2 my-sm-0 nav_search-btn" type="submit"></button>
                  </form>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <!-- end header section -->
  </div>

  <!-- welcome section -->
  <section class="welcome_section layout_padding">
    <div class="container">
      <div class="custom_heading-container">
        <h2>
          Welcome To Our Company
        </h2>
      </div>
      <div class="layout_padding2">
        <div class="img-box">
          <img src="./images/welcome.png" alt=""/>
        </div>
        <div class="detail-box">
          <p>
            dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
            aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            Duis
            aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
          </p>
          <div>
            <a href="">
              Read More
            </a>
          </div>
        </div>
      </div>

    </div>
  </section>
  <!-- end welcome section -->
  </nav>
</template>
