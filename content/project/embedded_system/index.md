+++
# Project title.
title = "A Six-Legged Smart Bionic Spider - Project for Embedded Systems course"

# Date this page was created.
date = 2016-12-01T00:00:00

# Project summary to display on homepage.
summary = """
- Designed a mobile-controlled spider-like robot that automatically finds paths and avoids obstacles
"""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
# tags = ["Distributed Systems"]

# Optional external URL for project (replaces project detail page).
external_link = ""
share = false

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
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
{{< figure src="robot.jpg" title="" >}}

Designed a mobile-controlled spider-like robot that automatically finds paths and avoids obstacles

- Worked with a group of four to design and develop a spider-like robot

- Connected ultrasonic and light sensors to Arduino Yun to find paths and avoid obstacles

- Used Arduino Yun as a Linux server, making users control the spider via Android phones

- Connected a webcam to Arduino Yun and streamed live video to Android phones using mjpg-streamer