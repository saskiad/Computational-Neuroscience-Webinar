# Computational-Neuroscience-Webinar
Demo content for the Computational Neuroscience Webinar. April 28 and 29, 2025.

The notebook demonstrates how to access the Allen Brain Observatory Visual Coding 2-photon dataset. The data is hosted on a public S3 bucket on the AWS Open Data Registry. This notebook demonstrates exploring the dataset and visualizing the contents of one session.
There is more extensive documentation at https://observatory.brain-map.org/visualcoding/ as well as in the Data Book for the Summer Workshop on the Dynamic Brain https://allenswdb.github.io/intro.html

Note: I've noticed issues where updates to Colab are impacting the numpy and pandas versions. Pinning numpy to <2.0 or upgrading pandas appear to resolve this, but I've found I need to tweak the very first set-up cell every time I return to this code. 
