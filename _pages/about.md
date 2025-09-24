---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I’m **Mingda Zhang**, an undergraduate at the **School of Software, Yunnan University** (Sep 2022–Jun 2026). I work on **vision–language models**, **multimodality**, **NLP**, and **computer vision**, aiming to tightly integrate language and visual signals for real-world applications in **medical imaging** and **legal analysis**. 

I’m fortunate to be mentored by **Professor [Jianglong Qin](http://www.sei.ynu.edu.cn/info/1023/1448.htm)** (Software, YNU), **Professor [Qing Xu](http://www.law.ynu.edu.cn/info/1143/3322.htm)** (Law, YNU), and **Professor [Xiaoyang Tan](http://parnec.nuaa.edu.cn/xtan/)** (NUAA), whose guidance has helped me develop a systematic, problem-driven approach to AI research.

🔬 Research Highlights
======
### 🫁 Medical Image Analysis & Segmentation
- Author/co-author on lung disease recognition in collaboration with **Army Medical University (AMU)**.
- Outcomes: **patents** and **peer-reviewed publications**.
- Dataset: **Privately processed dataset with institutional ethics approval** (IRB/ethics cleared; contains sensitive medical data and cannot be released publicly).  
  ➤ Access: available to qualified researchers under a data-use agreement and ethics compliance. *(Contact Me: yao110002@gmail.com)* 

### 🧠 Applications of Large Language Models
- Collaborated with the **President of an Intermediate People’s Court**; our system received **multiple letters of recommendation**.
- Produced related **publications**.
- **Sep 2025**: National Social Science Fund of China (NSSFC) project officially approved —  
  *“An Empirical Study on the Mechanism of Judicial Justice in the Digital-Intelligence Era under Socialism with Chinese Characteristics.”*  
  Role: **key contributor**.

### ⭐ GitHub — 160★ Project
Efficient fine-tuning of LLMs for the **medical vertical**.
 
[![GitHub Stars](https://img.shields.io/github/stars/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical-Fine-tune?style=social)](https://github.com/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical-Fine-tune)
[![Repo](https://img.shields.io/badge/Repo-DeepSeek--R1--Distill--Qwen--32B--Medical--Fine--tune-black)](https://github.com/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical-Fine-tune)


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
