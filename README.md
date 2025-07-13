# SQLinjection usando Kali con docker DVWA

En la actualidad hay tantos sitios que ofrecen cursos y capacitaciones de toda indole, entonces tanta informacion para un principiante te desconcierta, por eso nace este espacio como un aporte para la comunidad de habla hispana.

# Requerimientos
Descargar la ISO de Kali X86_64 que pesa 4.1GB: https://www.kali.org/get-kali/#kali-platforms ------*****-------- usa el hash SHA256 para validar la integridad de tu descarga, mi hash de descarga es 5723d46414b45575aa8e199740bbfde49e5b2501715ea999f0573e94d61e39d3 

# Instalacion de Kali y docker DVWA
Instalación de Kali Linux en computadoras de escritorio y portátiles mediante archivos ".ISO" (x64/x86)
https://www-kali-org.translate.goog/docs/installation/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=tc

Una vez instalado desde la terminal de Kali usamos los siguientes comandos para actualizar la lista de paqueres disponibles e instalar las versiones mas recientes de los paquetes:

sudo apt update
sudo apt upgrade 
 
como siguiente paso vamos a instalar el docker en el kali:

sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker

Ahora vamos a instalar el docker compose (Opcional pero recomendado)

sudo apt install docker-compose -y



# Consultas SQL en pagina web


