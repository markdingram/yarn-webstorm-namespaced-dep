WebStorm 2020.1
Build #WS-201.6668.106, built on April 6, 2020

IntelliSense doesn't appear to work for a namespaced Yarn workspace dependency - 

![Diff](./diff.png) 

'greeting' from library 'lib' is found.
  
'greeting2' from library '@markingram/namespaced_lib' isn't found. Note the difference in colour.


Update
======

'greeting3' from library 'lib3-xyz' is also not found. 

Seems like the workspace folder name has to equal the dependency name?
