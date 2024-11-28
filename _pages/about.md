---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received the B.E. degree in information and computing science and the M.E. degree in operational research and cybernetics from Lanzhou Jiaotong University, Lanzhou, China, in 2007 and 2010, respectively, and the Ph.D. degree in computer science from Peking University, Beijing, China, in 2015. I’m a Professor at the Institute of Computing Science and Technology, Guangzhou University, Guangzhou, China. My current research interests include theoretical, algorithmic, and applied research on hard problems.

Publications
======
Recent Paper:
1. A dual-mode local search algorithm for solving the minimum dominating set problem. E Zhu, Y Zhang, S Wang, D Strash, C Liu. Knowledge-Based Systems, 2024, 298, 111950
1. Boosting Reinforcement Learning via Hierarchical Game Playing With State Relay. C Liu, J Cong, G Liu, G Jiang, X Xu, E Zhu. IEEE Transactions on Neural Networks and Learning Systems, 2024.
1. Social Behavior Analysis in Exclusive Enterprise Social Networks by FastHAND. Y Yang, F Wang, E Zhu, F Jiang, W Yao. ACM Transactions on Knowledge Discovery from Data, 2024, 18 (6), 1-32
1. PHEE: Identifying influential nodes in social networks with a phased evaluation-enhanced search. E Zhu, H Wang, Y Zhang, K Zhang, C Liu. Neurocomputing, 2024, 572, 127195
1. iLSGRN: inference of large-scale gene regulatory networks based on multi-model fusion.

1. Total domination and open packing in some chemical graphs. Y Gao, E Zhu, Z Shao, I Gutman, A Klobučar. Journal of Mathematical Chemistry, 2018, 56, 1481-1492.
1. On graphs with the maximum edge metric dimension. E Zhu, A Taranenko, Z Shao, J Xu. Discrete Applied Mathematics, 2019, 257, 317-324
1. On dominating sets of maximal outerplanar and planar graphs. Z Li, E Zhu, Z Shao, J Xu. Discrete Applied Mathematics, 2016, 198, 164-169
1. Cross-inhibitor: a time-sensitive molecular circuit based on DNA strand displacement. C Liu, Y Liu, E Zhu, Q Zhang, X Wei, B Wang. Nucleic acids research, 2020, 48 (19), 10691-10701
1. Partition independent set and reduction-based approach for partition coloring problem. E Zhu, F Jiang, C Liu, J Xu. IEEE Transactions on Cybernetics, 2020, 52 (6), 4960-4969


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
