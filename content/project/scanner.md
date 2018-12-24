+++
# Project title.
title = "Scanner: Efficient Video Analysis at Scale"

# Date this page was created.
date = 2018-10-02T00:00:00

# Project summary to display on homepage.
summary = """
- Rewrote scheduler for _Scanner_, changing the task granularity from an entire DAG to each node therein
- Added support for streaming video, which enables direct access to memory data in addition to disk
- Developed an object detection app as an example of using _Scanner_ with Tensorflow
"""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
# tags = ["Distributed Systems"]

# Optional external URL for project (replaces project detail page).
external_link = "https://github.com/scanner-research/scanner"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{icon_pack = "fab", icon="github", name="Scanner on GitHub", url = "https://github.com/scanner-research/scanner"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++