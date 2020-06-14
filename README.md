# java-project
This project implemented a Jenkins multi-branch pipeline to support
continuous integration as follows:

I set up a jenkins server and created a jenkins file. so that when
people push the change to github, github will trigger jenkins server to 
build, unittest, deploy build to multiple platforms for integration tests.
if all the above stages run successfully, jenkins server will push code
to github master branch so that people have right code to use later on.
