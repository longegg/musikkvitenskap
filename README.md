# Musikkvitenskap MkDocs

Mitt prosjekt om musikkvitenskap.

## Deployment

Her kommer det mer info om dette. Tanken er:

1. Lokalt: git push
2. Bitbucket: post-push webhook
3. Webserver: webhook php script
4. Webserver: git post checkout bash hook (mkdocs build + bash copy build folder to web root)

### Linker

- [Bitbucket webhook deploy](https://bitbucket.org/lilliputten/automatic-bitbucket-deploy/)
- [Bitbucket webhook deploy 2](https://www.rarst.net/wordpress/simple-deploy/)