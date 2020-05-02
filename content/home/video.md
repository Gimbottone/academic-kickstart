+++
# A video section created with the Blank widget.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 14  # Order that this section will appear.

+++



<div class="section">
  <h1>Welcome To Paradise</h1>
    <div class="video-container">
      <div class="color-overlay"></div>
        <video autoplay loop muted>
          <source src="static/img/clouds.mp4" type="video/mp4">
        </video>
      </div>
    </div>
  
<style>
.section {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.section h1 {
  text-align: center;
  font-size: 6rem;
  font-family: "Cookie";
  padding: 20px;
  margin: 15px;
  z-index: 1;
  opacity: 0.7;
}

.video-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
}

.color-overlay {
  position: absolute;
  top: 0;
  left: 0;
  background-color: lightblue;
  width: 100%;
  height: 100vh;
  opacity: 0.5;
}
</style>
