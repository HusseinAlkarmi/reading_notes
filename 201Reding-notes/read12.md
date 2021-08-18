# read 12

## Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

< canvas id="buyers" width="600" height="400"></ canvas>

## Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:

< canvas id="countries" width="600" height="400"></ canvas>


## Drawing a bar chart
Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:

< canvas id="income" width="600" height="400" ></ canvas>

## Next, we retrieve the element and create the graph:

var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);

## And finally, we add in the bar chart’s data:

var barData = {

	labels : ["January","February","March","April","May","June"],
	datasets : [

		{
			fillColor : "#48A497",

			strokeColor : "#48A4D1",

			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",

			strokeColor : "rgba(72,174,209,0.4)",

			data : [364,504,605,400,345,320]
		}

	]
}


# Audio, Video, Images


![cssImg](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdoBCbELJB4WX6gP1AWmPku_PclctyAx_sig&usqp=CAU)



Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.



```

img.large {   width: 500px;   height: 500px;} 

img.medium {   width: 250px;   height: 250px;}

img.small {   width: 100px;   height: 100px;}

```

## repeating Images

- repeat

The background image is repeated both horizontally and vertically (the default way it is shown if the background- repeat property isn't used).



- repeat-x

The image is repeated horizontally only (as shown in the first example on the left).



- repeat-y

The image is repeated vertically only.



## Background posItIonbackground-position



```

body {  background-image: url("images/tulip.gif");  

background-repeat: no-repeat;  

background-position: center top;}

```



## Practical information

To wrap up the book we are going to look at some practical information that will help you launch a successful site.



**hoW to identify keyWords and Phrases**

1. Brainstorm

List down the words that someone might type into Google to find your site. Be sure to include the various topics, products or services your site is about.



2. organize

Group the keywords into separate lists for the different sections or categories of your website.



3. research

There are several tools that let you enter your keywords and then they will suggest additional



*HTML5 video and audio*



The `< video>` and `< audio>` elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:



```

<video controls>

  <source src="rabbit320.mp4" type="video/mp4">

  <source src="rabbit320.webm" type="video/webm">

  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>

</video>

```

## how Flash works

Since the late 1990s, Flash has been a very popular tool for creating animations, and later for playing audio and video in websites.



**Timeline:Flash, Video & audio**

Web technologies change quickly. Here you can see some of the changes in how animation, video, and audio are created on the web.