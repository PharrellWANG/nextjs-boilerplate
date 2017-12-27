# Nextjs Boilerplate

## features
1. [material-ui-next](https://material-ui-next.com/)
2. [gh-pages](https://pages.github.com/)

## how to dev

Install dependencies: ``npm install`` or ``yarn``

Start the development environment: ``npm run dev`` or ``yarn dev``


## how to deploy to GitHub pages

1. ``npm install`` or ``yarn``
2. ``npm run dev`` or ``yarn dev``
3. Deploy it to github
Edit ```env-config.js``` and replace ```'nextjs-boilerplate'``` by your project name.
Edit ```next.config.js``` and replace ```'nextjs-boilerplate'``` by your project name.
4. Create repository.
5. Link it to your github account.
6. add your project name at the front of the public path to static images/favicon
7. Publish your master branch ``npm run deploy`` or ``yarn run deploy``

View it to verify whether the deployment is successfull or not:

Replace 'github-user-name' and 'github-project-name'
<https://github-user-name.github.io/github-projet-name/>

Example:
<https://pharrellwang.github.io/nextjs-boilerplate/>

Extra: create a shorten link using *git.io*
```bash
curl -i https://git.io -F "url=https://pharrellwang.github.io/nextjs-boilerplate/" -F "code=pha-next"
```
Visit: <https://git.io/vbdew>

Note: I have specified nothing when creating the git.io link initially, 
hence I got a random name of ``vbdew``. If you specify your
customized name at beginning, you will be able to make it fancier! 


## The idea behind the example
*todo*

## References

1. [Nextjs with material-ui-next](https://github.com/zeit/next.js/tree/canary/examples/with-material-ui-next)
2. [Deploy nextjs to gh-pages](https://github.com/thierryc/Next-gh-page-example/)


