+++
# A video section created with the Blank widget.

widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 14  # Order that this section will appear.

+++
<style>
.wrapper {
    position:absolute;
    right:0;
    bottom:0;
    padding:25px;
    min-width:100%;
    max-height:auto
    width:100%;
    height:100%;
    z-index:-1;
}
.wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: auto;
}
@media (min-aspect-ratio:16/9)
{
    .wrapper iframe
    {
        width: 100%;
        height:auto;
    }
}
</style>
<div class="wrapper">
  <iframe src="https://www.youtube.com/embed/7w6MjJ7Cz8U?muted=1&autoplay=1&mute=1" allowfullscreen="true" frameborder="0"></iframe>
</div>

