# viber_to_ubuntu18.04_and_other
steps:
1. Download viber on oficial site from fedora https://download.cdn.viber.com/desktop/Linux/viber.rpm
2. install alien app   $ sudo apt-get install alien
3. Change dir from your downloaded file (cd ./Dowload)
4. reconfigure file .rpm to .deb   $ sudo alien --to-deb --scripts ./viber.rpm
5. install reconfigure app  $ sudo dpkg -i ./viber_7.0.0.1035-3_amd64.deb
