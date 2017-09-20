FROM chesszebra/node:8.5

# Run as root
USER root

# Install bower
RUN npm install -g bower

# Install Polymer
RUN npm install -g --unsafe-perm polymer-cli

# Run as node
USER node

ENTRYPOINT ["polymer"]
