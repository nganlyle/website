+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Canadian COVID-19 Dashboards"
subtitle = "Data from the COVID-19 Canada Open Data Working Group. Epidemiological Data from the COVID-19 Outbreak in Canada. https://github.com/ishaberry/Covid19Canada."

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "DarkGrey"

  # Background gradient.
  # gradient_start = "Grey"
  # gradient_end = "DarkGrey"

  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++


Select one or more (right click) provinces on the map.

<center><iframe scrolling="no" src="https://public.tableau.com/views/CanadaProvincialCOVID19/CanadaDashboard?:display_count=y&:origin=viz_share_link&:showVizHome=no" width="1000" height="827" frameborder="0"></iframe></center>


Mortality is higher in men and those over the 70 years old.

<center><iframe scrolling="no" src="https://public.tableau.com/views/CanadaCOVID19DemographicData/COVID19CanadaDemographics?:display_count=y&:origin=viz_share_link&:showVizHome=no" width="1000" height="827" frameborder="0"></iframe></center>

Deaths in Canada are growing exponentially.

<center><iframe scrolling="no" src="https://public.tableau.com/views/CanadaCOVID19/CanadaCOVID19?:retry=yes&:display_count=y&:origin=viz_share_link&:showVizHome=no" width="1000" height="827" frameborder="0"></iframe></center>
