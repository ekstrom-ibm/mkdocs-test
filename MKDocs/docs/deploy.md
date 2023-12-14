# Deploy to IBM Cloud

This part of the contribution is performed by the Maximo Labs admin team once they have accepted the Pull Request and merged it into the default branch.</br>

Build and test the site locally using the default branch:

    git pull
    cd MKDocs
    mkdocs serve
 
Deploy the site to the github pages:
 
    mkdocs gh-deploy

Go to Actions and wait for the pages-build-deployment to be succesfully completed.</br>
Then take a look at the deployed site.