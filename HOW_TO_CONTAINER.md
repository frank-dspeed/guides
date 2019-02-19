# How to Container
In general this is a hard question but if your already a Linux User Like me. I am my Self Ubuntu User i have my own 
Distribution called ```direktspeed ubuntu``` its there as Desktop, Server, Embeded Flavor i would never run windows 
again by the way. The only Situation when i run windows is when i code for Oldschool People that are using it. Or
when i buy hardware that chips only with Linux Drivers. Thanks to KVM i am able to run Windows in such Situation on Demand
so i am Not Forced to work with it and i always buy old used licences for it.

Thats Sayed

## Ubuntu Container Options
Docker and Ubuntu had a baybe called snapd its a cool wrapper around linux jails like Docker is they both together are well
you can even install Docker and Compose via Snapy and update them in a rolling way. If you want to container a Desktop Application 
you should use Snappy if you have something other use docker both together should use only the home directory this way you can backup
more easy that is really nice.


## Build your first Docker Container
you should be Already Familar with Operating system in general that means run, edit, list files, find files, The Basics.

Dockerfile === Description of a Container the exact build Instructions 
docker-compose.yml === Description of a Stack of Dockerfile based Containers can include even build instructions
