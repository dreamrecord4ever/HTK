HTK
===

Here are some useful HTK initial model generators.

\1. genProto.py

| A python code to generate lib/proto file.
| 

\* Usage

::

    python genProto.py -s [# of states] -o [outputPath]

\2. genMix.py

| A python code to generate lib/mix2_10.hed file
| 

\* Usage

::

    python genMix.py -s [# of states] -g [# of Gaussian mixtures per state] -m [modelListPath] -o [outputPath]

| You must specify each model's name in file **modelList**. There is an example in the directory.
