# Docker

Docker is new to me... 

After watching [this 12 min overview](https://www.youtube.com/watch?v=YFl2mCHdv24) , and finishing [a beginner's tutorial](https://training.play-with-docker.com/beginner-linux/), this is what I have:

## Containers, Containers, Containers

Docker is a way of running your application without the worries of enviromental differences. In other words, on Docker, your app will run excatly the same on Windows, Linux, or MacOS. 

This can happen because of how your application is packaged. Your code is packaged with all dependencies (your environment) in the container. It's almost the same as running your application on a virtual machine, or VM, without the overhead. Docker uses special features of the Unix file system to create the isolated environments without taxing your host machine as a VM would. Docker uses less disk space and less memory which also allows for instant startup of your application. I'm sure anyone running Parallels understands this.

Docker also allows you to keep all of your projects separated. Similar to my experience with GitHub, this allows you to not have to worry about conflicts. This also a good security measure.

If you want to extend another project, whether it's yours or someone else's public project, you dont need to go hunting for dependencies or software because the entire project is packaged already, and you can jump right in.
