---
layout: default
food: pears
---

this is the index.md file

### test
- when using a jekyll theme --> only the index.md file will be rendered into the website
- when not using jekyll --> the index.html file will be loaded into the website by default

### hyperlink test
[test a hyperlink to my new subpage](page1/index.md)

### testing images
__How to center images that have been added in markdown?__
* Github markdown doesn't support alignment of images (see [Centering images in README.md files, Stackoverflow](https://stackoverflow.com/questions/12090472/github-readme-md-center-image))
* so the only way is to do it through direct html img tags. And for centering an image the only option is to put it inside a p tag and center it

<p align="center">
      <b>testing a paragraph in html</b> <br/><br/>
       <img height="200px" src="images/mimi1.jpg">   <br/><br/>
       <img height="200px" src="images/mimi5.jpg">   <br/><br/>
       <img height="200px" src="images/mimi10.jpg">   <br/><br/>
</p>
