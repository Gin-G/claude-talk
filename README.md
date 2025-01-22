# claude-talk
A repository to work out of when giving a presentation on Claude at the NSF NCAR CISL GenAI session

## prompt.txt

There is a file in this repository named prompts.txt that contains the prompts given to Claude during the session.

My plan is, time permitting, to run through a code generation examples using the Web UI and then use the same exact prompts in GitHub Copilot running on VSCode. 

### Flask

The first prompt asks Claude to create a website based on Python and Flask. If all goes well we expect to get a working code base and instructions on how to launch it.

### Containerization

The second prompt asks Claude to create a container image file for the Flask app that we can use to build a container image. The expectation is that Claude will still be aware of the initial response and will be able to retain that information and provide a Dockerfile without having to give it more information. 

## lengthlimit.txt

Copy and paste the lengthlimit.txt contents in to the claude.ai prompt to see an example of what hitting a length limit looks like.  