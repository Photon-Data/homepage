# Welcome to Photon-HDF5 Project

## Quick-start: View Files

To open and export data from example Photon-HDF5 files install the HDF5 viewer 
[HDFView](https://www.hdfgroup.org/products/java/release/download.html)
and download the [example Photon-HDF5 data files](http://dx.doi.org/10.6084/m9.figshare.1456362).

## Quick-start: Convert Files

To convert files from other formats (PicoQUant PTU, HT3, Beker Hickl SPC, etc.) to 
Photon-HDF5 use [phconvert](http://photon-hdf5.github.io/phconvert/).

## Latest News

*We are currently working on the next Photon-HDF5 version (0.5) which will support 
many more measurement types. This is a good time for proposing new features. 
You are more than welcome to partecipate or follow us using GitHub Issues:*

- [Photon-HDF5 GitHub Issues for 0.5 Milestone](https://github.com/Photon-HDF5/photon-hdf5/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+milestone%3A0.5)

## Description

**Photon-HDF5** is a file format designed to store data from
freely-diffusing single-molecule spectroscopy experiments,
single-molecule FRET (smFRET) (with or without lifetime), 
Fluorescence Correlation Spectroscopy (FCS)
and related photon-counting techniques.

Photon-HDF5 is not limited to fluorescence-based techinues.
Any dataset containing photon timestamps and other per-photon data
can be stored using the Photon-HDF5 format.
Photon-HDF5 can store important experimental details
and metadata (setup configurations, sample information, authorship and provenance)
to make the file suitable for long-term preservation and data sharing.

The Photon-HDF5 format defines a conventional structure in HDF5 files for
a wide variety of timestamp-based spectroscopy data
(single-molecule techniques being the initial focus).
We provide detailed format description, examples to read Photon-HDF5 in
multiple languages and a reference python library to create and convert 
Photon-HDF5 files.

## Project Resources

**Documentation & Papers**

- Photon-HDF5 [Reference Documentation](http://photon-hdf5.readthedocs.io/)
- Photon-HDF5: an open file format for timestamp-based single-molecule fluorescence experiments. 
  [Biophysical Journal 110-1 (2016)](http://dx.doi.org/10.1016/j.bpj.2015.11.013) 
  or [bioRxiv preprint](http://dx.doi.org/10.1101/026484).

**Software**

- [Reading Photon-HDF5 in multiple languages](http://photon-hdf5.github.io/photon_hdf5_reading_examples/)
- [phconvert](http://photon-hdf5.github.io/phconvert/): a library to create and convert Photon-HDF5 files
- [phforge](http://photon-hdf5.github.io/phforge): a script to create Photon-HDF5 files in any language
- [Writing Photon-HDF5 in Python](http://nbviewer.ipython.org/github/Photon-HDF5/phconvert/blob/master/notebooks/Writing%20Photon-HDF5%20files.ipynb)
- [Writing Photon-HDF5 in LabVIEW](https://github.com/Photon-HDF5/photon-hdf5-labview-write)
- [Writing Photon-HDF5 in MATLAB](https://github.com/Photon-HDF5/photon-hdf5-matlab-write)
- [Photon-HDF5 Project on GitHub](https://github.com/Photon-HDF5)

## Contacts and Troubleshooting

For questions about the Photon-HDF5 format please use the [Photon-HDF5 google group](https://groups.google.com/forum/#!forum/photon-hdf5).

For bug reports or enhancements to the supporting software please open a GitHub Issue at the following links:

GitHub issues for phconvert (software to write and convert Photon-HDF5 files).
GitHub issues for code examples on reading Photon-HDF5 files.

## Software supporting Photon-HDF5

Software supporting Photon-HDF5 for reading or writing:

- [FRETBursts](http://fretbursts.readthedocs.io): burst analysis software for diffusion-based smFRET (*read support*).
- [PyBroMo](http://tritemio.github.io/PyBroMo/) confocal smFRET simulator (*write support*).
- [AliX](https://sites.google.com/a/g.ucla.edu/alix/): smFRET analysis and more (*read support*).

If you would like to add other software to this list please [contact us](https://groups.google.com/forum/#!forum/photon-hdf5).

## Acknowledgements

This work was supported by NIH Grant R01-GM95904.
