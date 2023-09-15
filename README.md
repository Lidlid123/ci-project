# ci-project


This  a simple github actions ci-cd project  that work as follows :

when the developer push to the main branch , it will trigger  a workflow that will  build the python app into a docker image and deploy it via ssh  access to an AWS ec2
instance that is pre installed  with docker and listen on port 80 

also eveytime  a new push will be commited the container will be updated .

