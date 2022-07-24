# AdGuardHome
Centro de protección de la privacidad para usted y sus dispositivos en docker con Adguard Home

<p align="center">
    <img src="https://brands.home-assistant.io/_/adguard/logo.png" alt="PNG" height="120px"  />
    <img src="https://logos-world.net/wp-content/uploads/2021/02/Docker-Symbol.png" alt="PNG" height="170px" />
    <h3 align="center">Privacy protection center for you and your devices</h3>
<p align="center">
  Free and open source, powerful network-wide ads & trackers blocking DNS server.
</p>
</p>


### Requeriments
- Servicio docker en funcionamiento
- Repositorio clonado de Adguard

### Instalar
```
git clone https://github.com/AzagraMac/AdGuardDocker.git
```

### Desplegar contenedor docker
```
docker-compose up -d
```

### Consultar contenedor
```
docker ps -a
docker-compose ps
docker-compose log adguard
```
### Acceso al dashboard
`http://<IP_ADDPRESS_OF_YOUR_SERVER>`

Ready!
