To view presentation:

    pip install "ipython[notebook]"
    pip install rise
    git clone https://github.com/okcpython/unicode.git
    cd unicode
    jupyter-nbextension install rise --py --sys-prefix
    jupyter-nbextension enable rise --py --sys-prefix
    jupyter notebook unicode.ipynb
    
To install the Reveal.js plugin:

    git clone https://github.com/damianavila/RISE.git
    cd RISE
    python setup.py install
    
    
There is a small chart icon at the end of the notebook toolbar in the presentation.  Clicking it should start the Reveal Slideshow.
