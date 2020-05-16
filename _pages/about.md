---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I'm a first-year Ph.D. student of  Computer Science and Engineering at Michigan State University (MSU), supervised by Dr. [Jiliang Tang](http://www.cse.msu.edu/~tangjili/). I completed my B.E. degree in Electrical Engineering at Zhejiang University. 

My interest lies in Graph Representation Learning and now I work on the area of graph neural network including its theory foundations, model robustness and applications. 

Previously, I worked as an intern at Hangzhou Xiaoyu Co. Ltd, developing user and microblog recommender systems, and worked as a research intern at University of Western Australia supervised by Dr. [Wei Liu](https://scholar.google.com/citations?user=o_u17HMAAAAJ&hl=en). I also worked as a research assistant with Dr. [Donghui Wang](https://scholar.google.com/citations?user=AkRWtMUAAAAJ&hl=en) (ZJU) in 2018.

Email: joe.weijin At gmail Dot com. Find me on [github](https://github.com/ChandlerBang), [Linkedin](https://www.linkedin.com/in/wei-jin-71041a182/).

<!--
-----
Research Interest
=====
*
-->

News
=====
* [05/2020] Our paper “Graph Structure Learning for Robust Graph Neural Networks” is accepted by KDD2020
* [05/2020] Our tutorial  “Adversarial Attacks and Defenses: Frontiers, Advances and Practice” is accepted by KDD2020
* [05/2020] Preprint ["DeepRobust: A PyTorch Library for Adversarial Attacks and Defenses"](https://arxiv.org/abs/2005.06149)
* [03/2020] Preprint ["Adversarial Attacks and Defenses on Graphs: A Review and Empirical Study"](https://arxiv.org/abs/2003.00653)
* [02/2020] Check our repository [DeepRobust](https://github.com/DSE-MSU/DeepRobust) here, which is a pytorch library for adversarial attacks and defenses on images and graphs
* [02/2020] Honored to present our tutorial in AAAI 2020 [[website]](http://cse.msu.edu/~mayao4/tutorials/aaai2020/)
* [09/2019] Our tutorial  “Graph Neural Networks: Models and Applications” is accepted by AAAI2020
* [08/2019] Start my Ph.D. life at Michigan State University!
* [07/2019] Graduate from Zhejiang University with the awards of Outstanding Graduate of ZJU and Zhejiang Province, China

Personal
====
I enjoy many different kinds of sports including running, basketball, ping-pong and tennis. During my undergrad, I got several champions in 400m, 400m hurdles and 4*400m relay races at the university sports meet. 

Now my goal is to bulk up ~~and hopefully get a certificate of personal trainer~~. Let's see what will happen 5 years later :)

<!---
Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**


I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
