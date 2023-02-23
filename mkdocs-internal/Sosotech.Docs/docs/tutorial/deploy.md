# Deploy
> Build and deploy to a remote public site


See [Deploying Your Docs](https://www.mkdocs.org/user-guide/deploying-your-docs/) on the Mkdocs site for more details.


## GitHub Pages
> How to deploy your docs site to GitHub Pages.

Follow one of the approaches below:

- [Run deploy command](#run-deploy-command) - Run a MkDocs CLI command locally to deploy.
- [Deploy with GitHub Actions](#deploy-with-github-actions) - Use the project's CI workflow in the cloud to build and deploy to GH Pages on commits pushed to master.

Then go to your repo's _Settings_ and _Pages_ then enable _GitHub Pages_ on the `gh-pages` branch's root.

_Note this is for a Project Page on a subpath, you will have to make adjustments to the command below if you want an Organization or User Page on the root path._

### Run deploy command
> Run a MkDocs CLI command locally to deploy

MkDocs needs to know where to publish commits on GitHub - so make sure you are working with a repo that you cloned, or that you initialize the local repo and add a `remote` repo.

