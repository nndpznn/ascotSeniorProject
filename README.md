# Getting Started Documentation

## Overview and Components

The Ascot Microforest Connect project is software solutions and infrastructure for tracking and documenting the positive environmental impact of micro-forests on urban areas. Consisting of multiple applications for contributors, stewards and observers, the project also maintains a database of plant logs that are aggregated into big-picture statistics that demonstrate the impact of planting micro-forests for communities and governments.

Note: You can find status updates in STATUS_UPDATES.md, they have moved.

### Data Contribution
For contributors: A mobile app that allows researchers and visitors alike to record plant growth for individual micro-forests.

### Steward Portal
For stewards, or micro-forest administrators: a portal that allows them to view statistics at a glance and manage contributors and data.

### Micro-Forest Connect
For curious observers: an interactive page that shows micro-forest locations and info on a dynamic map, with quick facts demonstrating impact!


## Building and Running
To view the components in their final states, follow the following steps. I have added you to the [LMU Applied Ecology](https://github.com/LMU-Applied-Ecology) organization, so you should have access to all of the following repositories.
Unfortunately, one of the developers has not yet added their repository for the Data Contribution component to this organization, so you will not be able to view it. I am also not able to fork it and make it public so that you can run it.

### Data Contribution
**Putting this here for the future, in case the owner of the PlantTrackingApp repository ever adds it to the LMU Applied Ecology organization.**
- Visit this repository and clone it [here](https://github.com/cchoi17/PlantTrackingApp).
- Run 'npm install' in the project
- Run 'npm start' in the project
- Follow the steps to deploy it on your preferred platform
	- iOS instructions: Download xCode, download the most recent iPhone OS, then after running 'npm start', press 'shift + i' and select the first iPhone in the menu.

### Steward Portal
This component is already deployed so you should not have to clone the repository. If you'd like to view the repository anyway, it's [here](https://github.com/LMU-Applied-Ecology/ascot-admin).
- Visit https://ascot-steward-portal.web.app/
- Create an account (anyone can do it) and log in. Let me know what your email is so that I can whitelist you to testForest so you can experience the micro-forest customization part of the app.
- Inside the "Your Micro-Forests" tab, enter the id "testForest" and join. 
- Poke around, submit a micro-forest request!

### Micro-Forest Connect
This component is already deployed so you should not have to clone the repository. If you'd like to view the repository anyway, it's [here](https://github.com/LMU-Applied-Ecology/ascot-microforestconnect).
- Visit https://microforest-connect.web.app/ 
- No account required, poke around, view the map and micro-forests pages! You can click on forests on the map to see more information about each one.
