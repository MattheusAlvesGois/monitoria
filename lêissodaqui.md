# monitoria
corrigindo erro da inserção no bd

; Desinstalando o Apache2! (lembrar de mover o projeto todo pra outro lugar) ;
sudo service apache2 stop 

sudo chmod 775 /etc/init.d/apache2

sudo rm /etc/init.d/apache2

; Instalando o Xampp ;

uname -m

32 bits: wget https://ufpr.dl.sourceforge.net/project/xampp/XAMPP%20Linux/7.4.11/xampp-linux-7.4.11-0-installer.run -O xampp-installer.run

64 bits: wget "https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/7.4.27/xampp-linux-x64-7.4.27-2-installer.run/download" -O xampp-installer.run

chmod +x xampp-installer.run

sudo ./xampp-installer.run

sudo /opt/lampp/manager-linux-x64.run

(trocar porta do mysql no xampp)
