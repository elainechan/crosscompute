CrossCompute
============
Publish your computational model.

Installation from PyPI
----------------------

    pip install -U crosscompute
    pip install -U crosscompute-integer crosscompute-text crosscompute-table

    git clone https://github.com/invisibleroads/crosscompute-examples
    crosscompute run find-prime-factors
    crosscompute serve find-prime-factors

Installation from GitHub
------------------------

    git clone https://github.com/invisibleroads/crosscompute
    git submodule init
    git submodule update
    cd crosscompute; python setup.py develop
    cd crosscompute/opt/crosscompute/types/integer; python setup.py develop
    cd crosscompute/opt/crosscompute/types/text; python setup.py develop
    cd crosscompute/opt/crosscompute/types/table; python setup.py develop

    crosscompute run find-prime-factors
    crosscompute serve find-prime-factors