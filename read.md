<!-- togglebutton -->

/* Navbar Toggler Button */
.navbar-toggler {
  border: none;
  outline: none;
}

.toggler-icon {
  width: 28px;
  height: 2.5px;
  background-color: #ce38ec;
  display: block;
  position: relative;
  transition: all 0.3s ease-in-out;
}

.toggler-icon::before,
.toggler-icon::after {
  content: '';
  position: absolute;
  width: 28px;
  height: 2.5px;
  background-color: #ce38ec;
  transition: all 0.3s ease-in-out;
}

.toggler-icon::before {
  top: -8px;
}

.toggler-icon::after {
  top: 8px;
}

/* When menu is open — turn into “X” */
.navbar-toggler:not(.collapsed) .toggler-icon {
  background-color: transparent;
}

.navbar-toggler:not(.collapsed) .toggler-icon::before {
  transform: rotate(45deg);
  top: 0;
}

.navbar-toggler:not(.collapsed) .toggler-icon::after {
  transform: rotate(-45deg);
  top: 0;
}
 
 <!-- htmltoggle -->
         <button class="navbar-toggler collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="toggler-icon"></span>
            </button>









             .stars i {
  margin: 0 2px;
  font-size: 1.1rem;
}

.scroll {
  display: flex;
  animation: scroll 20s linear infinite;
}
@keyframes scroll {
  from { transform: translateX(100%); }
  to { transform: translateX(-100%); }
} 
/* Scroll animation for stats section */
.scroll-wrapper {
  width: 100%;
  overflow: hidden;
  position: relative;
}

.scroll-content {
  display: inline-flex;
  white-space: nowrap;
  animation: scrollLeft 25s linear infinite;
}

@keyframes scrollLeft {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(-100%);
  }
}

/* Optional: Pause on hover */
.scroll-content:hover {
  animation-play-state: paused;
}

/* Stat box styling */
.stat-box {
  min-width: 200px;
  text-align: center;
}

.stat-box i {
  margin: 2px;
}



    <section class="stats-section py-4 text-white overflow-hidden">
  <div class="scroll-wrapper">
    <div class="scroll-content d-flex justify-content-around align-items-center flex-wrap">
      <div class="stat-box text-center m-3">
        <h2 class="fw-bold" style="color: #ce38ec;">10k+</h2>
        <p>Developers</p>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star-half-stroke" style="color: rgb(202, 205, 50);"></i>
      </div>

      <div class="stat-box text-center m-3">
        <h2 class="fw-bold">50k+</h2>
        <p>Companies</p>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star"></i>
      </div>

      <div class="stat-box text-center m-3">
        <h2 class="fw-bold" style="color: #ce38ec;">200k+</h2>
        <p>Jobs Posted</p>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star-half-stroke" style="color: rgb(202, 205, 50);"></i>
      </div>

      <div class="stat-box text-center m-3">
        <h2 class="fw-bold">95%</h2>
        <p>Success Rate</p>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star" style="color: yellow;"></i>
        <i class="fa-solid fa-star-half-stroke" style="color: rgb(202, 205, 50);"></i>
      </div>
    </div>
  </div>
</section>