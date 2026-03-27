# Architecture of ID-software

 * [Architecture of ID-software](http://open-eid.github.io)
 * [Domain Controller Configuration](http://open-eid.github.io/domain)

## Editing and building "Architecture of ID-software"

Uses http://www.mkdocs.org/ and https://github.com/mkdocs/mkdocs-bootswatch styles for generating documentation. 

1.  Update source files in ID_software_architecture_files/docs/

2.  Build documentation localy

        cd ID_software_architecture_files
        mkdocs build

## Editing and building "Domain Controller Configuration"

Uses https://jekyllrb.com and https://just-the-docs.com styles for generating documentation. 

1.  Update source files in domain/

2.  Build pdf document

```bash
# Export English version
pandoc index.md -L kramdown-toc.lua -o eID_Auth_Guide_EN.pdf

# Export Estonian version
pandoc index.et.md -L kramdown-toc.lua -o eID_Auth_Guide_ET.pdf
```


## Support
Official builds are provided through official distribution point [id.ee](https://www.id.ee/en/article/install-id-software/). If you want support, you need to be using official builds. Contact our support via www.id.ee for assistance.

Source code is provided on "as is" terms with no warranty (see license for more information). Do not file Github issues with generic support requests.
