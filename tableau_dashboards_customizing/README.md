
# Tableau Dashboards - Customizing

## Introduction
Until now we have been using the workbook in Tableau and getting used to the interface. Now we will take your Tableau skills one step further and dive into one of the most useful features of Tableau, the _Dashboard_. We will make a few vizes and add them into a dashboard and learn how to arrange and customize the dashboard so the necessary data is featured. We will then explore some of the interactive objects and see how they can be used to allow the viewer to change the view to their needs.

## Objectives
You will be able to: 
* Create and format both horizontal and vertical containers
* Locate and use each of the dashboard objects available
* Add interactive elements to the dashboard

## Creating a Dashboard
The first step in creating a _Dashboard_ is to open a blank dashboard. There are two ways to do this:
* __The Menu Bar__ - In the menu bar at the top of the interface you will see __Dashboard__. Click on this drop down and you will see the options for _Dashboard_. Your first option should be __New Dashboard__, click on this option and you will be taken to a new, blank dashboard.
* __New Dashboard__ tab at the bottom of the interface. To the right of the _New Worksheet_ tab, you will find the _New Dashboard_ icon, click on this icon and you will be taken to a new, blank dashboard.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/new_dashboard.png" alt="Image of the icon to click to open a new dashboard" height=50>

## Containers
_Containers_ are Tableau's way of assigning and formatting a space for elements of your dashboard. There are two types of containers: _Horizontal_ and, you guessed it, _Vertical_. To create a container you will simply drag either the _Horizontal_ or _Vertical_ container into the workspace. Once you have a container, you can begin adding worksheets or objects. Containers are how you group items in the dashboard, and they can be nested as much as you wish. As you add items to a container Tableau will highlight how the items will be arranged once you drop the item. To change the arrangement, simply move around the container until you are satisfied with the final placement. Working with containers can take some practice, but becomes very intuitive once quickly.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/containers.png" alt="Image of horizontal and vertical container buttons in the objects pane" height=250>

## Device Type
In today's business environment, there are multiple platforms for interacting with software, and Tableau did not leave this to chance. At the top of the _Dashboard Pane_ you will see the default device layout selected, which may already be __Phone__. You will likely want to add another view such as _Desktop_, which can be done with the menu at the top of the interface, by clicking on __Dashboard>Device Layouts>Add Desktop__. This option lets you see what your dashboard will look like on different devices, so you can ensure it will be visible. You can even customize the view for each device format. If you want to remove a device, you can hover over it on the _Dashboard Pane_ and click on the `...` and you will find the options for that device layout including _Delete Layout_.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/devices.png" alt="Image of horizontal and vertical container buttons in the objects pane" height=150>

## Objects
There are some very useful _Objects_ provided by Tableau that allow you to add many useful components to your dashboard. Below is a list of a few of them.

* _Text_ - This object is useful for adding text boxes in your dashboard to help convey information about your dashboard to the viewer.
* _Image_ - This object is for adding images to your dashboard such as a logo
* _Web Page_ - This object allows you to embed a web page in your dashboard
* _Navigation_ - This object allows you to create a link to any part of the workbook so the viewer can look closer at some component.
* _Download_ - This object allows you to embed a button for the viewer to download the viz as a PDF or an image file.

_Ask Data, Data Story, and Extension_, are not compatible with Tableau Public. If you would like to research their uses, you can look through the documentation on the <a src="https://www.tableau.com/" target="blank">Tableau Website</a>

### Working with Objects
Objects can be placed in the dashboard in one of two manners, either _Tiled_ or _Floating_ you need to select the attribute you wish to apply before adding the object to the dashboard. The _Floating_ attribute allows the object to be placed anywhere on the dashboard and can be overlapping any part of the view. The _Tiled_ attribute forces the object to share the space with the other objects in the container. If your container has more than one object in it, you will notice that you can determine how the item is placed based on the position you drop it in. Tableau will highlight the position the object will align to as you hover over the container. The same is true for containers as you are adding them to the dashboard.

You can modify the attributes of the individual containers and objects by selecting the item. When the item is selected you will see some options similar to the following image:

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/container_options.png" alt="Image of the remove container button and the arrow to access the more options menu" height=75>

Clicking on the down arrow will reveal the _More Options_ menu which will allow you to change the attributes of that object or container.

## Interactive Elements
The beauty of the Dashboard in Tableau is that you can make it interactive for the viewer so they can change the view of the data to fit their own questions. One way this is done is with _Filters_. Opening up the _More Options_ menu on a worksheet will offer you the option to add a _Filter_ by selecting the data feature you wish to filter by. This will add a box with the different options you can filter the data by. The viz in the dashboard will be filtered according to the viewers selection. By default the viz will be updated automatically, but this can be disabled in the _More Options_ menu.

## Summary
In this lesson we introduced the idea of a Dashboard and the components of the Dashboard. You learned how to create both _Horizontal_ and _Vertical_ containers and how the containers respond to objects added. You learned about a few of the _Objects_ Tableau has to offer and a little about each of them. You also were introduced to the interactive nature of the dashboard and how the viewer can be able to change the viz to suit their needs. In the next lesson, we will practice using all of these tools and dive a little deeper into how each of them can make your dashboard more useful.
