virtualenv is a tool to create a separate(isolated) environment for your python/Django projects. It creates a new environment for you, without affecting the dependencies or version installed globally on the host system. 

For example, if you are running Ubuntu 16.04, the OS may use python 3.5 internally and should be left untouched. But you need a recent python version for your Django project. This can be easily achieved by using virtualenv. 

virtualenv keeps your project environment isolated from the system environment and the packages installed inside, are independent and isolated from the one on the host system. 

It keeps the version and dependencies isolated from the globally installed libraries or other virtualenv environments on the host system. So that you can use packages and libraries as required by the project, without causing any version conflict.
