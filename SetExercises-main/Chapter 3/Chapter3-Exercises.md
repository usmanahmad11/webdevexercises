# Chapter 3 Exercises - Images

Exercises under the heading **Assessment Exercises** must be completed as part of the Set Exercises assessment. You will find additional optional exercises which can be completed to gain higher marks. 

For each exercise you should create a new project with the name of the exercise and save it to this exercises folder in your local repository. Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Set Exercises Assessment.

## Assessment Exercises 

### Three images :ballot_box_with_check:

In a new index.html file display three images (that you would be legally allowed to use for a commercial project) and do the following: 

* Select a theme which ties all three images together (example nature, citylife, gaming, etc.).
* Give each image an appropriate alt attribute.
* Give each image appropriate width and height attributes (retaining its original aspect ratio). 
* Give each image an appropriate title attribute.
* Use CSS filters to change the appearance of all three of your images.
* Underneath each image, provide information on its copyright license. 

### Styling those divs :ballot_box_with_check:

Copy the below html and css files into a new directory. Edit style.css so that the four ```div``` elements in index.html will have a filter look like this: 

![image](https://drive.google.com/file/d/1C-UmpOCYXqwEBgLc6laZkGKvMws38ti6/view?usp=sharing)

#### index.html:

```<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" type="text/css" />
    <link rel="stylesheet" href="additionalStyle.css" type="text/css" />
    <title>Styling those divs</title>
  </head>
  <body>
    <div id="A">div#A</div>
    <div id="B">div#B</div>
    <div id="C">div#C</div>
    <div id="D">div#D</div>
  </body>
</html>
```

#### style.css:

```
div {
  display: inline-block;
  font-family: sans-serif;
  font-size: 20px;
  margin: 25px;
  border: 4px solid black;
  line-height: 100px;
  text-align: center;
  width: 200px;
  height: 200px;
}

body {
  margin: 100px auto;
  width: max-content;
}

div#A {
  border-color: blueviolet;
}
div#B {
  border-color: lime;
}
div#C {
  border-color: darkorange;
}
div#D {
  border-color: firebrick;
}
```

## Bonus Assessment Exercise 

### Image Hitmap

Read the following tutorial: [Add a hitmap on top of an image](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Add_a_hit_map_on_top_of_an_image) and create your own hitmap. Again, images must be cleared for commercial use. Your idea doesn't have to be overly complicated. Here are some suggestions: 

* Example: A country/world map linking to Wikipedia pages for different continents/regions etc.
* Example: An image of the inside of a computer linking to different explanation/sales pages.
* Example: A map of BathSpa university that links to relevant course pages. 


