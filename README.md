# This project is about D3 and Data application in Journalism


![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

The tasks to bee accomplished was analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings.

The News Editor can run a series of feature stories about the Health Risks faced by particular demographics. First story was broused through. Then idea was to do sifting through the latest information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

## Tasks Accomplished as D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

A scatter plot was to be created between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques  a scatter plot that represents each state with circle elements was to be created. The graphic was  coded in the `app.js` file.The data was pulled from `data.csv` by using the `d3.csv` function. The Scatter plot was made to ultimately appear like the image at the top of this section.

* State abbreviations in the circles for States was added.

* Axes and Labels to the left and bottom of the chart was Created and situated.  your 

* Note:  `python -m http-server` can be used to run the visualization. This will host the page at `localhost:8000` in your web browser.

- - -

### Level 2: Make the Graph Interactive


![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

More demographics and more risk factors was to be included.Additional labels labels place in our scatter plot and give them click events so that our users can decide which data to display. Animated the transitions for our circles' locations as well as the range of your axes. Done it for two / three risk factors for each axis. Or, for an extreme challenge.

* Binding all of the .csv data to our circles does the magic. This let us easily determine their x or y values when we click the labels.

#### 2. Incorporate d3-tip

The ticks on the axes allow us to infer approximate values for each circle. Hoever it's impossible to determine the true value without adding another layer of data. With tooltips: we implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Adding tooltips to our circles and displaying each tooltip with the data that the user has selected. The `d3-tip.js` plugin developed by [Justin Palmer] was used.(https://github.com/Caged)—we've already included this plugin our directory.

![8-tooltip](Images/8-tooltip.gif)

* The following example was reffered [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how we should implement tooltips with d3-tip.

