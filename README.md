# compbio-notes
Stephen Ramsey's notes on bioinformatics, computational biology, and scientific computing

# PubMed

## Want to find a PubMed article containing two genes?  Use GeneView:

    http://bc3.informatik.hu-berlin.de/

# Ggplot2

## Separately ordering plots in `facet_wrap` bar charts:

See this R script:
https://github.com/dgrtwo/drlib/blob/master/R/reorder_within.R

# Emacs

## Git push from emacs:

In Emacs 24:

    M-& git push origin master
    

# LaTeX/BibTeX

To get a BibTeX entry given an article's DOI: (From Daniel Himmelstein)

    curl --location --header "Accept: application/x-bibtex" https://doi.org/10.7717/peerj.705
    
# bash

Here is a useful bash shell script template (from Michael Hoffman):

```
#!/usr/bin/env bash

## script.sh: <short description here>

## Copyright 2019 Michael M. Hoffman <michael.hoffman@utoronto.ca>

set -o nounset -o pipefail -o errexit

if [[ $# != 0 || "${1:-}" == "--help" || "${1:-}" == "-h" ]]; then
    echo usage: "$0"
    exit 2
fi
```

