![Securbot](assets/securbot_logo_text.svg)

## What is SecurBot ?
SecurBot is a project develop by a team of 8 students in electrical engineering from the Universite de Sherbrooke. The goal of this project is to use the different technologies develop by the [IntRoLab](https://introlab.3it.usherbrooke.ca/mediawiki-introlab/index.php/Main_Page) research team to create an autonomous security robot. The following video shows the current state of the project :

[![PROMO](https://img.youtube.com/vi/bDdfO7ZALls/0.jpg)](https://www.youtube.com/watch?v=bDdfO7ZALls)

## Project status

Securbot is currently under developement.

Follow the efforts of our team and the current issues through our team's [Jira](https://securbot.gel.usherbrooke.ca/jira/projects/SEC/issues/).

And our [Dashboard](https://securbot.gel.usherbrooke.ca/dashboard/dashboard.pdf)

## The wiki
To find tutorials and more information about the project, [Check our Wiki!](https://github.com/introlab/securbot/wiki)

## Code documentation
To read the code documentation of the latest release: [Read the doc!](https://introlab.github.io/securbot/)

## SecurBot Repository

The Securbot project can be split into 5 parts, the ROS packages used on the robots, the frontend web application done with Vue.js, the easyrtc backend server, the custom hardware (pcb) and the mechanical structure with a few more directories for assets, code documentation, script utilities, etc.

### Assets
This directory includes different versions of our logo and other ressources used by the docs or the wiki.

### Backend
The docker files and the server scripts (node.js) of the different versions of our easyrtc server are stored here.

### Dashboard
All utilities scripts attached to our Jira dashboard. Most of them were created to simplify an academic tasks for us.

### Docs
The docs directory contains the code documentation of the project that is served by our github documentation site. The frontend and the electron package documentation are generated with JSDoc and the securbot_pkg documentation is generated using Doxygen.

To generate the JSDoc documentation, navigate into either the frontend directory or the electron one with a terminal and enter the following command :
```
$ npm run docs
```

For the doxygen documentation, navigate into /docs/ros/doxygen using a terminal and enter the following command:
```
$ doxygen config_doxygen
```

This will generate the code documentation in the correct /docs sub-directory if need be.

### Frontend
Our web application done with Vue.js and all the necessary config files. The README.md inside enumerates all the commands needed to use the app.

### ROS Packages

At this time, we have produced 2 ROS packages, the SecurBot package and an electron application bundle as a ros node. The other packages distributed with them are packages created by other people that we are using. Those other packages are not documented here, so you'll have to look in their respective repositories for that.

Note: even though we didn't create the roboclaw node, we had to modify it to make it work properly. The README.md inside contains the changes that were done.

### Scripts
This mostly contains utility scripts such as installer scripts and virtual cameras (those will change in the future) for debugging.

### Test
All documented tests and their test procedures can be found inside.


