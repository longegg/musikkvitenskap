# Musikkvitenskap MkDocs

Mitt prosjekt om musikkvitenskap.

## Getting started

- (https://www.mkdocs.org/#installation)

- (https://help.github.com/articles/creating-project-pages-using-the-command-line/)

1. Kjør Git clone (adressen finnes her i github)

2. Installer Python

## Deployment

Bruker Github project pages. Hvis repo skal være privat kan en mulighet være:

1. Lokalt: git push
2. Bitbucket: post-push webhook
3. Webserver: webhook php script
4. Webserver: git post checkout bash hook (mkdocs build + bash copy build folder to web root)

### Linker

- [Bitbucket webhook deploy](https://bitbucket.org/lilliputten/automatic-bitbucket-deploy/)
- [Bitbucket webhook deploy 2](https://www.rarst.net/wordpress/simple-deploy/)