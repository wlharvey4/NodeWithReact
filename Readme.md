# About

This is a literate programming project based upon the Udemy course by
Stephen Grider called "Node With React --- Fullstack Web Development
version 4".

The entire full stack project plus all notes and documentation plus a
master Makefile are wrapped up inside the one source file
_nodeWithReact.twjr_.

# Requirements

This is a literate programming project using _Texiweb Jr_ by Arnold
Robbins.  See https://github.com/arnoldrobbins/texiwebjr.  This is
a project written as a literate program itself.

You will need _texiwebjr_ and _texinfo_ ver 6.5 installed in order to
extract the files in this project.  When it is all done, I will
probably have a PDF, HTML, and TEXT documents for review, but to
create the project implementation you will still need to have the
_texiwebjr_ and _texinfo_ files installed.

# How to Install and Interact with the Project

To extract the Makefile, execute _bootstrap_.

To implement the project, run _make_ with no target; this will run the
default target, which is to extract all files, create the directory
structure, install all Node dependencies, start the server, and open
the browser to the root.

The Makefile has a ton of targets that can be run as necessary.  For
example, to start and stop the server, you can type _make
start-server_ and _make stop-server_.  To open the browser, you can
type _make open-browser_.  To clean the top directory, type _make
clean_.  To clean all files except the Node dependencies and the
_package.json_, type _make very-clean_.  To remove all files except 
the source, Makefile, Readme, and bootstrap, type _make dist-clean_.

If you make a change to a file, you can type _make install-files_, and
the project should reboot with the changes installed, since _nodemon_ 
should be running, assuming you started with _make_.
