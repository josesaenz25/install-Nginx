#!/bin/bash

# Actualizar la lista de paquetes disponibles
sudo apt update

# Instalar Nginx
sudo apt install -y nginx

# Iniciar el servicio de Nginx
sudo systemctl start nginx

# Habilitar Nginx para que se inicie automáticamente al arrancar el sistema
sudo systemctl enable nginx

# Verificar el estado del servicio de Nginx
sudo systemctl status nginx

# Mostrar la dirección IP del servidor para verificar la instalación
echo "Nginx instalado y en ejecución. Puedes verificar accediendo a la IP de tu servidor en un navegador web:"
hostname -I
