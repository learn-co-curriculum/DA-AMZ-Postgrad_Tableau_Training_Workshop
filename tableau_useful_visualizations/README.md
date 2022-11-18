
# Tableau - Useful Visualizations

## Introduction
Tableau offers many visualizations for communicating your data to viewers and stakeholders. In this lesson, we will highlight a few of these vizes that are likely to be used more often. We will take a look at the types of data necessary for each of these very useful vizzes.

## Objectives
You will be able to: 
* Choose a viz from the Show Me Pane
* Identify the data type necessary for a specific viz
* Understand the possible use cases for some of the most useful vizzes

## Show Me Pane
The _Show Me Pane_ contains the selection of visualizations you have to choose from for your worksheet. Once you have selected data to display, Tableau will begin highlighting the vizzes that are compatible with the type of data selected. If you are not sure of the type of data needed for a viz you can hover over the viz in the Show Me Pane and Tableau will show suggestions for the type of data suitable.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/show_me_pane.png" alt="Tableau Show Me Pane with the selection of available vizzes" height=450>

## Bar Chart
 A _Bar Chart_ is used to visualize the relationship between a categorical measure and a continuous measure. If you hover over the _Bar Chart_ in the _Show Me Pane_ you will see that Tableau suggests __0 to 2 Measures__ and __0 or more Dimensions__. In previous lessons we have used a basic _Bar Chart_ in order to get familiar with the Tableau interface and the workspace. A _Bar Chart_ can be composed of either vertical or horizontal bars which can be beneficial to fitting the chart into a presentation. Much more information can be conveyed to the viewer via the built in tools Tableau has to offer, for example, you can add a diverging red-green color palette to indicate whether sales is positive or negative by using the _Color_ marks card. You can add some information to the ends of the bars with the use of the _Label_ card by adding some formatting options such as the _currency_ option. Below is an example of a _Vertical Bar Chart_.

 <img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/v_bar_chart.png" alt="Example of a bar chart" height=400>

## Scatter Plot
While a bar chart will allow you to visualize a categorical measure in relation to a continuous measure, you might want to see how two continuous measures relate to each other, in this case, the _Scatter Plot_ is a useful tool. The _Scatter Plot_ is useful for visualizing the relation of one measure to another, such as the total _Sales_ in relation to the total _Profit_. Hovering over the image for the _Scatter Plot_ in the _Show Me Pane_ you will reveal that Tableau suggests __2-4 Measures__ and __0 Dimensions__ are necessary to generate a _Scatter Plot_. Some of the features of a _Scatter Plot_ which help to convey important information include the addition of shapes, color, and size. Another very useful feature of the _Scatter Plot_ is the ability to add a _Trend Line_ which helps to show the general direction all of the data is heading. Below is an example of a _Scatter Plot_ with a _Trend Line_ applied.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/scatter_plot.png" alt="Example of a scatter plot with a trend line applied" height=400>

## Line Graph
A _Line Graph_ is useful for visualizing a measure over time and can help to identify seasonality in the data. Hovering over the _Line Graph_ in the _Show Me Pane_ will show the
Tableau suggestion of __1 Date__ and __0 or more Measures__ needed for generating a _Line Graph_ and example of a date field would be _Order Date_ and a measure would be _Profit_. This combination would show the increase or decrease in _Profit_ over specific periods. The period of the graph can be adjusted by clicking on the measure in the _Columns_ shelf and choosing the period from the drop-down. This will allow you to change the view from monthly, to daily, to quarterly, etc. Below is an example of a _Line Graph_ showing the _Profit_ quarterly.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/line_graph.png" alt="Example of a line graph with quarterly intervals" height=350>

## Summary
Great, now you know about some of the most useful vizzes that Tableau has to offer. You also got to see how to select which of these vizzes you want to work with along with the types of data needed to generate each of them. We also took a brief look at possible use cases for each viz to better understand how they can be useful. Now that we have looked at what is available, we will practice making a few of these in the next lesson.
