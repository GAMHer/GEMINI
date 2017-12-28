![GEMINI Logo](https://images2.jewelexi.com/zodiac-signs/images/medium/gemini-picture.png "Graphically Enhanced MICMAC's New Interface")

## GEMINI

**GEMINI is the new Graphical User Interface for MICMAC.**

Developed by [Alessio Calantropio](https://www.swas.polito.it/rubrica/scheda_pers.asp?matricola=037454) of [Politecnico di Torino](https://www.polito.it/index.php?lang=en) under the GAMHer Italian Research Project.

* * *

### Download

Download GEMINI to use it for your MICMAC dataset:

* [Last version](https://github.com/GAMHer/GEMINI/archive/master.zip)

* * *

### Installation

**If you don't have Node.JS installed or you need to update it (recommended):**

1. Remove any old version of  Node.JS and NPM

   To do so, open a terminal and type the following commands:
   
   `sudo apt remove nodejs npm`

1. Install Node.js with Ubuntu Package Manager.
   
   To install Node.js and Node Package Manager (NPM), open a terminal and type the following commands:

   `curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -`
   
   `sudo apt-get install -y nodejs`

2. Create a symbolic link so node will map to nodejs:

   `sudo ln -s /usr/bin/nodejs /usr/bin/node`

3. Test it:

   `node --version`
   
   `npm --version`

   These should output a valid version like v6.12.2 and 5.6.0
   
4. You may additionally run the followings:

   `sudo apt-get update`
   
   `sudo apt-get upgrade`
   
   `sudo apt-get autoremove`

5. Follow the instruction from the section below (If you have Node.JS installed and updated).

**If you have Node.JS installed and updated:**

1. Download latest release of GEMINI from the above [download link](https://github.com/GAMHer/GEMINI/blob/master/README.md#download)

2. Extract the GEMINI folder from the zip file

3. Open the terminal into the interface folder and run the following to download NW.js to the node_modules folder in the GEMINI main folder:

4. `npm install`

You''ll only ever need to run this once.

**Run GEMINI Interface:**

Now that you’ve got Node installed, from now on you’ll be able to just run the following command launching a terminal inside the GEMINI main folder to start the interface :

   `npm start`

* * *

### What is GEMINI?

Description

* * *

### Known Issues

* Starting the interface you may encounter an `ERROR:browser_main_loop.cc(170)`. This won't affect the correct functioning of the software.

* * *

### Credits

**People**

* [Marc Pierrot Deseilligny](http://micmac.ensg.eu/index.php/Marc_Pierrot-Deseilligny) - Is a senior researcher (directeur de recherche) at IGN. Currently he is working at ENSG and at LaSTIG.

* [Fulvio Rinaudo](https://didattica.polito.it/pls/portal30/sviluppo.scheda_pers_swas.show?m=1821) - Is full professor at Politecnico di Torino

* [Filiberto Chiabrando](https://didattica.polito.it/portal/pls/portal/sviluppo.scheda_pers_swas.show?m=012702) - Is researcher at Politecnico di Torino.

**Software**

* [MICMAC](http://micmac.ensg.eu/index.php/Accueil) - MicMac is a free open-source (Cecill-B licence) photogrammetric suite that can be used in a variety of 3D reconstruction scenarios. In aims mainly at professionnal or academic users but constant efforts are made to make it more accessible to the general public.

* [UGUI](https://github.com/UniversalGUI) - Universal Graphical User Interface - UGUI gives a face to command line applications using HTML, CSS, & JavaScript.

* [Node.JS](https://github.com/nodejs) - Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. The Node.js package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

* [NPM](https://github.com/npm) - A package manager for javascript.

* [NW.js](https://github.com/nwjs) - NW.js is an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js. It also lets you call Node.js modules directly from the DOM and enables a new way of writing native applications with all Web technologies.
