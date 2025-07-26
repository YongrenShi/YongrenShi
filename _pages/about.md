---
permalink: /
title: "Welcome to the homepage of Yongren Shi!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I'm an assistant professor in the School of Sociology at the University of Arizona. My principal line of research focuses on the interplay of culture, social groups, and social networks. My research is guided by two central questions: at the macro level, how do social groups develop distinct cultures? And at the individual level, how do people develop and internalize culture and use it to guide their actions? In my research, I use large-scale digital trace data and a range of quantitative and computational methods, including large language models, network analysis, computational textual analysis, agent-based modeling, machine learning, online experiments, and survey analysis.

My work has been supported by multiple research grants from the National Science Foundation (NSF 2048670, 1409593, 1922906, and 2420405), and covered by dozens of popular media outlets including Wired, The Guardian, BBC News, Huffington Post, and LA Times. I received the Outstanding Article Publication Award and Dissertation-in-Progress Award from the Mathematical Sociology Section of the American Sociological Association.

My research has appeared in top sociology and science journals, including American Sociological Review, American Journal of Sociology, Nature Human Behaviour, and Social Forces. My work has been supported by multiple research grants from the National Science Foundation (NSF 2048670, 1409593, 1922906, and 2420405), and covered by dozens of popular media outlets including Wired, The Guardian, BBC News, Huffington Post, and LA Times. I received the Outstanding Article Publication Award and Dissertation-in-Progress Award from the Mathematical Sociology Section of the American Sociological Association.

I received his PhD in sociology from Cornell University. Before joining the school, I worked as a postdoc researcher at Yale Institute for Network Science and an assistant professor at the University of Iowa.

If you’re considering doctoral studies at the University of Arizona or a research collaboration, you're encouraged to get in touch!

Selected Publications
------
Shi, Yongren, Regan Smock and Steve Hitlin. 2025. “Moral Disagreement in Everyday Life: An Inductive, Structural Model of Moral Order” Social Science Research. Volume 127, 103139 https://doi.org/

Shi, Yongren, Kevin Kiley, and Freda B. Lynn. 2025. “Beyond Statistical Variables: Examining the Duality of Persons and Groups in Structuring Opinion Space.” Poetics: Journal of Empirical Research on Culture, the Media and the Arts Volume 108, 101967 https://doi.org/10.1177/23780231241272681

Shi, Yongren, Kevin Kiley, and Stephanie M. DiPietro. 2024. “To the Extreme: A Descriptive Exploration of the Rise of a Radical Culture in a Misogynist Digital Community.” Socius: Sociological Research for a Dynamic World Volume 10: 1-18 https://doi.org/10.1177/23780231241272681

Lynn, Freda B., Yongren Shi, and Kevin Kiley. 2024. “Intersectional Group Agreement on the Occupational Order.” Social Psychology Quarterly Vol. 88(1) 135-148. https://doi.org/10.1177/01902725241256378

Shi, Yongren, Fedor Dokshin, Michael Genkin and Matthew E. Brashears. 2017. “A Member Saved is a Member Earned? The RecruitmentRetention Trade-Off and Organizational Strategies for Membership Growth.”
American Sociological Review 82(2): 407 - 434. https://doi.org/10.1177/0003122417693616

Feng Shi*, Yongren Shi*, Fedor Dokshin, Michael W. Macy and James Evans. 2017. “Millions of Online Book Co-purchases Reveal Partisan
Differences in the Consumption of Science.” Nature Human Behaviour https://doi.org/10.1038/s41562-017-0079 (Cover Article) (* co-first authors with equal contribution).

DellaPosta, Daniel, Yongren Shi and Michael W. Macy. 2015. “Why Do Liberals Drink Lattes?” American Journal of Sociology 120(5):1473-1511. https://doi.org/10.1086/681254

Manuscripts
------
Shi, Yongren, Edo Airoldi, and Nicholas Christakis. Multiplex Networks Provide Structural Pathways for Behavioral Contagion in Rural
Social Networks.

Shi, Yongren and Kevin Kiley. Culture from Conversation: How Conversation Transition Structures Shape Online Communities


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

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
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
