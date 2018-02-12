********************************************************
RNA3D: Explore RNA structure from evolutionary couplings
********************************************************

Description
===========
A set of scripts that allow for the processing of RNA alignments for the Evolutionary Couplings analysis. (It is an elaboration on 
the process used in `Weinreb et al (2016) <https://marks.hms.harvard.edu/ev_rna/>`_.) The main tools allow to read and create
Dot-plots of:
1. Secondary structure annotations from Stockholm alignments.
2. Evolutionary Couplings results.
3. FR3D interactions (from `RNA Structure Atlas <http://rna.bgsu.edu/rna3dhub/pdb>`_.)
4. Proximity of bases in a PDB file (given distance threshold)

Additionally, it includes a simple pipeline that allows to perform the necessary processing on an RNA alignment to perform the Evolutionary Couplings analysis and then plot the results against its annotated secondary structure and if desired, its 3D structure. An important feature of this pipeline is the ability to map the sequence from the original alignment (with the secondary structure annotation) to the reduced alignment (required for the EC computation) to the unaligned PDB sequence.

Requirements
============
For the stand-alone tools:

- ``python 2.7.13``
    + The ``python`` dependencies are specified in `requirements.txt <https://github.com/nataquinones/RNA3D/blob/master/requirements.txt>`_

For the full pipleline (EC analysis and mapping):

- ``plmc`` [`download <https://github.com/debbiemarkslab/plmc/>`_]

- From ``Infernal 1.1.2`` [`download <http://eddylab.org/infernal/infernal-1.1.2.tar.gz>`_]
    + ``cmalign``
    + ``esl-alimask``
    + ``esl-reformat``

Use
===
Jupyter notebooks and stand-alone tools:
----------------------------------------
.. code:: bash

    # 1. Clone or download repository
    TO_DO



Pipeline:
---------
.. code:: bash

    # 1. Clone or download repository
    cd /path/to/RNA3D
    git clone https://github.com/nataquinones/RNA3D.git

    # 2. Modify config/paths_local.py with appropriate paths
    TO_DO

    # 3. Create a new virtual environment
    virtualenv /path/to/RNA3D-venv/
    source /path/to/RNA3D-venv/bin/activate
    cd /path/to/RNA3D
    pip install -r requirements.txt

    # 4. Run pipeline
    cd /path/to/RNA3D
    TO_DO


    # For help
    TO_DO




Pipeline structure
==================

TO_DO
