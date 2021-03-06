litpro.lrplugin
===============

Literate Programming plugin for live reload

To use: 

1. Obtain [LiveReload](http://livereload.com/)
2. Clone this repository into [appropriate directory](https://github.com/livereload/livereload-plugins#installing-a-plugin).  I use `~/Library/LiveReload/Plugins`.  
3. cd into the cloned repo.
3. npm install
4. (Re)start LiveReload
5. Drag the appropriate folder to LiveReload. 
6. Start up a server; I currently use [http-server](https://github.com/nodeapps/http-server)
7. Enjoy literate programming with instant compiling :)

The end of the filename should be lp.md, not just .md. While literate-programming can work on just .md files, the plugin is designed to just work on lp.md to avoid compiling .md files that should not be compiled. 