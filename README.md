# Actualizar_debian-12-13Actualizar de Debian 12 a 13
pasar de debian bookworm a trixie



sudo apt update

sudo apt upgrade

sudo apt full-upgrade



sed -i 's/bookworm/trixie/g' /etc/apt/sources.list


sudo apt update

sudo apt upgrade

sudo apt full-upgrade

sudo apt --purge autoremove
