## Welcome to Taxonomy of Deployment Patterns

This is a simple repository to explain what Air-Gapped and Proxy means in the realworld. 


* direct connected
* nat'ed
* private nat'ed
* proxy
* disconnected
* air-gapped
* Sneakernet

### Building the document

```
podman run -it -v .:/documents/ asciidoctor/docker-asciidoctor
bash-5.0# asciidoctor-pdf taxonomy.adoc
```

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
