# Mac OS
Mac does not have a preinstalled package manager. Homebrew has been highly ranked.

* Install [Homebrew](https://brew.sh/) Package Manager.

## Git

* Install Git
    ```sh
    brew install git 
    ```

## Python 3.x

* List available Python3.x versions
    ```sh
    brew search Python@3.
    ```
* Install Python version
    ```sh
    brew install python@3.10
    ```

## Text Editor 

* [Text Editors](/texteditor/)




## Bash Shell

The default shell in some versions of macOS is Bash, and Bash is available in all versions, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities).

To see if your default shell is Bash type `echo $SHELL` in Terminal and press the `Return` key. If the message printed does not end with '/bash' then your default is something else and you can run Bash by typing `bash`

If you want to change your default shell, see [this Apple Support article](https://support.apple.com/en-au/HT208050) and follow the instructions on "How to change your default shell".