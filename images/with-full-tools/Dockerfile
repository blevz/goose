FROM my-base-image:latest

# Install more deps
RUN apt-get update && \
    apt-get install -y \
    # Base runtime dependencies
    libssl3 \
    ca-certificates \
    libxcb1 \
    libdbus-1-3 \
    # Development and debugging tools
    git \
    curl \
    wget \
    ripgrep \
    # Python support
    python3 \
    python3-pip \
    # X11 and screenshot capabilities
    x11-apps \
    scrot \
    imagemagick \
    # Additional development libraries
    build-essential \
    libffi-dev && \
    rm -rf /var/lib/apt/lists/*

