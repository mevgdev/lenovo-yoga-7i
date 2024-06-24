# Yoga Slim 7i 14" 9na Gen - Luna Grey  compatibilidad de Ubuntu linux

## Especificaciones

Procesador Procesador Intel® Core™ Ultra 7 155H (núcleos E de hasta 3,80 GHz núcleos P de hasta 4,80 GHz)
Sistema operativo Windows 11 Home Single Language 64
Tarjeta gráfica Gráficos Intel® Arc™ integrados
Memoria total 32 GB LPDDR5X-7467MHz (soldado)
Unidad de disco primaria 1 TB SSD M.2 2242 PCIe Gen4 TLC
Tipo de pantalla 14" WUXGA (1920 x 1200), OLED, brillante, sin capacidad táctil, HDR 500, 100%DCI-P3, 400 nits, 60 Hz, marco biselado fino, luz azul baja
Cámara 1080P FHD IR with E-Shutter
Batería Polímero de litio de 4 celdas 65 Wh
Fuente de alimentación 65W
Características de seguridad Sin lector de huellas dactilares
Dispositivo de Puntero ClickPad
Teclado Backlit, Luna Grey - Español
Red inalámbrica Wi-Fi 6E 2x2 AX & Bluetooth® 5.1 o superior
Garantía 1 año servicio de recogida o con transporte
Color Luna Grey
Operating System Language SP:Español


## Compatibilidad


| Componente | versión limpia 24.04 | versión 22.04 | versión 23.10 | versión upgradeada desde 22.04 a 24.04 | Comentarios |
|---|---|---|---|---|---|
|Audio| No | si | si | si| en la versión tenía problemas con lag intermitente en el audio tanto en audios como en videos | 	
|Bluetooth| si | si | si | testeando| se me desconecta a ratos el mouse luedo de volver de la ivernación| 	
|Keyboard| si | no | no | si | en los casos que no funcionaba eran los botones del brillo, luego cai que era porque el driver de video no los tomaba|
|Network 	|si | si | si | si| |
|Processor 	| si | si | si | si | |
|Video | si| no | no | si| no reconoce la intel arc en las versiones donde dice no|
|Wireless | si | si | si | si | |


## Versión actual que me encuentro probando versión upgradeada desde 22.04 a 24.04

| bug que ido encontrado | solución que he aplicado |
|--|--|
|problemas con firefox instalado como deb| eliminar dependencias de snap (sudo apt-get purge firefox) |
|problemas con cargar vpn desde el config | antes podía cargar el archivo .config creaba vpn, ahora lo tengo que hacer por consola de wireGuard|
|mouse desconecta luego de ivernar| aún no he buscado solución|
