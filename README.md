# FJC 

Simple and fast CLI tool to install and manage FortressJS instances

# Install 

`npm install -g fjc`

# Init a new FortressJS instance 

`fjc --init {NAME}`

# Add default engines 

`fjc --add engine --default`

# Add a demo server

`fjc --add srv --name adrien-thierry/fortressjs-demo-server`

# Add an empty srv and a host

* `fjc --add srv --name adrien-thierry/fjsweb`
* `fjc --add host --srv fjsweb --name adrien-thierry/fortpress`

# Start an instance 

`fjc --start`
