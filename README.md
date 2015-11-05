# houdini
An open source IBM BPM toolkit built on Bootstrap, jQuery, React and other cool JavaScript Libraries.

#User Accepted, Developer Approved!

As other toolkits that use widely available open source projects continue to make their tools less developer friendly through code minification and obfucation this project aims in the othe rdirection.  We've already seen the great success that certain vendors have had with using tools like Bootstrap, jQuery and hte like inside their toolkits the problem is these toolkits were never designed to be maintained or modified.  As a BPM developer myself I can't count the time a customer has asked for custom functionality that's just not available out of the box, thus Houdini is Bourne (see what id did there little pun for you).  

If you plan to contribute to the project understand the following:
- We are using React. All components should be build with their own react code in them and not in an external file.
- Libraries must be AMD comatible and loaded iwtht eh AMD loader.
- All javascript must follow Google JavaScript style formatting https://google.github.io/styleguide/javascriptguide.xml
- All major functions need to have event triggers at the biggining and end of the funciton to support developer customization.  
- Documentation is paramount please fill out descriptions for all Coach Views, build icons & labels using the established convention.
- Must use IBM BPM idioms (visibility and  when siutation applies.
- When a control needs validatoin it needs to use an AJAX validation service.  
