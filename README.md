# MERRI collaboration website 

 This is the **website** of the MERRI collaboration
 
 <http://merricollaboration.github.io>
 
## How to change stuff
 
Collaborators in the *MERRI Collaboration Github Group* can perform changes, following the steps below:
 
1. Clone the repository (or pull any changes if you already did) and perform your changes in the `.qmd` files. 
    Note that each of our pages (apart from the landing page `index.qmd`) has its own folder. 
    These folders then always have an `index.qmd`` file, see below: 
    
    ```bash   
    .
    ├── index.qmd
    ├── join
    │   └── index.qmd
    ├── current_collaborators
    │   ├── index.qmd
    │   ├── <collaborator>.qmd
    |   └── img/
    |       └── <collaborator>.jpg
    ├── terms_of_reference
    │   └── index.qmd
    ├── _quarto.yml
    ├── styles.css
    ├── docs/
    ├── LICENSE
    ├── MERRI_logo.png
    └── README.md
    ``` 
  
  The `/docs/` folder contains the rendered website.
  
2. This is a quarto website, so make sure you have quarto installed, see [here](https://quarto.org/docs/get-started/).

3. Render the website using ``quarto render`` in the (RStudio) terminal 

4. Push all the changes back to git, including changes in the `.qmd` files, new `.qmd` files and the updated `/docs/` folder.
