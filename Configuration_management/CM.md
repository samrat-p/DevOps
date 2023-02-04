#  🐍 Introduction to DevOps
**4. Configuration Management**


## Configuration Management
Configuration management is a process for provisioning developers, test and production environment by writing in one centralized location.</br>

 - Configuration Management is the practise of handling changes systematically so that a system maintains its intregraty over time.
 -  Configuration Management  ensure that the current design and bulid state of the system is known,good and trusted.
 - It doesn't rely on the tactics knowledge of the development team.

## Applications uses of configuration management

 - It can help us to figure out which components to change when requirement changes, it also help us in re-doing an implementation because the requirement have changed, since last implementation.
 - It helps us to revert to a previous version of the component if you have replaced with a new but flawed version now.
 
 **Example through a use case** 
blah blah blah will added later</br>
## Configuration Management Tools
 - Puppet
 - Chef
 - Ansible
 - Saltstack
 
In here we are gonna talk about **Puppet** </br>
Puppet is a configuration management tool that is used for deploying configuration and managing servers. </br>
**Function of Puppet**
 - You can define distinct configuration for each and every host and continuously checks and confirm whether the required configuration is in place and is not altered on the host.
 - If it is altered puppet will revert back to its required configuration.
 - It can also helping dynamic scaling up and down in machines.
 - It follows an Master- Slave architecture.
 -   &darr;
    **Pull configuration &rarr; Push configuration**
  <p>Lets talk about Pull configuration</P> </br>
 It obviously follows a master-slave architecture, where is slaves will pull the central server for changes made in the configuration.So we have multiple nodes connected to the master , so they will check continuously is there any changes in the configuration happened in the Master repository. </br>
The moment
 

