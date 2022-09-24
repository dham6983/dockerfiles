# How to use the docker image
#
# docker run --rm -it \
#	--name ubuntu \
#	dshome/customubuntu-image \
#   bash
#

FROM ubuntu
LABEL maintainer "Debabrata Shome <dham6983@gmail.com>"
RUN apt-get update && \
    apt install build-essential -y

CMD ["bash"]
