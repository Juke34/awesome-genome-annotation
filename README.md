[![CC BY 4.0][cc-by-shield]][cc-by]


# Awesome genome annotation
---------------------------

A curated list of awesome genome annotation tools.
Available here [https://juke34.github.io/awesome-genome-annotation/](https://juke34.github.io/awesome-genome-annotation/)

## Table of Contents

   * [Foreword](#foreword)
   * [Project layout](#project-layout)
   * [For collaborators teachers and developers](#for-collaborators-teachers-and-developers)     
     * [Modify content](#modify-content)   
     * [MkDocs](#mkdocs)
        * [Welcome to MkDocs](#welcome-to-mkdocs)
        * [Installation](#installation)
          * [Manual](#manual)
          * [Conda](#conda)
        * [Testing and building the website](#testing-and-building-the-website)

## Foreword

You can find here the list of genome annotation tools I have gathered during my bioinformatician life.
The data are located into docs/ and the static website made from this repo lives [https://juke34.github.io/awesome-genome-annotation/](https://juke34.github.io/awesome-genome-annotation/).



## Project layout

```
    README.md               # General readme 
    mkdocs.yml              # The configuration file for the site rendering.
    conda_env.yml           # Conda env to build and test the site locally
    docs/                   # material that will be publish with the static web site
        Readme.md            # The documentation homepage (Website Home page).
        pages/              # Folder dedicated to a topic 
            images/         # Folder containing images related to the topic
            xxx/            # Folder containing the .md files related to the topic topic
            ...    
    Images                  # Images used in the README
```  

## For collaborators teachers and developers

This part is for collaborators-teachers and developers.

### Modify content

When you are in the repository, add and/or modify your markdown tutorials in the docs directory.
The arborescence of the website menu is to setup in the `mkdocs.yml` file

### Mkdocs

#### Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).  
For full documentation about the [material mkdocs theme](https://squidfunk.github.io/mkdocs-material/).

#### Installation

##### Manual

As prerequisite you need python >=3.8 and pip.  

Install Mkdocs:

`pip install mkdocs`

For the theme:  
`pip install mkdocs-material`

For the extensions:  
`pip install pymdown-extensions`

For the plugins:  
`pip install mkdocs-minify-plugin`  
`pip install mkdocs-macros-plugin`
`pip install mkdocs-embed-external-markdown`

##### Conda

Clone the repository and move in it.  
Then install all dependencies using conda and the `conda_env.yml` shipped with this repo:

```
conda env create -f conda_env.yml
```

Activate the environment and you are good:

```
conda activate education
```

#### Testing and building the website


* `mkdocs serve` - Start the live-reloading docs server, to test the site locally (http://127.0.0.1:8000/).
* `mkdocs gh-deploy` - Deploys the site on github pages.

* `mkdocs build` - Build the documentation site.
* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs -h` - Print help message and exit.

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
