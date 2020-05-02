+++
# A video section created with the Blank widget.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 14  # Order that this section will appear.

+++

<body>
        <section class="header">
            <video autoplay loop class="video-background" muted plays-inline>
                <source src="static/img/clouds.mp4" type="video/mp4">
            </video>
            <div class="welcome-msg">
                <h1>WELCOME HOME!</h1>
            </div>
        </section>
        <section>
            <div>
                <p>Lorem ipsum..</p>
            </div>
        </section>
</body>

<style>
  *
{
    margin:0;
    padding:0;
}
.header
{
    background:rgba(0,0,100,0.4);
    height:100vh;
}
.video-background
{
    position:absolute;
    right:0;
    bottom:0;
    min-width:100%;
    max-height:auto;
    width:100%;
    height:100%;
    z-index:-1;
}
@media (min-aspect-ratio:16/9)
{
    .video-background
    {
        width: 100%;
        height:auto;
    }
}
@media (max-aspect-ratio:16/9)
{
    .video-background
    {
        width: 100%;
        height:auto;
    }
}
.welcome-msg
{
    position:relative;
    text-align: center;
    font-family: monospace;
    color: #fff;
    top: 150px;
}
.welcome-msg h1
{
    font-size: 80px;
    font-weight: 100;
    letter-spacing: 5px;
    margin-bottom: 30px;
}
</style>
