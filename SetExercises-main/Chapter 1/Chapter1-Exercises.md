# Chapter 1 Exercises - Intro to HTML

Exercises under the heading **Assessment Exercises** must be completed as part of the Set Exercises assessment. You will find additional optional exercises which can be completed to gain higher marks.

For each exercise you should create a new project with the name of the exercise and save it to this exercises folder in your local repository. Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.

## Assessment Exercises

### Simple HTML Document :ballot_box_with_check:

Create a new index.html file and include the following:

- All of the mandatory structural elements.
- Six headings using all of the `<h>` tags.
- A paragraph of text underneath your headings.
- Make sure the code is indented and spaced properly.
- Add comments explaining what each element does.

### Fix me :ballot_box_with_check:

Copy the below `index.html` and `syles.css` code into two seperate files in a new Fix Me folder.

Look through both files and fix all of the errors that you can find. Do the following:

- Ensure that styles.css is appropriately linked in your index.html file
- Fix Missings tags, incorrectly typed tags, spelling mistakes, missing brackets etc.
- Make sure the code is indented and spaced properly.
- Add comments explaining what each line of the code does.

#### index.html:

<!doctype html>
    <html lang="en">
<head><metacharset="utf-8"><title>FIXME!</title>
    <link rel="stylesheet" href="fixme.css">
    <link .css>
<h1Alice’s Adventures<br in
            Wonderland
p class="author">
By Lewis Carroll</p>
        <h2>Chapter I. Down the Rabbit-Hole</h2>
            Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, ‘and what is the use of a book,’ thought Alice ‘without pictures or conversations?’
        </p>
        p>
            So she was considering in her own mind (as well as she could, for the hot day made her feel very sleepy and stupid), whether the pleasure of making a daisy-chain would be worth the trouble of getting up and picking the daisies, when suddenly a White Rabbit with pink eyes ran close by her.
        </p>
        <p
There was nothing so <em>very</em remarkable in that; nor did Alice think it so <em>very</em> much out of the way to hear the Rabbit say to itself, ‘Oh dear! Oh dear! I shall be late!’ (when she thought it over afterwards, it occurred to her that she ought to have wondered at this, but at the time it all seemed quite natural); but when the Rabbit actually <emtook a watch out of its waistcoat-pocket/em>, and looked at it, and then hurried on, Alice started to her feet, for it flashed across her mind that she had never before seen a rabbit with either a waistcoat-pocket, or a watch to take out of it, and burning with curiosity, she ran across the field after it, and fortunately was just in time to see it pop down a large rabbit-hole under the hedge.
</p>
    </body>
</html>


#### style.css:

h1 { font-size: 3 rem;
    text-align: center; h2 {font-size: 1. 25rem
    text-align: center;
}

p {
    line-height: 1.3;
}

        #author {
font-size: 1.1rem;
        text-align: centre
    style-font: italic; }



    body-background-color: aliceblue;
    fontfamily: Georgia, serif;
}


Your working code should produce the following result: https://drive.google.com/drive/folders/1L92YJHoU3AemYk7lvMsGFQR41AAeyFDM 




### Replace Me :ballot_box_with_check:

Copy the below index.html code into a new file. Replace all of the inline CSS with a new external CSS document.

Hint: In order to complete one part of this you will need to understand how to use CSS classes.

Hint2: You should aim to achieve this using only four blocks of CSS in your style.css document.

```<!DOCTYPE html>
<html lang="en" style="background: #eeeeee">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Replace Me</title>
  </head>
  <body>
    <h1 style="font-size: 35px; color: #ff0000; text-align: center; font-family: Arial, Helvetica, sans-serif; text-decoration: underline">
      Remove all of the Inline CSS
    </h1>
    <p style="font-size: 18px; color: #111111; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
    <p style="font-size: 18px; color: #111111; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
    <p style="font-size: 18px; color: #111111; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
    <p style="font-size: 18px; color: #111111; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
    <p style="font-size: 18px; color: #111111; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
    <p style="font-size: 18px; color: #00ff00; font-weight: 700; font-family: Georgia, 'Times New Roman', Times, serif">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
      anim id est laborum.
    </p>
  </body>
</html>
```

## Bonus Assessment Exercise

### HTML and CSS Resource

Create a HTML & CSS quick-reference guide that covers all of the tags we've covered so far (and a few extras) with a description of how to use them and code examples.

- Use an external stylesheet.
- Be creative with your styling, but keep it professional.
- Use the `<code>` and `<pre>` HTML tags to include code examples.
- Include a minimum of 10 HTML tags.
- Include a minimum of 8 CSS properties.
- Include a variety of different headers.
- Make sure the code is indented and spaced properly.
