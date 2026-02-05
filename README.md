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
    ├── LICENSE
    ├── MERRI_logo.png
    └── README.md
    ``` 
  
2. This is a quarto website, so make sure you have quarto installed, see [here](https://quarto.org/docs/get-started/).

3. Render the website using ``quarto render`` in the (RStudio) terminal to check whether your changes are correct. 
   This will create or update a local `/docs/` folder with the rendered HTML files -- open the HTML files in your
   browser to check before moving on to step 4.

4. Push your changes or additions back to git. This should only be `.qmd` files and any images you added. 
   The `/docs/` folder is generated automatically and should not be pushed to git (as specified in the .gitignore).
