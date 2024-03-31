+++
# Projects widget.
widget = "portfolio"
headless = true
active = true
date = 2016-04-20T00:00:00

title = "Projects"
subtitle = ""

# Order that this section will appear in.
weight = 50

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
#view = 1


[content]
  page_type = "project"

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "project"

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
  filter_default = 0

 [[content.filter_button]]
   name = "All"
   tag = "*"


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""

+++
