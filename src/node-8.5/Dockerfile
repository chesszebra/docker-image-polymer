FROM chesszebra/node:8.5

# Run as root
USER root

# Install bower
RUN npm install -g bower

# Run as node
USER node

# Install Polymer
RUN npm install -g polymer-cli

ENTRYPOINT ["polymer"]
