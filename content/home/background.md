+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 23  # Order that this section will appear.

title = "Background"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
   #[[content.filter_button]]
    # name = "Background"
    # tag = "*"
  
   #[[content.filter_button]]
    # name = "Coal plants"
    # tag = "coal"
  
   #[[content.filter_button]]
    # name = "Southeast Accountability"
    # tag = "APA"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

I am driven to solve complex environmental problems through collaboration with experts in multiple fields and environmental stakeholders, while emphasizing the role of data and modern tools for data science. In particular, I am interested in Air Pollution Accountability, a field that tries to answer the question ‘Was it all worth it?’ in regard to air quality regulations. 

I prioritize communication with stakeholders affected by the links in the Accountability Chain (if you’re one of them, please reach out!), and I hope that my efforts will contribute to continued implementation of scientifically sound policies throughout the world.

In pursuing this research, I investigate relationships between links along the Chain of Accountability (figure below). This framework describes how regulations impact emissions, air quality, personal dose/exposure, and ultimately public health. Though we can measure changes at each of these links, the relationships that accountability researchers are interested in (blue portions of the arrows) are clouded by other factors (red portions), making it difficult to causally attribute changes at any link to air quality regulations.

![HyADS in each year](/img/AccountabilityChain.png)
