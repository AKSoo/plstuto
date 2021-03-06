# CCA/PLS tutorials in Python
***Tutorials to apply cross decomposition methods in Python (focus on application in neuroimaging)***

Let's chat on <a href="https://mattermost.brainhack.org/brainhack/channels/pls-tuto">
  <img src="http://www.mattermost.org/wp-content/uploads/2016/03/logoHorizontal.png" width=100px>
</a>

## Welcome!

First of all, welcome! If you're here, it's because we probably have one thing in common: you're ~~incredibly smart~~ interested in using cross-decomposition algorithms (e.g. Canonical Correlation Analysis - CCA, Partial Least Square - PLS, etc.).

This project has been proposed during the [OHBM Hackathon 2020](https://ohbm.github.io/hackathon2020/) and should soon gather a set of tutorials to help the application of these methods (especially in neuroscience). 

## Install dependencies
```
pip install -r requirements.txt
```

## What are we doing?

Cross decomposition algorithms look for the relations between two (or more) blocks of variables. These methods are particularly used in neuroimaging to analyze associations between physiological/behavioral variables and brain structure/function.
Between unsupervised and supervised modeling, this family of algorithms has many members (e.g. CCA, PLS regression, PLS canonical, PLS-PM, etc.) and many approaches are possible to validate the trained model (e.g. cross validation, bootstrapping, permutation test, etc.).
In this project, we propose to write several Python tutorials to help the application and interpretation of these models in practice.

## Who are we?

This project brings together a group of collaborators (neuroscientists participating to the 2020 OHBM Hackathon) interested in this issue and you are welcome to join us!

## What do we need?

**You**! As long as you're interested in cross-decomposition algorithms.

We need expertise in Python, tutorial redaction (Jupyter Notebook) and of course cross-decomposition approaches.

## How can you get involved?

In order to help the development of this project, please check out the [contributors' guidelines](CONTRIBUTING.md) and the [roadmap](../../issues/3).

During the OHBM Hackathon 2020, please check the [kanban board](https://github.com/LeonieBorne/plstuto/projects/1) to track the progress of the project.

## Contact us
During the OHBM Hackathon 2020 (June 16 to 18), let's chat on <a href="https://mattermost.brainhack.org/brainhack/channels/pls-tuto">
  <img src="http://www.mattermost.org/wp-content/uploads/2016/03/logoHorizontal.png" width=100px>
</a>

If you want to report a problem or suggest an enhancement we'd love for you to [open an issue](../../issues) at this github repository because then we can get right on it. But you can also contact [Léonie Borne](https://www.newcastle.edu.au/profile/leonie-borne-749) by email (leonie.borne AT gmail DOT com) or on [twitter](https://twitter.com/LeonieBorne).

## Find out more
You might be interested in:

* [Initial project proposition](https://github.com/ohbm/hackathon2020/issues/149)
* [Roadmap](../../issues/3)
* [Contributors' guidelines](CONTRIBUTING.md)
* [Kanban board for OHBM Hackathon 2020](https://github.com/LeonieBorne/plstuto/projects/1)

## Glossary
* **CCA**: Canonical Correlation Analysis
* **PLS**: Partial Least Square
* **PLS-PM**: Partial Least Square Path Modeling
* **PCA**: Principal Component Analysis
* **ICA**: Independent Component Analysis
