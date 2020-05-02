+++
# A video section created with the Blank widget.

widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 14  # Order that this section will appear.

+++
<style>
.wrapper {
    width: 100vw;
    height: 300px;
}
.wrapper iframe {
    position:absolute;
    right:0;
    bottom:0;
    min-width:100%;
    max-height:auto;
    width:100%;
    height:110%;
    z-index:-1;
    margin-bottom:-30px;
}
 .welcome-msg
{
    position:relative;
    text-align: center;
    font-family: monospace;
    color: white;
    top: 100px;
    margin-left:-50px;
}
.welcome-msg h1
{
    font-size: 80px;
    font-weight: 100;
    letter-spacing: 5px;
    margin-bottom: 30px;
}
</style>
<section class="wrapper">
  <iframe src="https://www.youtube.com/embed/7w6MjJ7Cz8U?muted=1&autoplay=1&mute=1&controls=0" allowfullscreen="true" frameborder="0"></iframe>
  <div class="welcome-msg">
    <h1>WELCOME HOME!</h1>
  </div>
</section>


