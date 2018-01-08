# About

Notes and implementations of a full stack project from the Udemy course
"Node with React --- Fullstack Web Development version 4"

This project is implemented as a Literate program using _Texiweb Jr_.

## How To Extract and Implement

To implement the project, you must have _Texiweb Jr_ installed, and the
latest _Texinfo_ program, currently version 6.5.

Download the source, `nodeWithReact.twjr`.

To extract the files, including a Makefile, type: `jrtangle nodeWithReact.twjr`

The extract the documentation, type `make info`.

To install the application and run the servers and open the browser to the root
page, `type make`.

The Makefile has a ton of targets that can be called, including `make
install-files` to reinstall the source files, but not the node_modules
if those have already been installed and don't need to be
re-installed.  You can also start and stop the express server by
typing `make start-server` and `make stop-server`.
