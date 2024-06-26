
# <span style="color:orange ">My analysis of the Palmer Penguins Dataset, as an assessment for Module: Principles of Data Analytics, 2024, Higher Diploma in Science, Data Analytics <span>

## *Author: Laura Lyons*

***

This README file was written using the [GitHub's documentation on READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) as a guidance document
***

  &#x26a0;&#xfe0f;<span style="color:orange "> **DISCLAIMER** <span>

  Microsoft Co-Pilot was used to generate ideas of the content of the following notebook. That said, the notebook is mainly my own work, as i had to re-work the code the text in generated to meet my own needs.(*The warning icon was sourced from [Stackoverflow](https://stackoverflow.com/questions/50544499/how-to-make-a-styled-markdown-admonition-box-in-a-github-gist)*)

## <span style="color:orange ">**Table of contents** <span>

1. [Introduction.](#introduction).
1. [The purpose of this project.](#the-purpose-of-this-project)
1. [How to get started.](#how-to-get-started)
1. [How to get help.](#5-how-to-get-help)
1. [How to contribute.](#6-how-to-contribute)

## <span style="color:orange ">1. Introduction <span>

This project is was created to fufill an assessment requirement of the Principles of Data Analytics, as part of the H.Dip in Science in Data Analytics.

The aim of this project is to demonstrate the knowledge to both research and analyis the famous [Palmer Penguins Data Set](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv), using both instruction provided in the lectures, data analysis complete by previous analyists and also based on my own research.

The core componments of this assessment is to:

1. Create a GitHub repository with a README.md and a .gitignore. Add a Jupyter notebook called penguins.ipynb and add a title to it.
1. Find the palmerpenguins data set online and load it into your Jupyter notebook. In your notebook, give an overview of the data set and the variables it contains.
1. Suggest the types of variables that should be used to model the variables in the data set in Python, explaining your rationale.
1. Create a bar chart of an appropriate variable in the data set. Then create a histogram of an appropriate variable in the data set.
1. Project: Select two variables from the data set and provide an analysis of how correlated they are.

## <span style="color:orange ">2. The purpose of this project <span>

As noted on the [assignment instructions](https://ianmcloughlin.github.io/2324_principles_of_data_analytics/),

The purpose of the assessment is to ensure students can demonstrate the following:

1. Source and investigate sets of data.
1. Programmatically explore and visualize data.
1. Apply basic mathematical data analysis techniques to data sets.
1. Model real-world problems for analysis by computer.
Provide evidence in a decision-making process using a data set.
Appreciate the limitations of graphical representations in data intensive workflows.

## <span style="color:orange ">3. How to get started <span>

<span style="color:orange "> Necessary software <span>

In order to run the included files, you will need to ensure that you have access to the correct softwear. I would recommend downloading the following applications (ensuring sufficent space on your hard drive prior to installation):

1. [Anaconda](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf) (if Anaconda is too large, miniconda would also suffice).
2. [Visual Studio Code](https://code.visualstudio.com/Download) (this is a code editor).

If installing packages is not an option, you can use the following clickable 'badge', generated in [openincolab.com](https://openincolab.com/) to access the Juypter notebook 'penguins.ipynb', associated with the project.
<a target="_blank" href="https://colab.research.google.com/github/Laura6826/PofDA-mywork/blob/d15060d2db8740b10fe977c72a09c26edc6bd071/penguins.ipynb">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

<span style="color:orange "> Recommended libraries <span>

For a seamless excutition, I would also recommend you have access to the below libraries prior to running the files:

```
  import pandas as pd
  import numpy as np
  import matplotlib.pyplot as plt
  import seaborn as sns
  import scipy
```

<span style="color:orange "> Additions to *.gitignore*<span>

A number of [additional files](https://github.com/github/gitignore/tree/main/Global) were added to my .gitignore prior to running the programmes:

  1. python.gitignore
  2. macOS..gitignore
  3. VisualStudioCode.gitignore
  4. Linux.gitignore
  5. TeX.gitignore
  6. Vim.gitignore

## <span style="color:orange "> 5. How to get help <span>

I have attached below,a number of helpful links, should you wish to extrapolate on any of the methods used within this project.

1. [Anaconda](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf)
1. [Visual Studio Code](https://code.visualstudio.com/Download)
1. [w3schools](https://www.w3schools.com/)
1. [Pandas](https://pandas.pydata.org/)
1. [Numpy](https://numpy.org/)
1. [Matplotlib.py](https://matplotlib.org/)
1. [Seaborn](https://seaborn.pydata.org/)

Additionally, a number of links are embedded within the code, in areas that i found confussing/difficult, that should help should there be any difficulty.

## <span style="color:orange "> 6. How to contribute <span>

As this project was created to fufill an assessment requirement of the Principles of Data Analytics, as part of the H.Dip in Science in Data Analytics, no contributions will be allowed, in order to comply with ATU Policy on [Plagiarism](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf) and the [Student Code of Conduct](https://www.atu.ie/sites/default/files/2022-08/Student%20Code_Final_August_2022.pdf).

Should you find any errors or have any recommendations , please submit a pull reuqest on GITHUB. or just wish to contact that author, you can do so at <maxwell6826@gmail.com>.

***

### <span style="color:orange"> End
