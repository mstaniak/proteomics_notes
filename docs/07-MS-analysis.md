# Analysis of Mass Spectrometry data


## Data Formats 

The output from an MS experiment is a large collection of precurson ion intensities and associated (tandem) mass spectra. 
Data formats in which these outputs are stored can be divided into two main groups: 
  - raw data formats, which are often propriety formats associated with specific MS equipment. Standardized raw data formats such as mzXML or mzDATA were proposed to make data processing easier.
  - processed data formats that store only the most important information - the observed _m/z_ and charge state of precursor ion and most informative _m/z_-intensity pairs for the fragment ions. These formats (associated software is given in parenthesis) include pkl (MassLynx, Micromass), mgf (Mascot generic file), data (Data analysis, Bruker), pkx (VEMS), dta (Xcalibur).

### Raw Data Formats

#### mzXML


#### mzML

TODO: wiecej formatow

### Processed Data Formats

#### pkl Format


#### mgf Format


#### pkx Format


### Data Import


#### R Tools (Bioconductor)


#### Python Tools


## Data Analysis

