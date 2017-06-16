# pymidifile

This repository combines various available and stable resources to provide a pythonic framework for music analysis and manipulation of midi files. It is conceptually inspired in the MATLAB *miditoolbox* by Tuomas Eerola and Petri Toiviainen (https://github.com/miditoolbox), although the various conversions, filters and descriptors implemented are guided by my own research on tonality in Electronic Dance Music.

*Pymidifile* is a conveniency repository aiming at bridging already existing and widely tested tools such as the data analysis library *Pandas* or the *music21* toolkit for computer-aided musicology, adapting, combining and extending the capacities of these powerful projects to my research needs.

The *Pymidifile* functions can be grouped into three categories: 

1) **Conversion**: midi files to and from python lists, pandas Dataframes and/or music21 scores, in all combinations.
2) **Tranform**: process some parameters of any of the previous types, filtering or transfoming its contents.
3) **Descriptive**: describe in some way (by means of plots or statistical analysis) analytical results.

Additionally, I provide a number of **command-line scripts** that perform useful operations on batches of files (quantization, reformatting, feature extraction).

### Main Dependencies

*Pymidifile* works with Python =>2.7 and >=3.6. The following libraries are needed --and are indeed essential descriptive tools-- that this repository combines:

- **mido** for midi file management (https://github.com/olemb/mido).
- **Pandas** for data analysis (http://pandas.pydata.org/).
- **music21** for symbolic music manipulations (http://web.mit.edu/music21/). 
- **seaborn** for plotting graphs and distributions (http://seaborn.pydata.org).

Other dependencies include common python scientific toolkits such as *Numpy*, *scipy-stats* and *json*.
