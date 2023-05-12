# sakura-pelican
Minimal and simple but functional Pelican SSG theme based on Sakura CSS framework.
* Support for standard features like categories and pagination.
* Responsive
* Basic support for writing mathematics (see below).
![Index page](screenshots/index.png)

# Writing mathematics

Pelican does not provide native support for writing mathematics.
However, the reStructuredText format parser built into Python used by Pelican has native support to [write mathematics](https://docutils.sourceforge.io/docs/ref/rst/mathematics.html).
Mathematical content is displayed using just CSS rules provided by `math2html.css`. 
It works well for many purposes but may not be sufficient for advanced use cases. 
Use [Pelican render math](https://github.com/pelican-plugins/render-math) plugin for more advanced use cases.
This plugin utilizes mathjax. 
Note that math in markdown format is not supported. 
Please see the documentation of reStructuredText for more details.
![Math display](screenshots/math.png)

