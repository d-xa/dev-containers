FROM ubuntu

RUN apt update

# vim editor
RUN apt install -y vim

# google-chrome
RUN wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb \
    && sudo apt install -y ./google-chrome-stable_current_amd64.deb

# vs code
RUN apt install -y software-properties-common apt-transport-https wget \
    && wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add - \
    && echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list \
    && apt install -y code

# sublime text
#RUN command \
#    && echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list