# Homematic Fensterkontakt – verdeckter Einbau

Dieses Projekt bassiert auf der Bibliothek AskSinPP (https://asksinpp.de). Es handelt sich hierbei um einen Nachbau des "Homematic IP Fenster- und Türkontakt – verdeckter Einbau" welcher für den unsichtbaren Einbau im Fenster konzipiert wurde.


## Material

Für das Projekt wird ein Arduino Pro Mini 3,3V, ein 868 MHZ Modul (CC1101), 

| Anzahl | Typ |
| ------------------ | ------------------ |
| 1 | Arduino Pro Mini 3,3V |
| 1 | CC1101 Modul (868 Mhz) |
| 2 | 0805 SMD Widerstand |
| 1 | 0603 SMD LED grün |
| 1 | 0603 SMD LED rot |
| 1 | SMD-Kurzhubtaster, 4,2 x 2,8 mm |


## Hardware

Alle genannten Bauteile müssen an der dafür vorgesehene Stelle verlöten werden. (Siehe Bilder/Schaltplan)

## Software

Als Sketch findet folgender Anwendung: https://github.com/jp112sdl/Beispiel_AskSinPP/blob/master/examples/HM-SEC-SC/HM-SEC-SC.ino
Für das flashen muss man sich an die allgemeine Anleitung halten: https://asksinpp.de/Grundlagen/02_software.html


## Gehäuse

Für das Gehäuse findet ein 3D Druckteil Anwendung, welches von Thingiverse heruntergeladen werden kann.


[Thingiverse](https://www.thingiverse.com)



## Making your first edit

When you make any change to any file in your project, you’re making a **commit**. If you fix a typo, update a filename, or edit your code, you can add it to GitHub as a commit. Your commits represent your project’s entire history—and they’re all saved in your project’s repository.

With each commit, you have the opportunity to write a **commit message**, a short, meaningful comment describing the change you’re making to a file. So you always know exactly what changed, no matter when you return to a commit.

## Practice: Customize your first GitHub website by writing HTML code

Want to edit the site you just published? Let’s practice commits by introducing yourself in your `index.html` file. Don’t worry about getting it right the first time—you can always build on your introduction later.

Let’s start with this template:

```
<p>Hello World! I’m [username]. This is my website!</p>
```

To add your introduction, copy our template and click the edit pencil icon at the top right hand corner of the `index.html` file.

<img width="997" alt="edit-this-file" src="https://user-images.githubusercontent.com/18093541/63131820-0794d880-bf8d-11e9-8b3d-c096355e9389.png">


Delete this placeholder line:

```
<p>Welcome to your first GitHub Pages website!</p>
```

Then, paste the template to line 15 and fill in the blanks.

<img width="1032" alt="edit-githuboctocat-index" src="https://user-images.githubusercontent.com/18093541/63132339-c3a2d300-bf8e-11e9-8222-59c2702f6c42.png">


When you’re done, scroll down to the `Commit changes` section near the bottom of the edit page. Add a short message explaining your change, like "Add my introduction", then click `Commit changes`.


<img width="1030" alt="add-my-username" src="https://user-images.githubusercontent.com/18093541/63131801-efbd5480-bf8c-11e9-9806-89273f027d16.png">

Once you click `Commit changes`, your changes will automatically be published on your GitHub Pages website. Refresh the page to see your new changes live in action.

:tada: You just made your first commit! :tada:

## Extra Credit: Keep on building!

Change the placeholder Octocat gif on your GitHub Pages website by [creating your own personal Octocat emoji](https://myoctocat.com/build-your-octocat/) or [choose a different Octocat gif from our logo library here](https://octodex.github.com/). Add that image to line 12 of your `index.html` file, in place of the `<img src=` link.

Want to add even more code and fun styles to your GitHub Pages website? [Follow these instructions](https://github.com/github/personal-website) to build a fully-fledged static website.

![octocat](./images/create-octocat.png)

## Everything you need to know about GitHub

Getting started is the hardest part. If there’s anything you’d like to know as you get started with GitHub, try searching [GitHub Help](https://help.github.com). Our documentation has tutorials on everything from changing your repository settings to configuring GitHub from your command line.
