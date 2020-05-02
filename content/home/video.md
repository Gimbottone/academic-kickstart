+++
# A video section created with the Blank widget.

widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 14  # Order that this section will appear.

+++
{{ if or (eq (index .Params 1) "widescreen") (not (index .Params 1) ) }}
    {{ $.Scratch.Add "ratio" 56.25 }}
{{ else if eq (index .Params 1) "standard" }}
    {{ $.Scratch.Add "ratio" 75 }}
{{ else }}
    {{ $nums := split (index .Params 1) ":" }}
    {{ $.Scratch.Add "ratio" (div (mul (int (index $nums 1)) 100.0) (int (index $nums 0))) }}
{{ end }}
<div style="position: relative; padding-bottom: {{ $.Scratch.Get "ratio" }}%; overflow: hidden;">
    <iframe style="position: absolute; width: 100%; height: 100%;"
        src="http://www.youtube.com/embed/{{ index .Params 0 }}" allowfullscreen frameborder="0">
    </iframe>
</div>

{{< youtube 7w6MjJ7Cz8U "16:9">}}
