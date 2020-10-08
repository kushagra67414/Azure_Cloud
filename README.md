# Daily_report
logs of everyday tech knowledge I learn or found interested to save for others too

## Maven archetype:generate

archetype: An ideal example of something.

`mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=Myproject -DarchetypeArtifactId=maven-archetype-quickstart -D-DarchetypeVersion=1.4 -DinteractiveMode=false`
for parameters understanding : [Click Here](https://maven.apache.org/archetype/maven-archetype-plugin/generate-mojo.html)

> -DinteractiveMode=false means  blank java project with all default options. (non-interactive)
> -DinteractiveMode=true means rest of the options will be specified by the user.( interactive )

## Day-2

1. PuTTYgen is a key generator tool for creating pairs of public and private SSH keys.


PuTTY will open a "network" between both machines. You'll get a console (like the shell) when you'll be connected. Really useful to administrate remote server from your computer.

Usually, the port is not 80, but 22.

2. Core Azure Services -Compute 
  a. Virtual machine
  b. Function app
  c. App Service
  d. Azure Kubernetes Services. 
  
 3. Creating a virtual machine on azure.
 hosting a webpage at server not localhost
 4. Networking :
  a. Virtual networks 
  b. load balancers
  c. application gateways : it do path way routing.
  d. DnS Zones
  e. CDN profile (content delivery network )
  
  
  ## Day-3
1. Core Azure Services - Storage
    a. Blob
    b. file storage
    c. tables
    d. Queues
    e. data lake storage
    f. Data Box
    
2. Core Azure Services - databse + Analytics 
  a. Sql databases
  b. CosmosDB
  c. Data Factory
  d. event hubs
  e. Data lake analytics
 
3. Core Azure Services - AI and Machine Learning
  a. Cognitive Services 
  b. Bot services
  c. Machine Learning Studio
