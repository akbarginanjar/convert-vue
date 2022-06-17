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

  <section class="service_section">
    <div class="container">
      <div class="custom_heading-container">
        <h2>
          Our Services
        </h2>
      </div>
      <div class="service_container layout_padding2">
        <div class="service_box">
          <div class="img-box">
            <img src="./images/s-1.jpg" alt=""/>
          </div>
          <div class="detail-box">
            <h4>
              Business <br/>
              Consultant
            </h4>
            <p>
              have suffered alteration in some form, by injected humour, or randomised words which don&#39;t look even
              slightly believable. If you are
            </p>
          </div>
        </div>
        <div class="service_box">
          <div class="img-box">
            <img src="./images/s-2.jpg" alt=""/>
          </div>
          <div class="detail-box">
            <h4>
              Marketing <br/>
              Analytics
            </h4>
            <p>
              have suffered alteration in some form, by injected humour, or randomised words which don&#39;t look even
              slightly believable. If you are
            </p>
          </div>
        </div>
        <div class="service_box">
          <div class="img-box">
            <img src="./images/s-3.jpg" alt=""/>
          </div>
          <div class="detail-box">
            <h4>
              Financial <br/>
              Planning
            </h4>
            <p>
              have suffered alteration in some form, by injected humour, or randomised words which don&#39;t look even
              slightly believable. If you are
            </p>
          </div>
        </div>
      </div>
      <div>
        <a href="">
          Read More
        </a>
      </div>
    </div>
  </section>

    </nav>
</template>