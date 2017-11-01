## Before Building

### install libfreenect
run _brew install libfreenect_ on Termial

### copy folder /OpenKinect  to your project

### Edit Project
####  General
add /usr/local/Cellar/libfreenect/0.5.6/lib/libfreenect.a to Linked Frameworks and Liberay

####  Building Setting
* add _${SRCROOT}/OpenKinect_ to _Import Paths_ under _Swift Compiler – Search Paths_
* add _/usr/local/include/libfreenect_ to _Header Search Paths_ under _Search Paths_
* add _/usr/local/lib_ to _Libary Search Paths_ under _Search Paths_

