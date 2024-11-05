---
permalink: /
title: "About Me (Updated: 05-Mov-2024)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


My name is Wang Kehan. I obtained my Ph.D. in 2024 from Tsinghua University. Subsequently, I joined *China Telecom* Cloud Co., Ltd. as a senior researcher. During my doctoral studies, I interned at *Huawei* and *Samsung Research China-Beijing (SRC-B)*. My research covers AI for science(Machine Learning Molecular Dynamics, AI for Materials), large language models, and new-generation cloud computing technologies. I have published papers in journals including JPCL.

You can contact me at wangkehan2018@yeah.net.

Education and Employment
======
[07/2024]-[Now], Senior Researcher, China Telecom Cloud Co., Ltd.,Beijing, China

[09/2019]-[06/2024], PhD student (Mechanical Engineering, Ph.D. thesis title: Research on Structural Superlubricity Simulation Based on Machine Learning.), Tsinghua University, Beijing, China

[07/2022]-[04/2023], AI research Intern (SRC-B Best Intern Award), Samsung Research China-Beijing (SRC-B), Beijing, China

[06/2021]-[08/2021], AI Engineering Intern, Huawei, Dongguan, China

[09/2015]-[07/2019], Bachelor’s degree (Material Physics), University of Science and Technology Beijing, Beijing, China



Research Interests
======

More introductions to my current and previous research projects can be found in papers.

Following are some related keywords often appeared in my papers:

Computational Chemistry: quantum chemistry, MD simulation, multi-scale calculation, DFT…

AI for Science: machine learning potentials, generative AI for molecular generation, Large Language Models …
Materials: battery, OLED, semiconductors, capacitor, aluminum foil, fluorine chemicals…

Tribology:Friction, Wear, Lubrication,...

New-generation cloud computing technologies: Large language model, log analysis, software engineering,...

I am committed to applying various intelligent technologies to a wide range of fields, including natural sciences, software engineering, and new-generation cloud computing technologies. While pursuing accuracy, a good computational method should provide new physical insights for key issues and guide product design.

I am particularly interested in the following topics:

1.AI4S
======

My interests in AI4S include machine learning potential , automatic differentiation algorithms, deep generative models, graph theory, and their applications into interface modelling, enhanced sampling method, force field optimization, molecular generation, material property prediction and chemical reaction networks, etc.



Particularly, I developed a method with my co-workers to use multi-fidelity training data of JAX-ReaxFF—an automatic differentiation method to parameterize ReaxFF and DFT to reduce the computational costs in training SchNet and MACE based machine learning potentials. The method was employed to study a diverse range of properties of 2D semiconductor materials, see 2024 JPCL: https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.3c03080.


2.Tribology
======

I formally published a paper in the journal Frontiers in Chemistry titled "Negative or positive? Loading area dependent correlation between friction and normal load in structural superlubricity." In this study, we discovered a counterintuitive phenomenon: as pressure increases, friction actually decreases. We conducted MD simulations with data analysis and statistical analysis on morphological and energetic data, built models, effectively predicted frictional forces, and proposed effective methods for reducing friction.


3.New-generation cloud computing technologies

In the field of cloud computing, the automated analysis of log data is crucial for operations and maintenance teams. This study introduces LLMDPP, a novel log parser that leverages Large Language Models (LLMs) and Determinantal Point Process (DPP) sampling techniques to enhance the efficiency and accuracy of online log parsing. LLMDPP transforms raw log messages into structured log templates through fewshot learning, thereby simplifying the processing and analysis of log data.The study explores the accuracy of LLMDPP in log parsing tasks and compares the effectiveness of different encoding functions (TF-IDF and Flan-T5-small embedding layer) in DPP sampling. Experimental results show that LLMDPP outperforms traditional methods in both Global Accuracy (GA) and Parsing Accuracy (PA), with the semantic information encoding function performing better when the number of samples is low. Furthermore, we simulated an online scenario to evaluate the parsing effectiveness of different sampling methods on unseen
log datasets. The results indicate that the DPP sampling method has an advantage in maintaining sample diversity and fairness, which can improve parsing accuracy.

![image](https://github.com/user-attachments/assets/67172333-293d-4037-a5f0-bf6e6c40895e)



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
