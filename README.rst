speedtest-cli
=============

CLI test bande passante
speedtest.net

.. image:: https://img.shields.io/pypi/v/speedtest-cli.svg
        :target: https://pypi.python.org/pypi/speedtest-cli/
        :alt: Latest Version
.. image:: https://img.shields.io/pypi/dm/speedtest-cli.svg
        :target: https://pypi.python.org/pypi/speedtest-cli/
        :alt: Downloads
.. image:: https://img.shields.io/pypi/l/speedtest-cli.svg
        :target: https://pypi.python.org/pypi/speedtest-cli/
        :alt: License

Versions
--------

speedtest-cli fonctionne avec Python 2.4-3.5

.. image:: https://img.shields.io/pypi/pyversions/speedtest-cli.svg
        :target: https://pypi.python.org/pypi/speedtest-cli/
        :alt: Versions

Installation
------------

pip / easy\_install
~~~~~~~~~~~~~~~~~~~

::

    pip install speedtest-cli

ou

::

    easy_install speedtest-cli

Github
~~~~~~

::

    pip install git+https://github.com/panhwerion/speedtest-cli.git

ou

::

    git clone https://github.com/panhwerion/speedtest-cli.git
    python speedtest-cli/setup.py install

Téléchargement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

    wget -O speedtest-cli https://raw.githubusercontent.com/panhwerion/speedtest-cli/master/speedtest.py
    chmod +x speedtest-cli

ou

::

    curl -Lo speedtest-cli https://raw.githubusercontent.com/panhwerion/speedtest-cli/master/speedtest.py
    chmod +x speedtest-cli

Usage
-----

::

    $ speedtest-cli -h
    usage: speedtest-cli [-h] [--bytes] [--share] [--simple] [--csv]
                         [--csv-delimiter CSV_DELIMITER] [--csv-header] [--json]
                         [--list] [--server SERVER] [--mini MINI] [--source SOURCE]
                         [--timeout TIMEOUT] [--secure] [--version]
