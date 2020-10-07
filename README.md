# Daily_report
logs of everyday tech knowledge I learn or found interested to save for others too

## Maven archetype:generate

archetype: An ideal example of something.

`mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=Myproject -DarchetypeArtifactId=maven-archetype-quickstart -D-DarchetypeVersion=1.4 -DinteractiveMode=false`
for parameters understanding : [Click Here](https://maven.apache.org/archetype/maven-archetype-plugin/generate-mojo.html)

> -DinteractiveMode=false means  blank java project with all default options. (non-interactive)
> -DinteractiveMode=true means rest of the options will be specified by the user.( interactive )

## Day-2

PuTTYgen is a key generator tool for creating pairs of public and private SSH keys.


PuTTY will open a "network" between both machines. You'll get a console (like the shell) when you'll be connected. Really useful to administrate remote server from your computer.

Usually, the port is not 80, but 22.
