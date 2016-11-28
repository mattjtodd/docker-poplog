# docker-poplog

## Background

What is Poplog? 
Poplog is a multi-language software development environment that has proved itself useful for teaching absolute beginners programming and AI, and supporting major commercial software projects, including Clementine a leading user-extendable data-mining toolkit in the 1990s, later incorporated into IBM's business development software. "Poplog" was a trade-mark of the University of Sussex from about 1983 to 2015.

The core language of Poplog is Pop-11, derived from the Edinburgh University POP-2 Programming language developed for AI research in the 1970s.

The other languages are all implemented in Pop-11.

[http://www.cs.bham.ac.uk/research/projects/poplog/freepoplog.html]

## Build

`docker build -t mattjtodd/poplog .`

## Run

### CLI

`docker run --name poplog  --rm -it mattjtodd/poplog`

### Provided file

`docker run -v $PWD:/files --name poplog  --rm -it mattjtodd/poplog /files/test.p`

Type `bye` in the command prompt to exit.
