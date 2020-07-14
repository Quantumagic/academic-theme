---
title: "Gallery"  # Add a page title.
summary: "Explore the gallery"  # Add a page description.
date: "2019-01-01T00:00:00Z"  # Add today's date.
type: "widget_page"  # Page type is a Widget Page
widget: "slider"
---

+++
# gallery feature.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Pic interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 3500

# Pic height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"

# Pics.
# Duplicate an `[[item]]` block to add more pics.
[[item]]
  title = ""
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_img = "gallery/im1.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Know More"
  cta_url = "url of the related post"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

[[item]]
  title = ""
  content = ""
  align = ""

  overlay_img = "gallery/im2.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = ""
  content = ""
  align = ""

  overlay_img = "gallery/im3.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
[[item]]
  title = ""
  content = ""
  align = ""

  overlay_img = "gallery/im4.jpg"  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++


This is the gallery use gallery template.
