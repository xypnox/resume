# Resume

This Resume was borrowed and modified from themes available at Overleaf.

I do not use the online overleaf editor and prefer touse VS Code to edit the resume. However, This should work just fine in Overleaf too.

## Build Instructions

1. Install `texlive-full` package on Ubuntu.
2. Install the `latex-workshop` package for VS Code.

Add in the settings (if not already):

```json
"latex-workshop.latex.recipes": [{
    "name": "xelatex",
    "tools": [
        "xelatex"
    ]
}],
"latex-workshop.latex.tools": [{
    "name": "xelatex",
    "command": "xelatex",
    "args": [
        "-interaction=nonstopmode",
        "-file-line-error",
        "%DOC%.tex"
    ],
    "env": {}
}],
"latex-workshop.view.pdf.viewer": "tab"
```

## Aditya Vikram Singh
[xypnox.com](https://www.xypnox.com)

SDS-340, MMM Hall of
Residence, IIT Kharagpur, WB,
India - 721302

## Education

### M.Sc. (5 year) in Physics
*2017-2022 (Expected)*
Indian Institute of Technology, Kharagpur