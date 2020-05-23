---
permalink: /
title: "Benjamin Gutierrez: nomad, physicist, data scientist, linux geek"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Brief bio
======

Current: Scientific Computing Engineer at Argonne National Lab. About me
Previous:
 - Data Scientist, TrustScience Inc.
 - Visiting Professor, [ITAM] (http://www.itam.mx), Mexico City.
 - Data scientist, Honeywell, Mexico City.
 - Devops/High Performance Computing specialist at [ANSYS] (http://www.ansys.com), in the outskirts of Pittsburgh, Pennsylvania. worked on the ANSYS Enterprise Cloud project to perform Elastic HPC and data intensive workflows, mostly aimed to leverage ANSYS Engineering Simulation Applications. My skills include linux, machine learning and distributed/parallel computing to data analytics and mathematical modeling. My interests span to distributed file systems, clouds and virtualization.I am passionate about scalable data-intensive techniques to analyze large datasets, such as statistical methods, sampling, statistical inference, etc. I want to apply my experience to cloud computing, fraud detection and big data mining. I am a big fan of the Openstack ecosystem, virtualization technologies and python.

Education
======

I received my B.Sc. in Physics in 2002 from the National University of Mexico (UNAM). I was awarded a Ph.D in Computational Physics at the University of British Columbia, in Vancouver, Canada. My research and skills have benefited from several internships since my undergraduate years (CERN, Summer Program 1996), more recently at the Max-Planck Institute for Gravitational Physics, in Golm, Germany (2008) and The Perimeter Institute for Theoretical Physics (2010) in Waterloo, Canada. Before starting my doctoral studies I worked as a Linux server specialist at my home university's Institute for Mathematical Research, and later at Hewlett Packard Mexico..

After Argonne I collaborated with the Clear Linux Project as a Linux integration and data engineer at Intel's Open Source Technology Center in Guadalajara, Mexico.

Soliton non-linear dynamics my passion
======

My [PhD. research] (http://circle.ubc.ca/handle/2429/44527) project consisted in the study of dynamics of certain type of solutions to the equations of motion of non-linear classical field theories. The scattering of solitons and their time-dependent evolution in a non-integrable classical or quantum field theory remains an intractable and difficult problem. This is where numerical methods offer an effective tool to deal with the complexity of the equations, which require sophisticated algorithms and extensive runtime and storage resources. Independently of their physical applications, the non-linear nature of the solutions provides a rich phenomenology, interesting in its own right.
These problems are expressed as hyperbolic time-dependent non-linear partial differential equations (PDEs) in 2 and 3 spatial dimensions, supplemented by suitable  boundary conditions. To solve them, we apply finite difference techniques and iterative relaxation methods such as Newton-Gauss-Seidel. However, the physical domain spans over several time and space scales. The appropriate optimization of computational resources is achived by means of parallel adaptive mesh refinement (PAMR) techniques. They implement a hierarchy of meshes with different resolutions, concentrating resources on areas with high phenomenology using a modified Berger-Oliger algorithm.

My training in parallel programming and hyperbolic PDEs allowed me to gain experience in another area I find deeply exciting: Computational hydrodinamics. I am interested in problems involving astrophysical (maybe relativistic) fluids, reactive-transport models, Euler equations and shallow water equations to model tsunamis. Some of this equations develop shocks, which require the use of high resolution shock capture methods. I am familiar with some finite-volume techniques coupled to iterative linear solvers and fully implicit schemes. 



This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
