# Managed Services for Machine Learning
This repository is a summary of the content of lesson six of the *Introduction to Machine Learning on Azure* course which is part of the *Microsoft Scholarship Foundation course Nanodegree Program* on *Udacity* (July - September 2020).

As part of our role as student leaders, we will not only write this guide book, but also answer commonly asked question of the community. Furthermore, we will provide a list of resources to support your success in this course.

**You can do it!**

## Introduction

Managed services for Machine Learning can be used to *outsource* your local Machine Learning processes (Training, Inference and Notebook Testing) to the cloud. By using end-to-end automation via pipelines (DevOps for ML / MLOps), you can deploy to production environments easily. The examples in this lesson will use services provided by Azure Machine Learning.

In comparison to local development, you don't need to install any applications and libraries, as all this has been done already. You don't have to take care of the *low level* layers, so you can jump right in using your webbrowser!

Speaking of using your webbrowser, you might already know from the previous lessions, that you need to prelaunch your lab environment to get the scholarship account details. Visit [this page](https://classroom.udacity.com/nanodegrees/nd00332/parts/9e5002de-e740-4eb2-aa15-03861fff12fc/modules/ae74a72a-97c1-4306-b55e-708c58118bd2/lessons/ff14cb2c-d367-4f57-9f35-244fd1aceda2/concepts/0d9d532d-d0e3-4a76-bfa3-fd6630372628) and click on the blue *Prelaunch Lab* button before moving on.


## Labs
### Lab 1: Compute Resources
In this lab, you will learn how to create a new compute resource, how to modify an existing one and how to stop, restart or delete it.

1. [Open Workspace](https://classroom.udacity.com/nanodegrees/nd00332/parts/9e5002de-e740-4eb2-aa15-03861fff12fc/modules/ae74a72a-97c1-4306-b55e-708c58118bd2/lessons/ff14cb2c-d367-4f57-9f35-244fd1aceda2/concepts/50fa8755-d4eb-413d-9b5d-6277671452b2)
2. Enter the *Studio* by clicking *Launch now* and select a subscription and workspace as mentioned in the lab guide.
3. Select *Compute* in the right menu.
4. Select the *Compute instances* tab.
5. Click on the *Create* button, choose a unique name of your choice and select a virtual machine from the dropdowns. For this lession, we will be using a CPU-based VM with size *Standard_D3_v2*.
6. Click on *Create* and wait a few seconds (took 8 minutes in my case) until the shown status changes to *Running*.
7. Select your compute resource in the list and click on its name to view details about the compute. You can also click on any of the buttons to stop, delete or restart the resource.
8. Go back to the list of computes and take a look at the *Application URI* column. By clicking on any of the links, a new browser tab with the respective development environment will be launched. 
![screenshot of the list of compute resources](images/lab-1-list.jpg)

## About

### Contributing
Feel free to send pull requests or open an issue if you have any questions.

 All commit messages should follow the [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/).

### License
The content of this repository is released under the [MIT license](LICENSE).