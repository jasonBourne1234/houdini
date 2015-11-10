# houdini
An open source IBM BPM toolkit built on Bootstrap, jQuery, React and other cool JavaScript Libraries.

#User Accepted, Developer Approved!

As other toolkits that use widely available open source projects continue to make their tools less developer friendly through code minification and obfucation... this project aims in the other direction.  We've already seen the great success that certain vendors have had with using tools like Bootstrap, jQuery and the like inside their toolkits the problem is these toolkits were never designed to be maintained or modified.  As a BPM developer myself I can't count the time a customer has asked for custom functionality that's just not available out of the box, thus Houdini is Bourne (see what id did there little pun for you).  

If you plan to contribute to the project understand the following:
- We are using React. All components should be built with their own react code in them and not in an external file.
- Libraries must be AMD comatible and loaded with the AMD loader.
- All javascript must follow Google JavaScript style formatting https://google.github.io/styleguide/javascriptguide.xml
- All major functions need to have event triggers at the biggining and end of the funciton to support developer customization.  
- Documentation is paramount please fill out descriptions for all Coach Views, build icons & labels using the established conventions.
- Must use IBM BPM idioms (for example supporting the visibilty controls) when siutation applies.
- When a control needs validation it needs to use an AJAX validation service.
- All Coach View options should be checked for a null value on load. 
