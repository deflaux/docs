
To run the docker container locally:

1. Install `Docker`_ for your platform.
2. Run command ``docker run gcr.io/bioc_2015/devel_sequencing``

See https://github.com/googlegenomics/gce-images for the Docker file.  It depends upon http://www.bioconductor.org/help/docker/ which depends upon https://github.com/rocker-org/rocker/wiki.

Note that its big, over ``4GB``, since it is derived from the `Bioconductor Sequencing view <http://www.bioconductor.org/packages/release/BiocViews.html#___Sequencing>`_ and contains many annotation databases.
