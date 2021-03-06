# **NVR (neighborhood variance ratio)**

Python implementation of NVR (neighborhood variance ratio) gene selection to select genes with local and monotonic variation [(Welch et al., 2016)](https://www.ncbi.nlm.nih.gov/pubmed/27215581). The selected genes possess specific expression patterns over the entire data space amenable to trajectory analysis.

### Installation for Mac or Linux

There are two ways to install p-Creode with Mac/Linux operating systems.

1.
```python
git clone git://github.com/KenLauLab/NVR
cd NVR
sudo pip install .
```

2.
```python
sudo pip install nvr
```

### Installation for Windows (in Anaconda2 environment)
In terminal, navigation to directory where you want to install NVR (e.g. d:\src)
```
cd d:\src
git clone git://github.com/KenLauLab/NVR
cd NVR
pip install .
```
Whereas the typical linux approach to importing the module is ```import NVR as nvr```, an Windows/Anaconda2 installation will instead require ```import nvr```.
