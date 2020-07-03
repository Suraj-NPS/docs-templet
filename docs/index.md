# Documentation Templet

The documents prepared in ```.md``` files are very convenient to convert to a documentation website. 

#### Get GitHub account: 
Before transforming the documents to a website, we need to have a GitHub account with ```user``` and ```password```. 

#### Get landing page: 
the basic requirement is creation of a GitHub repo with name ```user.github.io```. This repo includes your landing page contents, basically navigation to projects and introductory ideas.

#### Get docs repo: 
Create a repo named ```docs-test```. This repo includes documentation resources and codes for ``mkdocs``.

#### Get documents: 
Download [this document](https://github.com/npshub/docs-templet), extract and push/upload to your repo ```docs-test```. This one is for learning purpose only. You can edit/modify the contents for your convenience.


#### Create docs website:
This docs can be hosted in the Github with following steps

- Upgrade ```pip``` if this is old version.
```
pip install --upgrade pip
```
- Install ```mkdocs``` to current environment.
```
pip install mkdocs
```
- Install ```mkdocs-theme```. 
```
pip install mkdocs-rtd-dropdown
```
-  Navigate to working directory.
```
mkdocs new my-project
cd my-project
```
-  Serve the mkdocs website in local server (```localhost:8000```)
```
mkdocs serve
```
- GitHub deployment at (www.user.github.io/docs-test)
```
mkdocs gh-deploy
```