# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Taps
tap homebrew/python
tap homebrew/homebrew-games

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
#sudo ln -s /usr/local/bin/gsha256sum /usr/local/bin/sha256sum

# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
install findutils
# Install GNU `sed`, overwriting the built-in `sed`
install gnu-sed --default-names
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
install bash
install bash-completion

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
install homebrew/dupes/grep
install homebrew/dupes/screen
install homebrew/php/php55 --with-gmp

# Install some CTF tools; see https://github.com/ctfs/write-ups
install bfg
install binutils
install binwalk
install cifer
install dex2jar
install dns2tcp
install fcrackzip
install foremost
install hashpump
install hydra
install john
install knock
install nmap
install pngcheck
install sqlmap
install tcpflow
install tcpreplay
install tcptrace
install ucspi-tcp # `tcpserver` et al.
install xpdf
install xz

# Install other useful binaries
install ack
install bfg
install exiv2
install ffmpeg
install git
install gource
install imagemagick --with-webp
install lynx
install mercurial
install node # This installs `npm` too using the recommended installation method
install p7zip
install pigz
install pillow
install pv
install python
install rename
install rhino
install tree
install webkit2png
install zopfli

# Install games
install gnu-chess


# Remove outdated versions from the cellar
cleanup
