baseURL = "https://rodrigo.github.io/"
languageCode = "en-us"
title = "El meu Blog"
publishDir = "docs"
paginate = 2
canonifyurls = true
[params]
description = "Blog del Projecte 5 de M7"
cover = "images/FonsJoan.png"
logo = "images/LogoJoan.png"
githubName = "cf19rodrigolindo"
hideHUGOSupport = false

[[menu.main]]  # here are the buttons on the menu
name = "Home" # Button will display as "Home"
weight = 100 # the weight decides the position of the button (higher or lower)
identifier = "home"
pre = "<br />"
url = "/"

[[menu.main]]
name = "Contact"
weight = 0
identifier = "contact" # this button will refer to a markdown file named "contact" in the content folder
pre = "<br />"
url = "/contact"
[[menu.main]]
name = "Blog"
identifier = "blog" # this page will refer to a markdown file named "blog" in the content folder
pre = "<br />"
url = "/post"
weight = 40

[sitemap]
ChangeFreq = ""
Filename = "sitemap.xml"
Priority = "-1"

