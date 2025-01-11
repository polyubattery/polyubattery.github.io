---
permalink: /
title: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I currently serve as a Research Assistant Professor at the [Research Centre for Grid Modernisation (RCGM)] (https://www.polyu.edu.hk/rcgm/) within the Department of Electrical and Electronic Engineering at The Hong Kong Polytechnic University. 
I lead a group specialising in the modelling, management, and control of energy storage systems, with a particular emphasis on rechargeable batteries.

I earned my Ph.D. degrees in Mechanical Engineering in 2021 and Electrical Engineering in 2022 from the Beijing Institute of Technology, China, and Swinburne University of Technology, Australia, respectively, under the supervision of Professor Rui Xiong and Professor Weixiang Shen. From 2023 to 2024, I worked as a postdoctoral research fellow at The Hong Kong Polytechnic University (PolyU), Hong Kong. I previously held the role of Teli Postdoctoral Fellow at the Beijing Institute of Technology, China, from 2021 to 2023.

I has published over 30 papers as either the first or corresponding author in top-tier journals, including Joule and Nature Communications. My publications have been cited over 4500 times, including 10 ESI highly cited papers. I has been the PI of three research projects funded by government agencies and a collaborator on another three projects. I was ranked among the "World's Top 2% of Scientists" by Stanford University and Elsevier. I also received the “Fellowship of China National Postdoctoral Program for Innovative Talents” from the China Postdoctoral Science Foundation and the "Outstanding Doctoral Thesis Award" from the China Electrotechnical Society.


News
======
+ **We are actively seeking talented and self-motivated students, postdoctoral researchers and visiting scholars, who have a keen interest in energy storage research. If you are passionate about this field and wish to join our team, please do not hesitate to reach out to me or Professor C. Y. Chung.**

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.
