# vagrant-windows
Vagrant windows guest configuration

To build vagrant boxes for windows you can version windows environments. Given the ongoing use of windows in the modern business world, the ability to deploy these systems with codified configurations is highly desireable.

the [Windows Packer Templates](https://github.com/joefitzgerald/packer-windows) repo contains a wealth of resources for building windows vagrant boxes.

Install packer as a git submodule

```
git submodule add --name packer https://github.com/StefanScherer/packer-windows
```

Packer, and its windows templates can be managed in a seprate git repo and updated within the vagrant windows deployment repo.
