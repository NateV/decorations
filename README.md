# decorations

This repository contains examples of adding decorations to Legal
Server.

## Contents

* `music.html`: This adds a picture in which the mouse cursor is
  either Santa and Reindeer or a dreidel, depending on a random
  number.  It also includes an audio widget for playing a random
  holiday song.
* `snow.html`: This adds an animation of falling snow at the top of
  the home screen.
* `xmas-lights.html`: This adds blinking Christmas lights to the blue
  navigation bar of the Legal Server home page.
* `xmas-other.html`: This adds a variety of other holiday decorations
  to the Legal Server home page, such as the replacement of "Home" in
  the breadcrumb navigation with "Ho, ho, home!", "wrapping paper" in
  the sidebar, and a Christmas tree in the background.

## Instructions

Log into Legal Server as an Administrator.

Go to Admin -> Processes, Forms, and Profiles

Set "Forms and Processes for Module" to "Home/Section Front"

On the Profiles tab, click the edit icon next to your main "Home"
profile.

Scroll down to where you see the "Add" button.

Set the pull-down selector to "Instruction" and click "Add."

This will add an "Instruction" as an "Enabled" form element.

Open up the instruction's properties by clicking the blue triangle.

Check the checkbox next to "Format as HTML."  This is very important!

Copy and paste the contents of one of the HTML files in this
repository into the "Text" of the Instruction.

Then press "Continue" or "Save & Stay on Page" to save your work.

## Customization

The HTML snippets contain URL referencse to image files hosted on the
web site of Philadelphia Legal Assistance.  E.g.,
`https://philalegal.org/html/night.jpg` You can see what each of these
images looks like by selecting the URL, copying it, opening a new tab
in your web browser, and then pasting the URL into the location bar.
If you want to use a different image, just change the URL.  For
example, `https://philalegal.org/html/night.jpg` is a nighttime
picture of Philadelphia.  You might want to change this to a URL for a
nighttime picture of your city.  If you have an image on your computer
that you want to make available at a URL, talk to your IT director
about putting the image on your organization's web site.

The JavaScript code inside the HTML snippets also contains some
if/else statements based on random numbers.  For example, the code
that places some "holiday wrapping paper" in the Legal Server sidebar
is programmed to use one pattern 50% of the time, another pattern 25%
of the time, and a third pattern (a Hanukkah pattern) 25% of the time.
You might want to change these ratios by tweaking the random number
thresholds, which are numbers between 0 and 1.

## Bonus customization: random cat picture

* `random-cat.html`: You can place this in any auxiliary form.  It
  displays a link saying "Click here to display your visual reward!"
  and when you click it, you see a random picture of a cat, courtesy
  of the Cat API.

## Second bonus customization: puppies tab

* `puppies.html`: From the "Home/Section Front" area of your
  "Processes, Forms, and Profiles," go to "Tab Blocks" and edit one of
  the "tab blocks" that is used by your Home screen.  Add a "Tab"
  called "Puppies" and include this HTML as an instruction.

## Contact

Contact [Jonathan Pyle](mailto:jpyle@philalegal.org) at [Philadelphia
Legal Assistance](https://philalegal.org), 215-981-3843, with any
questions.
