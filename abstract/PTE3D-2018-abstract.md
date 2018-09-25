---
title: From parchment to 3D to HTML&#58; the use of the 3D and the Web in architectural history research (a case study)
author: Dr. Bereczki Zoltán
bibliography: /Users/zbereczki/Dropbox/Bibdesk-library/Library.bib
csl: /Users/zbereczki/Documents/tudomany/csl/ieee.csl
---

**Index Terms:** architectural history, Middle Ages, Gothic, construction, Vienna, GitHub, Jekyll, WebGL, Rhinoceros 3D, open source

# Abstract

The construction of Gothic church towers with carved stone spires and often with significant height required the most advanced technology and financial support of their age, and the application of advanced machines was also inevitable for it. In my PhD thesis defended in 2017 I attempted to reconstruct the process of a 15th-century tower construction, including the main auxiliary structures: scaffoldings and machinery, on the example of the unrealised north tower of the St. Stephen’s church in Vienna, with the use of mostly contemporary sources. [@bereczki_2017_gotikus] While creating the images for the final version of the thesis I faced the problem that the paper as a medium is only able to communicate fragments of the information contained by the 3D model. This project is the result of this realisation, so it serves as an extension of the printed thesis: I created an online visualisation of the model with animations, embedded models, and links to the most important and online available drawn sources.

# Introduction

One of the main questions of the research of the mediæval technical drawings is whether they served as a modern blueprint or not; so was their main purpose to make possible the realisation of a structure (machine, building), or something else (education, representation, etc). [@bucher_design_1968] [@lefevre_picturing_2004] [@bereczki_machine_2015] The most reassuring way to answer this question would be conducting a lifesize experiment: to construct the structures relying only on the drawings representing them. Since there is hardly an opportunity to achieve this, 3D-modelling emerges as a solution.

It is important to emphasise – as it is discussed in several papers written by Norbert Nußbaum of the University of Cologne –, that the Gothic construction praxis cannot be generalised. While the forms could spread on paper or parchment, the technical details, solutions could not. [@nusbaum_form_2010] [@nussbaum_planning_2011] [@nussbaum_planen_2012] So not only I do not state that a particular tower was constructed this way, but I also do not state that Gothic towers were generally constructed this way: my 3D model and the resulting drawing series and website illustrate a possible solution, based almost exclusively on contemporary sources. As far as I know a similar representation of a Gothic tower’s construction – illustrating not only the tower, but also the auxiliary structures, based on historic sources – wasn’t published in the literature yet.

# The 3D reconstruction

During my research I modelled the partially realised north tower of the St. Stephan's church in Vienna using exclusively its contemporary (15th-century) plans. I choose wittingly an unrealised tower, as I wanted to avoid any possible misunderstanding. I do not want to introduce how a particular tower was built (this would be impossible), but how a tower could have been constructed using the instruments in the discussed sources. 

For the construction of a tower the scaffolding and machinery are the most important auxiliary structures. Accordingly, my model about the construction consists of three main parts: the tower itself, the scaffoldings, and the machines. The detailed description of the non-written sources used extends beyond the scope of this abstract, so here I merely list the most important ones. 

The two most complete plans of the Viennese north tower are in the collection of the Wien Museum Karlsplatz: the drawing no. 105.064 (a floor plan) and the drawing no. 105.067 (an elevation). [@kronberger_dombau_2011] I used these two drawings for my model. The two are mostly coherent. Where conflict emerged, I considered the floor plan relevant. Since my goal was to reconstruct a structure based solely on original designs, I used only the drawings for the model; photos of the realised parts of the tower were used only for the interpretation of the drawings. Thus, the parts that are not visible on the drawings and can not be deduced (mostly the east and west facades of the ground floor) are only schematic.

Discussing the machines, the mediæval machine drawings survived almost only in warfare-themed manuscripts. Notable exception is the portfolio of the Strasbourg master Hans Hammer, where many machine drawings can be found, likely in connection with the tower plans of the master. [@fuchs_introduction_1992] [@bereczki_machine_2015] I used mainly this manuscript for the reconstruction of the machines.

The survived contemporary drawings about scaffoldings are almost exclusively book illuminations and paintings, these were my main sources for the modelling of the scaffolding. [@binding_mittelalterliche_2001] An additional source available from the Modern Age, but before the age of industrialisation is the detailed drawing and description of the scaffolding used during the early 19th-century reconstruction of the top of the south spire at the St. Stephen’s church. [@trost_umbau_1843] Further important sources of information were the surviving or reconstructable scaffoldings inside of Gothic towers and the related literature. [@tatton-brown_building_1997] [@jones_salisbury_2005] [@jones_ironwork_2005] [@caston_spatmittelalterliche_1997]

My modelling software of choice was the Rhinoceros 3D. The modelling of the tower was carried out by drawing the outlines of the different storeys on the floor plan from one level to another, starting from the outside. It was possible because of a unique characteristic of the Gothic floor plans: they represent the different levels (every storey) of the whole structure on one drawing. When the contour of one level was ready, I determined the height of the contour on the elevation drawing and raised up the contour line to the corresponding height; then I filled up the space between the contours with the 3D structure, also based on the elevation drawing.

During the modelling of the tower I applied of course simplifications: I modelled only the geometrical forms of the intricate stone carvings (finials, foliage), just like in Matthäus Roriczer's contemporary book on construction a pinnacle [@roriczer_buchlein_1999]; and I did not display any tracery.

I have modelled the construction in five main stages. In the first stage the lower, quadratic levels of the tower are ready; in the second stage the belfry is under construction; the third displays the building of the octagon, the fourth the building of the openwork spire, and the last one displays the placement of the top finial.

For each phase, at first I modelled the tower to the desired height, using the mediaeval drawings (floor plan, elevation); then I designed a possible solution for the scaffolding, based on the discussed sources; finally I put Hans Hammer’s machines to the appropriate places.

![The five main phases](arnyekolt_egyben.jpg)

# The online representation

In my thesis I illustrate the construction with five phases. Consequently, the on-line presentation consists of five subpages. 

The structure of the pages is the following:

- a short animation about the discussed phase
- embedded models
    - the whole structure (building, machinery, scaffoldings)
    - separate windows for each machine used in this phase
- the sources of archive drawings and plans used (in the case of the online available drawings with link )
- references

The main content of each site is the embedded WebGL-window with the model of that phase.

Discussing the technical implementation the following aspects were important for me: the plugin-free operation; the possibility of simple, offline editing; and version tracking. Accordingly, the embedded models use WebGL, the site is written in Markdown using a simple text editor, and is hosted on GitHub Pages.

WebGL is developed by the Khronos Group. According to the official definition, "WebGL is a cross-platform, royalty-free web standard for a low-level 3D graphics API based on OpenGL ES, exposed to ECMAScript via the HTML5 Canvas element.” [@Khronos_2018_webgl] According to the Wikipedia, "WebGL evolved out of the Canvas 3D experiments started by Vladimir Vukićević at Mozilla. Vukićević first demonstrated a Canvas 3D prototype in 2006. […]
In early 2009, the non-profit technology consortium Khronos Group started the WebGL Working Group, with initial participation from Apple, Google, Mozilla, Opera, and others. Version 1.0 of the WebGL specification was released March 2011." [@wikipedia-WebGL] It is supported by the modern web browsers (such as Apple Safari, Google Chrome, Mozilla Firefox, Opera) without installing plug-ins, just like the most popular mobile browsers (Safari, Chrome, Firefox). The Khronos Group also runs a simple test page where it's easy to check if a browser is WebGL-compatible: https://get.webgl.org. If so, a rotating cube can be seen.

To export the Rhino model to WebGL, I used the Iris plugin for Rhino developed by Luis E. Fraguada. The plugin generates JSON data from a Rhino model that is parseable and viewable through WebGL in a modern web browser. [@iris-web] JSON is an open-source format derived from JavaScript. [@json-web] Iris depends on the following libraries:

- Three.js
- Bootstrap
- Tween.js
- jQuery
- JSON.net

Iris is able to export a so-called Web Archive from the model, which is a local folder with the following content:

- Archive (Named during export)
    - index.html (the html page for the Iris Scene)
    - app
        - iris.min.js (the Iris WebApp Javascript Code)
    - data
        - data.json (the exported model in Three.js json format)
    - ui (this is the default UI template that ships with Iris)
        - css
            - styles.min.css (the css required by the ui)
    - js
        - ui.min.js (the javascript required for the ui)

Embedding the index.html into a webpage using iframe results a 3D window, containing a User Interface (UI) in the corner with a number of buttons. The model loads from the *data* folder, and the UI is loaded from the *ui* and *js* folders.

The version number of the plugin is currently 0.6.0.2, so its operation is not perfect. The UI can not be edited, so it contains a number of (for me) unnecessary items (for example Planes, Materials, or Positions). To avoid the visitors to lose focus I have included a small manual next to the main 3D window discussing most important UI elements. These are the following:

- Zoom Extents
- Views, including the pre-saved views I consider important

The most important shortcuts for navigation are also included:

- Left mouse button: pan around the scene
- Right mouse button: orbits the scene camera
- Middle mouse wheel: zooms
- Zooming extents - ‘z’
- Zooming selected - ‘s’

The custom views displayed in the 'Views' menu can be defined in Rhinocheros itself, using the NamedView command. For each of my embedded models I defined views that point to some important detail. The Iris UI displays the standard views too (Top, Left, etc.).

I used Jekyll and Github Pages to create the online site. The main workflow of this technique is the following. At first, the content of the entire website is created on the local computer with a plain text editor, using Markdown. According to its official website, "Markdown is a text-to-HTML conversion tool for web writers." [@markdown-web] By now, Markdown is much more than this: it has become a de-facto standard, and the documents written in Markdown can be exported to almost any text format with the open source application called Pandoc. [@pandoc-web] Pandoc is developed by John MacFarlane, Professor of Philosophy at the University of California, Berkeley.

The site created in Markdown is translated into html by Jekyll, an open-source server-side application. [@jekyll-web] The result is a lightweight static website that does not require any database. For Jekyll to be able to do its job, the page structure and the markdown files themselves has to be created according to the Jekyll conventions (that means the proper folder system, the corresponding filenames, and the creation of the corresponding YAML headers for each markdown file).

Besides the simple, local editing and the static website generation Jekyll has another important advantage: it is used by GitHub Pages, the web hosting solution of GitHub. The workflow of the online publication is the following. At first, a local Git repository has to be created with the content of the local files of the website. Git is an open source, de-facto standard version control system, and it can be installed on every major desktop operating system. When the local edits are finished, the changes have to be committed to the local Git repository, then synced to the respective online GitHub repository. When the appropriate switch is turned on in the repository's settings on the online GitHub interface, the website is generated by Jekyll running on the GitHub server. The site will be edited and updated still locally: the Markdown files and the folder structure can be edited on the local computer, and when the edits are done, the repository has to be again synced to GitHub where Jekyll monitors the changes and generates the updated static website. This way the version controlling occurs almost unnoticed, because Git (and GitHub) is basically a version-controlling system. Actually, each synchronisation is a commit to the main online repository. 

The resulting website is a detailed online interpretation of the 3D model, where the intricate spatial structure can be observed interactively, in detail.

Here is the URL of the website:

[https://zbereczki.github.io/gothic-construction/](https://zbereczki.github.io/gothic-construction/),

and the URL of the underlying GitHub repository:

[https://github.com/zBereczki/gothic-construction](https://github.com/zBereczki/gothic-construction)

# Conclusions

The modelling based on contemporary sources has shown that with the exceptions of some contradictions and hidden parts, the contemporary plans of the north tower in Vienna carried enough information to build up the structure in 3D. Around and inside the 3D-model, based on historic representations and survived structures I could construct a scaffolding the way it would be constructible using technology available in the Middle Ages. With this scaffolding the construction of the tower would be possible. By placing Hans Hammer’s machines, as well as the clever ladders of the portfolio on the model I was able to clarify their possible application modes.

The mediæval drawings used for the project are definitely workshop drawings, „blueprints”: relying on them and only them it was possible to build up in 3D both the complex building, both the elaborate machines. For the presentation the Web as a medium was much more appropriate than printing. In the printed version of my dissertation I could only include images in a limited number and size, and they (obviously) depict the model only from a certain angle, in a certain size. The web representation, on the other hand, can be rotated and zoomed; and I could define the important views with the Rhino and display them with the Iris UI.

For the whole picture it has to be mentioned, that the technology does not work smoothly yet. On one hand there are errors in the operation of Iris. Probably the most annoying is that it often does not load the predefined view, so either an empty window is displayed, or only a part of the model is visible. So I had to include on every page the warning "if the models are not visible or not centered, press *Z*". In addition, the complete, very complex model requires powerful hardware to render. I can not tell the exact hardware requirements, just the results of some testing. A 2017 MacBook Pro (Intel Iris Plus Graphics 640 1536 MB) was able to render the site without any problem. A much older and weaker 2013 Macbook Air (Intel HD Graphics 5000 1536 MB) could also do the job. I did some mobile testing also, with worse results. The iPhone SE was the most powerful phone available for testing, but it could only display the models of the machines, not the tower model.

# References
