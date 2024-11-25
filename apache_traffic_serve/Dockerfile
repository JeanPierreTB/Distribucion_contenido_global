# Utilizar la imagen base de Traffic Server
FROM wernight/trafficserver:latest

# Copiar los archivos de configuración personalizados al contenedor
COPY records.config /usr/local/etc/trafficserver/records.config
COPY remap.config /usr/local/etc/trafficserver/remap.config

# Abrir el puerto 8080
EXPOSE 8080

# Comando para iniciar Traffic Server
CMD ["traffic_server", "-T", "p"]
