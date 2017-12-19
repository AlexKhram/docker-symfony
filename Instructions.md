#### Fix permissions (you can skip if command/init-dist-files.sh executed):
    cd ~/sites/symfony && sudo setfacl -R -m u:82:rwX -m u:`whoami`:rwX backend
    cd ~/sites/symfony && sudo setfacl -dR -m u:82:rwX -m u:`whoami`:rwX backend
