<template>
  <footer>
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center h-vh-50 pt-5">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="social-media mb-5 text-center">
              <p class="text-fade-black-1">
                Lorem ipsum dolor sit amet.
              </p>
              <div class="d-flex justify-content-center align-items-center mb-5">
                <router-link class="text-decoration-none border-icon p-2 px-3 mx-3" to="#"><i
                    class="wh-16px fab fa-twitter"></i></router-link>
                <router-link class="text-decoration-none border-icon p-2 px-3 mx-3" to="#"><i
                    class="wh-16px fab fa-facebook-f"></i></router-link>
                <router-link class="text-decoration-none border-icon p-2 px-3 mx-3" to="#"><i
                    class="wh-16px fab fa-instagram"></i></router-link>
              </div>
            </div>
            <div
              class="copyright d-block d-lg-flex justify-content-end align-items-center text-center border-fade-black-1 border-top py-5">
              <p class="px-2 m-0 fw-bold">
                Chili - Lorem ipsum dolor sit amet.
              </p>
              <ul class="text-uppercase d-inline mp-0">
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">/ v. 08.234.123.54.32</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">/ Lorem, ipsum.</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">/ Lorem, ipsum dolor.</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">/ Lorem ipsum dolor sit amet
                    consectetur..</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>