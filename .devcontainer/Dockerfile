# Dockerfile
FROM texlive/texlive:X

# Set working directory
WORKDIR /workspace

# Install additional tools if necessary
RUN apt-get update && apt-get install -y \
    git \
    make \
    && apt-get clean

# Default command
CMD ["/bin/bash"]
