# Installation instructions for MetaPhlAn3 in a Galaxy environment.
These instructions require the Mercurial versioning system, galaxy, and an internet connection.

# For general information about MetaPhlAn3 please refer to:
```
https://github.com/biobakery/metaphlan
```
# Installation procedure: MetaPhlAn3  under Galaxy

Go to the ```//usr/local/galaxy-dist/tools```  directory
Clone MetaPhlAn3 by entering the following command    

```git clone https://github.com/biobakery/MetaPhlAn.git```
 
Clone this repository somewhere: It will create a directory named "galaxy_MetaPhlAn3"

Create a directory named "MetaPhlAn3"  under /galaxy-dist/tools/MetaPhlAn3

Copy member MetaPhlAn3.xml from galaxy_MetaPhlAn3 on to /galaxy-dist/tools/MetaPhlAn3
 

Update member tool_conf.xml  in the galaxy directory adding the following: 
```
   <section name="MetaPhlAn3" id="MetaPhlAn3">
     <tool file="MetaPhlAn3/MetaPhlAn3.xml"/>
  </section>

```
 
Recycle galaxy

# Note:
Once the repository will e upladed to the tool shed, the instructions will be updated accordingly
