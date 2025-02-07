FROM rocker/verse:latest

# Install Quarto
RUN wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.4.551/quarto-1.4.551-linux-amd64.deb && \
    dpkg -i quarto-1.4.551-linux-amd64.deb && \
    rm quarto-1.4.551-linux-amd64.deb

# Copy dotfiles
COPY .zshrc /root/.zshrc