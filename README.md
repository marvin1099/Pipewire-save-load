# Pipewire-save-load

Unclean script to save and load your pipewire wires.  
Also a name to id function is included since its nice to have.  

# Download
Go To  
Main Repo: https://codeberg.org/marvin1099/Pipewire-save-load/releases  
Backup Repo: https://github.com/marvin1099/Pipewire-save-load/releases  
Then download the pipewire-script.sh file and run it with the needed option   

# Usage

      Usage:
    ./wipewire-script.sh save                             - To save wires
    ./wipewire-script.sh load                             - To load wires
    ./wipewire-script.sh getpid 'nodename' 'otherreturn'  - To get nodeid, otherreturn is optional
    ./wipewire-script.sh getnid 'portname' 'otherreturn'  - To get portid, otherreturn is optional
    ./wipewire-script.sh lsnodes                          - To list all nodes with names
    ./wipewire-script.sh lsports                          - To list all ports with names
    The config that is used for save and load is ./pipewirewires.conf