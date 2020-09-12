+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 4000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "800px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = "Bla"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
   
 # overlay_img = "rik_presenting5.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = ""
  content = "Koe"
  align = "right"

  # overlay_color = "#555"  # An HTML color value.
  # overlay_img = "rik_presenting4.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

[[item]]
  title = ""
  content = {{< youtube XujJZxfeCaM >}}
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  # overlay_img = "rik_training.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.
+++




