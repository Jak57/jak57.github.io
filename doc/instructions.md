## Instructions for setting up my website locally
* ``cd /mnt/e/jakir/personal_website``
* ``git clone https://github.com/Jak57/jak57.github.io.git``
* ``cd jak57.github.io``
* ``sudo apt update``
* ``sudo apt install ruby-full build-essential zlib1g-dev``
* ``echo '# Install Ruby Gems to ~/.gem' >> ~/.bashrc``
* ``echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc``
* ``echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc``
* ``source ~/.bashrc``
* ``gem install jekyll bundler``
* ``jekyll -v``
* ``jekyll serve``

## GitHub Access token
* ``https://github.com/settings/personal-access-tokens``
