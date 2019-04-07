---
title: "Basic Usage"
permalink: /docs/basic-usage/
excerpt: ""
last_modified_at: 2019-03-30
toc: true
---
Try the following steps in order to test the extension and to learn the basic functionality.

**Tip:** If you are new to Inkscape, have a look at their [Basic Tutorial](https://inkscape.org/en/doc/tutorials/basic/tutorial-basic.html) first.
{: .notice--info }

## Step 1 - Draw an Object

Create an object, e.g. a circle and make sure it has a fill.

![Circle with fill color](/assets/images/docs/en/basic-usage-circle-fill-color.png)

## Step 2 - Convert to Path

Transform **all objects** you want to stitch to paths:

* Select all objects (`Ctrl+A`)
* `Path > Object to Path` or `Ctrl+Alt+C`.<br>

**Info:** Objects that are not of "path" type, are ignored by Ink/Stitch.
{: .notice--warning }

## Step 3 - Parametrize SVG Path for Embroidery

* Select at least one object.
* Open `Extensions > Ink/Stitch > English > Params`.
* Play with the values. The simulator will update whenever you change the settings.
* For now, close without saving.

## Step 4 - Create the Embroidery File

* Run `File > Save as...`
* Navigate to the folder where you would like to save the file
* Choose the correct file format for your machine
* Click `Save`
* Copy the file to your machine

**Tipp:** Make sure to save the file as an SVG file as well. Then you will always be able to modify it easily.
{: .notice--info}

## Workflow

If this worked well, we recommend to also read through the next page (workflow). Where you can get a deeper insight into Ink/Stitch and you can learn how to perform essential functions for embroidery files, like e.g. ordering objects, etc.

If you run into trouble, contact us through [GitHub](https://github.com/inkstitch/inkstitch/issues/). We really like to hear about your problem, this way we can either improve the documentation or the programm itself.
