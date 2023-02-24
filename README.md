# ocserv.





نصبVPN :

yum install net-tools epel-release radcli bzip2 wget -y


mkdir CISCO-VPN-SERVICE; cd CISCO-VPN-SERVICE

دانلود فایل oc.sh

chmod 777 oc.sh

sed -i -e 's/\r$//' oc.sh

./oc.sh
