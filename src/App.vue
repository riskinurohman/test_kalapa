<template>
  <div class="wrapper">
    <Sidebar/>
    <div class="container-fluid p-4">
      <Navbar/>
      <Breadcrumb/>
      
      <!-- Main content start -->
      <div class="row">
        <div class="col-lg-9">
          <div class="row">
            <div class="col-lg-6 mt-3">
              <div class="card border-0 rounded-3 shadow">
                <img :src="chair" class="card-img-top custom-card-image">
                <div class="card-body">
                  <h5 class="card-title text-muted mb-3">The Best Features Coming to iOS and Web Design</h5>
                  <div class="d-inline">
                    <img :src="person2" class="rounded-circle avatar-article"/>
                    <span class="text-muted ms-2">by</span>
                    <span class="text-muted ms-2 f-w-500 border-end border-2 pe-3">Ghani Pradita</span>
                    <span class="text-muted ms-3">Jan 10, 2020</span>
                  </div>
                  <div class="mt-2 mb-2">
                    <span class="badge rounded-pill bg-info-custom text-info f-w-700">Quote</span>
                    <span class="badge rounded-pill bg-purple-custom text-purple f-w-700 ms-2">Fashion</span>
                  </div>
                  <p class="card-text text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere congue metus, at viverra dui rutrum quis. Integer quis turpis ac ex blandit lacinia.</p>
                  <hr>
                  <div class="d-flex">
                    <div class="text-muted f-w-500">
                      <i class="fas fa-comment-alt"></i> 76 Comments
                    </div>
                    <div class="ms-auto f-w-500">
                      <a href="javascript:void(0)" class="read-more-link">Read More</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mt-3">
              <div class="card border-0 rounded-3 shadow">
                <img :src="lollipop" class="card-img-top custom-card-image">
                <div class="card-body">
                  <h5 class="card-title text-muted mb-3">Latest Quirky Opening Sentence or Paraghraph</h5>
                  <div class="d-inline">
                    <img :src="person2" class="rounded-circle avatar-article"/>
                    <span class="text-muted ms-2">by</span>
                    <span class="text-muted ms-2 f-w-500 border-end border-2 pe-3">Ghani Pradita</span>
                    <span class="text-muted ms-3">Jan 10, 2020</span>
                  </div>
                  <div class="mt-2 mb-2">
                    <span class="badge rounded-pill bg-danger-custom text-danger f-w-700">Gaming</span>
                    <span class="badge rounded-pill bg-warning-custom text-warning f-w-700 ms-2">Video</span>
                  </div>
                  <p class="card-text text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere congue metus, at viverra dui rutrum quis. Integer quis turpis ac ex blandit lacinia.</p>
                  <hr>
                  <div class="d-flex">
                    <div class="text-muted f-w-500">
                      <i class="fas fa-comment-alt"></i> 76 Comments
                    </div>
                    <div class="ms-auto f-w-500">
                      <a href="javascript:void(0)" class="read-more-link">Read More</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mt-3">
              <div class="card border-0 rounded-3 shadow">
                <img :src="clock" class="card-img-top custom-card-image">
                <div class="card-body">
                  <h5 class="card-title text-muted mb-3">Share an Amazing and Shocking Fact or Statistic</h5>
                  <div class="d-inline">
                    <img :src="person2" class="rounded-circle avatar-article"/>
                    <span class="text-muted ms-2">by</span>
                    <span class="text-muted ms-2 f-w-500 border-end border-2 pe-3">Ghani Pradita</span>
                    <span class="text-muted ms-3">Jan 10, 2020</span>
                  </div>
                  <div class="mt-2 mb-2">
                    <span class="badge rounded-pill bg-danger-custom text-danger f-w-700">Gaming</span>
                    <span class="badge rounded-pill bg-success-custom text-success f-w-700 ms-2">Food</span>
                  </div>
                  <p class="card-text text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere congue metus, at viverra dui rutrum quis. Integer quis turpis ac ex blandit lacinia.</p>
                  <hr>
                  <div class="d-flex">
                    <div class="text-muted f-w-500">
                      <i class="fas fa-comment-alt"></i> 76 Comments
                    </div>
                    <div class="ms-auto f-w-500">
                      <a href="javascript:void(0)" class="read-more-link">Read More</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mt-3">
              <div class="card border-0 rounded-3 shadow">
                <img :src="ice" class="card-img-top custom-card-image">
                <div class="card-body">
                  <h5 class="card-title text-muted mb-3">Withhold a Compelling Piece of Information</h5>
                  <div class="d-inline">
                    <img :src="person2" class="rounded-circle avatar-article"/>
                    <span class="text-muted ms-2">by</span>
                    <span class="text-muted ms-2 f-w-500 border-end border-2 pe-3">Ghani Pradita</span>
                    <span class="text-muted ms-3">Jan 10, 2020</span>
                  </div>
                  <div class="mt-2 mb-2">
                    <span class="badge rounded-pill bg-warning-custom text-warning f-w-700">Video</span>
                  </div>
                  <p class="card-text text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere congue metus, at viverra dui rutrum quis. Integer quis turpis ac ex blandit lacinia.</p>
                  <hr>
                  <div class="d-flex">
                    <div class="text-muted f-w-500">
                      <i class="fas fa-comment-alt"></i> 76 Comments
                    </div>
                    <div class="ms-auto f-w-500">
                      <a href="javascript:void(0)" class="read-more-link">Read More</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mt-3">
          <div class="input-icon-wrapper">
            <input class="form-control" placeholder="Search here" type="text">
            <i class="fa fa-search input-icon text-muted"></i>
          </div>

          <!-- Recent Post -->
          <div class="mt-5">
            <span class="text-muted">RECENT POST</span>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-4 col-5">
                <img :src="skate" class="recent-post-img rounded-1">
              </div>
              <div class="col-md-9 col-lg-8 col-7">
                <h5 class="text-muted">Why Should Forget Facebook?</h5>
                <span class="text-muted mt-2 d-block">Jan 14, 2020</span>
              </div>
            </div>
            <div class="row mt-5">
              <div class="col-md-3 col-lg-4 col-5">
                <img :src="mountain" class="recent-post-img rounded-1">
              </div>
              <div class="col-md-9 col-lg-8 col-7">
                <h5 class="text-muted">Publish your passions, your way</h5>
                <span class="text-muted mt-2 d-block">Jan 14, 2020</span>
              </div>
            </div>
            <div class="row mt-5">
              <div class="col-md-3 col-lg-4 col-5">
                <img :src="surfing" class="recent-post-img rounded-1">
              </div>
              <div class="col-md-9 col-lg-8 col-7">
                <h5 class="text-muted">The Best Ways to Retain More</h5>
                <span class="text-muted mt-2 d-block">Jan 14, 2020</span>
              </div>
            </div>
            <div class="row mt-5">
              <div class="col-md-3 col-lg-4 col-5">
                <img :src="paperboat" class="recent-post-img rounded-1">
              </div>
              <div class="col-md-9 col-lg-8 col-7">
                <h5 class="text-muted">Share a Shocking Fact or Statistic</h5>
                <span class="text-muted mt-2 d-block">Jan 14, 2020</span>
              </div>
            </div>
          </div>
          <!-- End Recent Post -->

          <!-- Categories -->
          <div class="mt-5">
            <span class="text-muted">CATEGORIES</span>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-3 col-3">
                <div class="bg-purple-custom text-purple rounded-1 p-2 text-center">
                  <i class="fas fa-clock" style="font-size: 1em"></i>
                </div>
              </div>
              <div class="col-md-9 col-lg-9 col-9 text-muted f-w-500 p-2">Fashion</div>
            </div>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-3 col-3">
                <div class="bg-success-custom text-success rounded-1 p-2 text-center">
                  <i class="fas fa-shopping-cart" style="font-size: 1em"></i>
                </div>
              </div>
              <div class="col-md-9 col-lg-9 col-9 text-muted f-w-500 p-2">Food</div>
            </div>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-3 col-3">
                <div class="bg-danger-custom text-danger rounded-1 p-2 text-center">
                  <i class="fas fa-th-large" style="font-size: 1em"></i>
                </div>
              </div>
              <div class="col-md-9 col-lg-9 col-9 text-muted f-w-500 p-2">Gaming</div>
            </div>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-3 col-3">
                <div class="bg-info-custom text-info rounded-1 p-2 text-center">
                  <i class="fas fa-hashtag" style="font-size: 1em"></i>
                </div>
              </div>
              <div class="col-md-9 col-lg-9 col-9 text-muted f-w-500 p-2">Quote</div>
            </div>
            <div class="row mt-3">
              <div class="col-md-3 col-lg-3 col-3">
                <div class="bg-warning-custom text-warning rounded-1 p-2 text-center">
                  <i class="fas fa-video" style="font-size: 1em"></i>
                </div>
              </div>
              <div class="col-md-9 col-lg-9 col-9 text-muted f-w-500 p-2">Video</div>
            </div>
          </div>
          <!-- End Categories -->

        </div>
      </div>
      <!-- End Main content -->

    </div>
  </div>
</template>

<script>
import Sidebar from "./components/Sidebar.vue"
import Navbar from "./components/Navbar.vue"
import Breadcrumb from "./components/Breadcrumb.vue"
import Chair from "./assets/images/chair.jpg"
import Person2 from "./assets/images/person2.jpg"
import Lollipop from "./assets/images/lollipop.jpg"
import Clock from "./assets/images/clock.jpg"
import Ice from "./assets/images/ice.jpg"
import Skate from "./assets/images/skate.jpg"
import Mountain from "./assets/images/mountain.jpg"
import Surfing from "./assets/images/surfing.jpg"
import Paperboat from "./assets/images/paperboat.jpg"

export default {
  name: 'App',
  components: {
    Sidebar,
    Navbar,
    Breadcrumb
  },
  data: function() {
    return {
      chair: Chair,
      person2: Person2,
      lollipop: Lollipop,
      clock: Clock,
      ice: Ice,
      skate: Skate,
      mountain: Mountain,
      surfing: Surfing,
      paperboat: Paperboat
    }
  }
}
</script>
<style>
  .input-icon-wrapper {
    display: flex;
  }
  .input-icon {
    position: absolute;
    right: 40px;
    margin-top: 10px;
  }
  .read-more-link {
    text-decoration: none;
    color: #9890F3;
  }
  .wrapper {
    display: flex;
  }
  .breadcrumb-link {
    text-decoration: none;
    color: #A39BF3;
    font-weight: 600;
  }
  .btn-primary, .btn-primary:hover, .btn-primary:active, .btn-primary:visited {
    background-color: #7367EF !important;
    border-color: #7367EF !important;
  }
  .custom-card-image {
    height: 500px;
    object-fit: cover;
  }
  .avatar-article {
    object-fit: cover;
    height: 30px;
    width: 30px;
    max-height: 100%;
  }
  .f-w-500 {
    font-weight: 500;
  }
  .f-w-700 {
    font-weight: 700 !important;
  }
  .bg-info-custom {
    background-color: #E0F9FD !important;
  }
  .bg-purple-custom {
    background-color: #EEEDFD !important;
  }
  .bg-danger-custom {
    background-color: #FCEAEA !important;
  }
  .bg-purple {
    background-color: #7367EF;
  }
  .bg-warning-custom {
    background-color: #FFF3E7 !important;
  }
  .bg-success-custom {
    background-color: #E3F7EC !important;
  }
  .text-purple {
    color: #7367EF !important;
  }
  .recent-post-img {
    height: 80px;
    width: 100%;
    max-height: 100px;
    object-fit: cover;
  }
</style>
