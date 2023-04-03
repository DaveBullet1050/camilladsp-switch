# camilladsp-switch

A set of (very rudimentary) shell scripts used to switch / reload / check CamillaDSP filter YML files

# Package / software dependencies

Camilla-DSP - see https://github.com/HEnquist/camilladsp
websocat - this allows command line communication to Camilla-DSP

# Installation / setup

+ Ensure you are running camilla-dsp with a web socket listener port, eg:
    /usr/local/bin/camilladsp -p 7070

+ If you are running CamillaDSP on a different port, edit the port number in websocat_cli.sh

+ 

# Scripts

    get_config.sh

This displays the currently loaded .yml file (full path), eg:
