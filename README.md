# CADDSeminar_2025

CADD Seminar - Winter semester 2025/26

__Teachers__
* Andrea Volkamer
* Afnan Sultan
* Guillermo Pérez Hernández

## General guidelines for each assignment

  1. Initial session: Intro
  2. Five bi-weekly sessions: Short task presentations (alternating by group), plus lectures about the topic by us.
  3. In between work sessions: Study the task, write your talktorial notebook. Work on theoretical and practical application ‘Talktorials’. The final result should be comparable with [the notebooks from TeachOpenCADD](https://github.com/volkamerlab/teachopencadd). Please push your progress to this repo by **Wednesday 6 pm** the latest, so we have time to check your talktorials until **Friday** mornings.
  4. Presentation session: Both groups present their notebook to the class (Each student has an active part!).

## Course dates

The seminar takes place on **Fridays**, starting at **10:00 am**.

Date   | Course content                                                               |
|-----:|:-----------------------------------------|
31.10. | Introduction and topic assignment
14.11. | Presenting 1st task + lecture + Q&A
28.11. | Presenting 2nd task + lecture + Q&A
12.12. | Presenting 3rd task + lecture + Q&A
09.01. | Presenting 4th task + lecture + Q&A
23.01. | Presenting 5th task + lecture + Q&A
06.02. | Talktorial presentations


## Before you start

Make sure you have conda installed in your OS, see [Miniconda for Python](https://docs.conda.io/en/latest/miniconda.html)

## How to start working

  Clone repo
  
  1. Clone the _volkamerlab/CADDSeminar_2025_ repository
      * using `git clone git@github.com:volkamerlab/CADDSeminar_2025.git`
      * or... git pull on master (to get all updates!
  2. Change into seminar folder: `cd CADDSeminar_2025`
  
  Create enviornment
  
  3. Create enviornment: `conda env create --file environment.yaml`
  4. Activate the environment with `conda activate <my_env>`
  5. You can find a conda cheat sheet [here](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).
  
  Create your own branch
  
  6. Create a new branch called `T[mynb]-[your_initials]-[topic]` (e.g. T01-AV_proteinfolding) using `git checkout -b T[mynb]-[your_initials]-[topic]`
  7. Copy and paste the folder `0[nr]_topicname/` in `notebooks/` and rename it with your own topic number and topic name. This can be done using `cp -r notebooks/0[nr]_topicname notebooks/[mynb]_[mytopicname]` .
  8. Rename the `talktorial_template.ipynb` notebook in your topic folder as `T[mynb]_[mytopicname].ipynb`. This can be done using `mv talktorial_template.ipynb T[mynb]_[mytopicname].ipynb`.
  
  Start your work 
  
  9. Run `jupyter notebook` and open your notebook `T[mynb]_[mytopicname].ipynb` through the web-app
  10. Fill the template with the theory and start working.

## Version control
  1. Save, stage and upload your changes using 
      * `git add <my_file>`, 
      * `git commit -m 'message associated to commit.' ` 
      * and `git push origin T[mynb]-[your_initals]`. 
      * __Be aware of the new files you add!__
  2. You will now be able to create your pull request on GitHub on the `volkamerlab/CADDSeminar_2023` repo. Rename the title of your PR as `T[mynb]-[your_initials]`.

## Useful links & Cheatsheets
* [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
* Pythonic code: [PEP8 style](https://www.python.org/dev/peps/pep-0008/)
* [Numpy docstring](https://numpydoc.readthedocs.io/en/latest/format.html)
* Markdown [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)
* Git [cheatsheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
* [Gitmoji](https://gitmoji.carloscuesta.me/)
