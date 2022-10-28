/* skills */
.progress-wrapper {
  height: 130px;
  overflow: hidden;
}

.wave {
  position: absolute;
  width: 100%;
  height: 100%;
}
.wave::before, .wave::after {
  content: "";
  position: absolute;
  width: 800px;
  height: 800px;
  bottom: 0;
  left: 50%;
  background-color: rgba(255, 255, 255, 0.4);
  border-radius: 45%;
  transform: translateX(-50%) rotate(0);
  -webkit-animation: rotate 6s linear infinite;
          animation: rotate 6s linear infinite;
  z-index: 10;
}
.wave::after {
  border-radius: 47%;
  background-color: rgba(255, 255, 255, 0.9);
  transform: translateX(-50%) rotate(0);
  -webkit-animation: rotate 10s linear -5s infinite;
          animation: rotate 10s linear -5s infinite;
  z-index: 20;
}

@-webkit-keyframes rotate {
  50% {
    transform: translateX(-50%) rotate(180deg);
  }
  100% {
    transform: translateX(-50%) rotate(360deg);
  }
}

@keyframes rotate {
  50% {
    transform: translateX(-50%) rotate(180deg);
  }
  100% {
    transform: translateX(-50%) rotate(360deg);
  }
}
/* /skills */


<!-- skills -->
<section class="section">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-title">Skills</h2>
      </div>
      <div class="col-lg-3 col-sm-6 mb-4 mb-lg-0">
        <div class="card shadow text-center">
          <div class="position-relative rounded-top progress-wrapper" data-color="#fdb157">
            <div class="wave" data-progress="90%"></div>
          </div>
          <div class="card-footer bg-white">
            <h4 class="card-title">Web Design (90%)</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-sm-6 mb-4 mb-lg-0">
        <div class="card shadow text-center">
          <div class="position-relative rounded-top progress-wrapper" data-color="#9473e6">
            <div class="wave" data-progress="60%"></div>
          </div>
          <div class="card-footer bg-white">
            <h4 class="card-title">Logo Design (60%)</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-sm-6 mb-4 mb-lg-0">
        <div class="card shadow text-center">
          <div class="position-relative rounded-top progress-wrapper" data-color="#bdecf6">
            <div class="wave" data-progress="80%"></div>
          </div>
          <div class="card-footer bg-white">
            <h4 class="card-title">After Effects (80%)</h4>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-sm-6 mb-4 mb-lg-0">
        <div class="card shadow text-center">
          <div class="position-relative rounded-top progress-wrapper" data-color="#ffbcaa">
            <div class="wave" data-progress="70%"></div>
          </div>
          <div class="card-footer bg-white">
            <h4 class="card-title">Web App (70%)</h4>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- /skills -->