<!-- TO DO: 
- Continue updating skills and sources as you go along -->

Project: Recipes

This is a basic recipe website containing:
1. Main index page with links to recipes

Skills required (* indicates optional for assignment. Full details at end of page):
1. Basic Git:
    - Create a repository
    - Locate and share SSH key
2. Basic command line to:
    - Create a directory
    - Use Git workflow
        - Clone repository
        - Add file to staging area
        - Commit and add comments
        - Push files to GitHub main branch
        - Check status
        - Check commit history
    - Navigate directories
    - Create a file
    - (*) Open VS Code
3. Basic HTML to:
    - Add boilerplate
    - Add block elements
        - header
        - paragraphs
        - lists
            - unordered
            - ordered
    - Add inline elements:
        - * comments
        - links
            - for relative navigation
            - (*) in new tab
            - (*) with added security & performance
                - (*) for extra privacy
        - images
            - (*) hosted locally in parent directory
            - (*) with alternative text (not listed as requirement for assignment but best practice)
            - (*) with size attributes
        - (*) italics

Assignment (Full instructions: https://www.theodinproject.com/lessons/foundations-recipes)

Iteration 1: initial structure
1. Within the odin-recipes directory, create an index.html file.
2. Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

Iteration 2: recipe page
1. Create a new directory within the odin-recipes directory and name it recipes.
2. Create a new HTML file within the recipes directory and name it after the recipe it will contain. 
3. For now, just include an h1 heading with the recipe’s name as its content.
4. Back in the index.html file, add a link to the recipe page you just created. 
5. Add a link back to the index page on your recipe page for easier navigation. 

Iteration 3: recipe page content

Your new recipe page should have the following content:
1. An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or Allrecipes.
2. Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
3. Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
4. Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: add more recipes
1. Add two more recipes with identical page structures to the recipe page you’ve already created.
2. Don’t forget to link to the new recipes on the index page.

Sources
1. Assignment: https://www.theodinproject.com/lessons/foundations-recipes
2. Chicken wing recipe and images: https://www.allrecipes.com/recipe/230873/amazing-and-easy-chicken-wings/
3. Curry recipe and images: https://www.allrecipes.com/recipe/46822/indian-chicken-curry-ii/
4. Mushroom soup recipe and images: https://www.allrecipes.com/recipe/235589/chef-johns-creamy-mushroom-soup/


Skills required:
1. Basic Git:
    - Create a repository (via Github)
    - Locate and share SSH key (code)
2. Basic command line to:
    - Create a directory (mkdir)
    - Use Git workflow
        - Clone repository (git clone SSH key)
        - Add file to staging area (git add fileName.extension)
            - all files with changes (git add .)
        - Commit and add comments (git commit -m "")
        - Push committed files in staging area to GitHub main branch (git push)
        - Check status (git status)
        - Check commit history (git log)
    - Navigate to directory (cd directoryName)
        - to parent directory (cd ..)
        - to home (cd ~)
    - Create a file (touch Filename.extension)
    - Open in VS Code (code .)
3. Basic HTML to:
    - Add boilerplate (!)
    - Add block elements
        - header (h1)
        - paragraphs (p)
        - lists
            - unordered (ul li)
            - ordered  (ol li)
    - Add inline elements:
        - comments (cmd + /)
        - links (a href="")
            - for relative navigation (../)
            - in new tab (target="_blank")
            - with added security & performance (rel="noopener")
                - for extra privacy ("noreferrer")
        - images (img src="URL")
            - hosted locally in parent directory (../images/imagename.fileextension instead of URL)
            - with alternative text (alt="")
            - with size attributes (height="" width="")
        - italics (i)