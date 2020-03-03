# Starting page

## Introduction

REproDucible ComputAtional Research or simply REDCAR is a project initiated by TU Delft [HumTechLab](https://www.tudelft.nl/tbm/over-de-faculteit/afdelingen/multi-actor-systems/research/humtech-lab/humtech-lab/). The goal of the project is to help students and researchers to make their computational results **reproducible**, more easily **understandable**, and **accessible to others**.

![Figure 1. Project idea](.gitbook/assets/project-idea.png)

## Background

Big data, powerful computers, and programming languages such as Python and R brought quantitative research to a whole new level. Now you can apply a machine learning algorithm to train a car or a drone to become automated with 2 lines of code \(proof can be found [here](https://drive.google.com/open?id=13pEtv7Fox14mz7hDAqo5jsq_KI0CjCZE)\).

Along with the opportunities, such a technological leap brought complications. Scientists became overwhelmed with all details that should be taken into account while conducting a computational study. Given the pressure from the deadlines, they are forced to **decide between "quick-and-dirty"** **and reproducible research**, not in favor of the latter. Manual corrections of the raw data, conflicting versions of software packages, lack of instructions on how the code should be executed, making it hard if not impossible to reproduce results of a computational study. As a result, more and more scholars have started to highlight the importance of **reproducibility**, propose ways to achieve it and pose it **as a minimum standard** **for assessing the value of scientific claims** \[[1](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285),[2](https://science.sciencemag.org/content/334/6060/1226)\].

But what do we mean by reproducible? In this project we will use definition introduced in \[[3](https://stm.sciencemag.org/content/8/341/341ps12.short?casa_token=VgB2iSv2JNkAAAAA:nEpwUfQh5c9LtRUjk7k3CNW99XUArjLuFcwBRgdVYUnIWHifsZLnrtxvEfCFcYk4V2yehf7Sg-LC6sA)\]:

> _"The ability to implement, as exactly as possible, the experimental and computational procedures, with the same data and tools, to obtain the same results."_

It means that we won't talk about [_empirical_](https://www.nature.com/news/announcement-reducing-our-irreproducibility-1.12852) or [_statistical_](https://science.sciencemag.org/content/343/6168/229) reproducibility but instead [_computational reproducibility_](https://web.stanford.edu/~vcs/talks/Census2017-STODDEN.pdf) \[[4](https://aip.scitation.org/doi/abs/10.1109/MCSE.2012.82?journalCode=csx)\].

Alright. Now you understand what reproducibility is and what it's important. But what are the ways to ensure it? In short, you need to follow the rules described in \[[1](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)\], and use the tools and practices that were developed for that \(see, e.g., \[[5](https://books.google.nl/books?hl=en&lr=&id=JcmSAwAAQBAJ&oi=fnd&pg=PP1&dq=implementing+reproducible+research&ots=ym1btRtPJE&sig=tR2_-mmsrsZUwXwEHXYIrYz_HT4&redir_esc=y#v=onepage&q=implementing%20reproducible%20research&f=false)\]\). But in the REDCAR project, you'll find a bit more than that.

## REDCAR

With the REDCAR project, we're aimed at achieving more than reproducibility 🧞. We realize how important is the **structure** of the study, **code formatting**, and whether it's **easily accessible** by other researchers or the general public. We translated these additional principles into 2 extra components: **understandable** and **shared** \(see Figure 1\).

We linked all these three components into a system.

## To be prepared

To participate in the workshops you will need a laptop and a couple of tools installed. The preparation process will take less than 30 minutes.

1. Download and install Anaconda Distribution with Python 3.7 from [here](https://www.anaconda.com/distribution/). The process is pretty straightforward: select your operating system, download installer and follow the steps. If you already have it, make sure that it works by running any script in JupyterLab \(that's the IDE that we will work in\). If you prefer to use R programming language - no problem! After installing Anaconda Distribution, open it and install RStudio. To use R in Jupyter Notebook follow [this](https://docs.anaconda.com/anaconda/navigator/tutorials/r-lang/) simple tutorial. 
2. Install Git from [here](https://git-scm.com/downloads). The same principle works here: select your operating system and follow the steps.

That's it! All set now.

## Contributing & authors

We're highly interested in your opinion on the project! To contribute please, either fork it and submit a pull request, or contact us via Twitter or email.

_Mikhail Sirenko_ [@mikhailsirenko](https://twitter.com/mikhailsirenko), _Nicolas Dintzner, Jason Wang_ [@jasonrwang](https://twitter.com/jasonrwang) and _Trivik Verma_ [@TrivikV](https://twitter.com/TrivikV).

## License

[BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

## Acknowledgements

While working on this project the REDCAR project team was inspired by Cookiecutter Data Science \[[4](https://drivendata.github.io/cookiecutter-data-science/)\] made by _friendly folks at DrivenData_ , Reproducible Research module of Data Science Specialization \[[5](https://www.coursera.org/specializations/jhu-data-science)\] by _Jeff Leek_, _Roger D. Peng_ and _Brian Caffo_.

We also would like to thank _Jan Kwakkel_, _Igor Nikolic, Alexander Verbraeck_ and _Bartel Van de Walle_ for their input into the shaping of the project.

## References

1. Sandve GK, Nekrutenko A, Taylor J, Hovig E. Ten simple rules for reproducible computational research. PLoS computational biology. 2013 Oct;9\(10\).
2. Peng RD. Reproducible research in computational science. Science. 2011 Dec 2;334\(6060\):1226-7.
3. Goodman SN, Fanelli D, Ioannidis JP. What does research reproducibility mean?. Science translational medicine. 2016 Jun 1;8\(341\):341ps12-.
4. Stodden V. Reproducible research: Tools and strategies for scientific computing. Computing in Science & Engineering. 2012 Jul;14\(4\):11-2.
5. Stodden V, Leisch F, Peng RD, editors. Implementing reproducible research. CRC Press; 2014 Apr 14.
6. DrivenData. Cookiecutter Data Science. Available from [https://drivendata.github.io/cookiecutter-data-science/](https://drivendata.github.io/cookiecutter-data-science/) \[Accessed 03 March 2020\].
7. Coursera Inc. Data Science Specialization. Available from [https://www.coursera.org/specializations/jhu-data-science](https://www.coursera.org/specializations/jhu-data-science) \[Accessed 03 March 2020\] 

