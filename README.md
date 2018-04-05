# Rmarkdawg

A template for adding a University of Washington bootstrap header to an Rmarkdown file. In order to use this header you need to place the assets folder in the same location as the Rmarkdown file and and add the following to the header of your Rmarkdown code.

```
---
output:
    html_document:
        includes:
            in_header: assets/huskyheader.html
            before_body: assets/huskynavbar.html
---
```

The end result is a header that is flexible and even mobile friendly that you can attach to any of your Rmarkdown files. An example to the demo Rmarkdown file is below.

![Demo](/assets/demo.png)
