#
# Dockerfile for alyz/devenv
#

# Pull base image.
FROM alyz/devbase

# Install utilities
RUN apt-get update \
    && apt-get -y upgrade \
    && apt-get install -y sudo rsync

# Install python
RUN apt-get install -y python python3

# Install python libraries
RUN apt-get install -y python-gd python-imaging python-magic python-six python3-magic python3-six \
    && apt-get install -y python-openssl python3-openssl \
    && apt-get install -y python-crypto python3-crypto \
    && apt-get install -y python-webob python3-webob \
    && apt-get install -y python-paste python3-paste python-pastedeploy python3-pastedeploy \
    && apt-get install -y python-reportlab python3-reportlab

# install tools
RUN apt-get install -y poppler-utils
