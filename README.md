# Catalog Github Pages Example
Example for creating and publishing an instance of Catalog using Github Pages.

## Installation and Configuration
- Create a new Catalog following the [instructions here](https://docs.catalog.style/installation/create-catalog).
- Create a new repository on Github following the [instructions here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository).
- Add your Catalog code to the new repository following the [instructions here](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line).
- Setup [Github Pages](https://pages.github.com/) on the settings page of your Github repo and select master branch /doc folder as the source for your page.

## Building and Publishing
- Build your Catalog using the script `catalog build --public-url=/[your-repo-name]/ --out=docs`.
- Push the code changes to your repo.
- Navigate to https://[your-username].github.io/[your-repo-name]/ to see your new Catalog in full bloom.
