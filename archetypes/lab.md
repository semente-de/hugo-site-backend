---
date: '{{ .Date }}'
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
#draft: true
#weight: 1
#author: "Who"
#author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
UseHugoToc: true
hidemeta: false
comments: false
disableHLJS: true # to disable highlightjs
disableShare: false
#disableHLJS: false
#hideSummary: false
#searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
#ShowRssButtonInSectionTermList: true
#cover:
#    image: "/img/icon.png" # image path/url
#    alt: "imagem" # alt text
#    caption: "imagem" # display caption under cover
#    relative: false # when using page bundles set this to true
#    hidden: false # only hide on current single page
#editPost:
#    URL: "https://github.com/<path_to_repo>/content"
#    Text: "Suggest Changes" # edit text
#    appendFilePath: true # to append file path to Edit link
---
Body.