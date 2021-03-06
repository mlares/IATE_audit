# pinnacle

.. image:: https://readthedocs.org/projects/pinnacle/badge/?version=latest
:target: https://pinnacle.readthedocs.io/en/latest/?badge=latest
:alt: Documentation Status

.. image:: https://travis-ci.org/IATE-CONICET-UNC/pinnacle.svg?branch=master
    :target: https://travis-ci.org/IATE-CONICET-UNC/pinnacle

.. image:: https://badge.fury.io/py/pinnacle-pub.svg
    :target: https://badge.fury.io/py/pinnacle-pub

Run the statistics and create some plots:

Create or load an ADS API key, and save it in a environment variable ADS_DEV_KEY 

::

   import pinnacle
   # create a config dictionary
   iate = pinnacle.inst_adsentries(config)
   iate.load_inst()
   viz = pub_dataviz(iate)
   viz.plot_all()


The task of this project is to analyze the publication metrics in the IATE.
 


Autor
-----

Project by Marcelo Lares (IATE, UNC).  Developed in 2020.      
