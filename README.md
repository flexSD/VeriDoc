VeriDoc
=======

Verilog -> Markdown Rough Spec 
-------

* Parse out verilog block comments and display them above module code blocks
    * We can pick a commenting syntax that allows our script to "know" its a module comment
    * Or we can use standard comments and try to make VeriDoc guess who the block comments belong to
* For all instantiated module code, have some reference or clickable link to the module code itself
* Maybe it would be possible (if we wanted to make this specific for Github use) to have clickable links to the files themselves in Github.
    * I'll look into it
* Use a graphviz script or something like that to generate a module diagram of module heiriarchy and connections.
