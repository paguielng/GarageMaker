---
permalink: /
title: "A logbook on my work in Electronics"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am [Paguiel Nganji](https://www.linkedin.com/in/paguiel-nganji/), a student passionate about electronics, robotics, and aerospace, currently pursuing a degree in **Electrical Engineering and Industrial Computing**, and I specialize in automation, electronics, and embedded systems. This website is more than just a resume. It is a reflection of my journey and my ambition: to become an engineer. Here, you will find not only my academic background but, more importantly, the practical application of my knowledge through hands-on projects I build in my personal time.

  You will find some of my projects on my [Github profile](https://github.com/paguielng), such as rocket development projects, hardware gadgets, and more. Each project is a step in my journey to master embedded systems and solve real-world engineering challenges.

A resource-driven personal work
======
I believe that the best way to learn is by doing. While my academic studies in Electrical Engineering and Industrial Computing provide me with a strong theoretical foundation, my personal projects are where I truly bring these concepts to life. This hands-on approach allows me to face real-world challenges, debug complex problems, and develop a deep, practical understanding of electronic systems. This portfolio is a living document of that process, showcasing not just the final result, but the journey of learning and iteration behind each creation.

My passion extends beyond simple electronics; I am deeply fascinated by the intersection of hardware and software, especially in high-stakes environments like aerospace. I am driven by the challenge of building systems that are not only functional but also reliable and efficient. Whether it's designing a circuit board, writing firmware for a microcontroller, or developing control logic for a robot, I am committed to precision and quality. I see every line of code and every solder joint as a step toward building the robust technologies of the future. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/paguieng/Myportfolio.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://Myportfolio.github.io/talkmap.html).

To do this, I continuously explore tools and methods that are standard in the industry. I use some popular tools:
- [C/C++](https://isocpp.org/) for performance-critical embedded applications.
- [KiCad](https://www.kicad.org/) for schematizing electronic circuit
- [Git/GitHub](https://github.com/paguielng/) for managing my projects
- [Wokwi](https://wokwi.com/) for online ESP32 simulator
- [MatLab](https://www.mathworks.com/products/matlab.html/) for computing simulations
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](./images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
