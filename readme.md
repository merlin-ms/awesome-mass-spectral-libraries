# Awesome Mass Spectral Libraries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources and tools to use and build mass spectral libraries.


## Contents

- [Specifications](#specifications)
- [Spectral Libraries](#spectral-libraries)
- [Quality Assessment](#spectral-quality-assessment)
- [Library Generation](#spectral-library-generation)
- [Handling of Spectral Libraries](#handling-of-spectral-libraries)
- [Compound Annotation](#compound-annotation)
- [Other Related Resources](#other-related-resources)


## Specifications
- [mzSpecLib](https://github.com/HUPO-PSI/mzSpecLib): MS library format specifications

## Spectral Libraries

### Public (Open)

- [GNPS](https://gnps-external.ucsd.edu/gnpslibrary)
- [MassBankEU](https://massbank.eu/MassBank/), contribute spectra on GitHub
- [MoNA](https://mona.fiehnlab.ucdavis.edu/) (MassBank of North America)

### Commercial

- [NIST](https://chemdata.nist.gov/dokuwiki/doku.php?id=chemdata:start#libraries)
- [mzCloud](https://www.mzcloud.org/): MSn spectral tree library


## Spectral Quality Assessment

- [msPurity](https://pubs.acs.org/doi/10.1021/acs.analchem.6b04358): R, purity score 

## Spectral Library Generation

- [mzmine](https://github.com/mzmine/mzmine/): Java, GUI/CLI, process MS data, ion mobility spectrometry, generate spectral libraries, visualize spectra
- [RMassBank](https://github.com/MassBank/RMassBank) + [scripts](https://github.com/meowcat/RMassBank-scripts/): Generate spectral libraries, requires specific data acquisition method
- [MSMS-Chooser](https://ccms-ucsd.github.io/GNPSDocumentation/msmschooser/) - Automatically select MS/MS from LC standard runs and generate GNPS libraries

## Handling of Spectral Libraries

- [Metabolomics USI resolver](https://metabolomics-usi.gnps2.org/): Web-tool, visualize library spectra and mirror plots

## Compound Annotation

- [FASST / fastMASST](https://fasst.gnps2.org/): Search single spectrum against public libraries or studies 
- [GNPS2](https://gnps2.org/): Web-apps, nextflow workflows, spectral library matching, molecular networking
- [mzmine](https://github.com/mzmine/mzmine/): Spectral library matching, molecular networking, MS2Deepscore (soon)


## Other Related Resources

- [RepoRT](https://github.com/michaelwitting/RepoRT) ([cite](https://www.nature.com/articles/s41592-023-02143-z)): Retention time database

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
