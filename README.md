scalajs-react-template
======================

Basic skeleton app for scalajs-react and scalacss


Changes
* Updated Dependencies (react/scalacss/scalajsplugin etc)
* Added [work bench server](https://github.com/lihaoyi/workbench)
* Disabled rhino / depends on Node

Running
=======
startup sbt and workbench will default to serving on port 12345 ..navigate to 
 localhosthost:12345/index.html and you should see what renders when you go [here](http://chandu0101.github.io/scalajs-react-template/)
 
Reloading
=========
I have run into trouble with this and the router. Need to update this once I figure out a solution.
With everything committed running ```sbt "~fastOptJS"``` from the command line should kick it off and you will see
sbt output in console of dev tools in the browser. 