# ocserv.





نصبVPN :

yum install net-tools epel-release radcli bzip2 wget -y


mkdir CISCO-VPN-SERVICE; cd CISCO-VPN-SERVICE

دانلود فایل oc.sh

wget https://github.com/erfanuir/ocserv./blob/main/oc.sh

chmod 777 oc.sh

sed -i -e 's/\r$//' oc.sh

./oc.sh





oc.sh      centos
ocserv-en.sh        ubuntu
