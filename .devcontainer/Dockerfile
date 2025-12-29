FROM mcr.microsoft.com/devcontainers/ruby:3.1

# Install Jekyll dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    && rm -rf /var/lib/apt/lists/*

# Create gem directory with proper permissions
RUN mkdir -p /home/vscode/.gems && chown -R vscode:vscode /home/vscode/.gems

# Set up gems to install in user space
ENV GEM_HOME=/home/vscode/.gems
ENV PATH=$GEM_HOME/bin:$PATH

# Install bundler as vscode user
USER vscode
RUN gem install bundler
