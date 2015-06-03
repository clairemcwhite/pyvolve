Pyvolve
============

Pyvolve is an open-source Python module for simulating sequences along a phylogenetic tree according to continuous-time Markov models of sequence evolution.

A detailed user manual for Pyvolve is available [here](https://github.com/sjspielman/pyvolve/raw/master/user_manual/pyvolve_manual.pdf), and API documentation for Pyvolve is available at [http://sjspielman.org/pyvolve](http://sjspielman.org/pyvolve). See [here](http://sjspielman.org/announcing_pyvolve) for a blog post introducing Pyvolve!

Pyvolve has several dependencies:
* [Biopython](http://biopython.org/wiki/Download)
* [Scipy and Numpy](http://www.scipy.org/install.html)

You can install Pyvolve directly using `pip` or `easy_install` (note that, if needed, these lines will install any missing dependencies for you!):
```bash
pip install pyvolve
# OR
easy_install install pyvolve
```
Note that these commands might need `sudo` in front, depending on your permissions.

To update your version of Pyvolve (for pip), simply use the `--upgrade` argument (again, possibly w/ sudo):
```bash
pip install --upgrade pyvolve
```

Alternatively, you can download and install from source. Download the most recent version of Pyvolve from the Releases tab ([https://github.com/sjspielman/pyvolve/releases](https://github.com/sjspielman/pyvolve/releases)), uncompress the file, and navigate into the `pyvolve/` directory. From this directory, enter the following commands:
```bash
sudo python setup.py install
sudo python setup.py test  # optional, but recommended
```

If you do not have root privileges, you can install Pyvolve for only you (the user!) with this line instead:
```bash
python setup.py install --user
```

Please file any bugs and/or relay any questions under the Issues tab: [https://github.com/sjspielman/pyvolve/issues](https://github.com/sjspielman/pyvolve/issues).

*If you use Pyvolve in your research, please cite us!* <br>
Spielman, SJ and Wilke, CO. 2015. "Pyvolve: a flexible Python module for simulating sequences along phylogenies". *biorXiv*. doi: http://dx.doi.org/10.1101/020214


