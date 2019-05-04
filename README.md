# Informations
Custom configurations to ark server.

# Criação do servidor (Windows)
## Requisitos
### .NET Framework version 4.5
Baixe o [.NET Framework](https://www.microsoft.com/en-us/download/details.aspx?id=30653) e instale

### Steam CMD
Baixar o [Steam CMD](https://arkservermanager.s3.amazonaws.com/release/latest.zip)
Crie um diretório (C://servidores/steam_cmd/) e descompacte os arquivos ali.

### Ark Server Management (ASM)
Baixe e instale o [Ark Server Management](http://arkservermanager.freeforums.net/thread/4/installation-ark-server-manager)

# Configuração
## Portas
As portas por padrão são:
* Server Port: 7777
* Query Port: 27015

OBS: caso elas já estejam sendo usadas por outra aplicação, é necessário trocar.


## Firewall
### Firewall do Windows
* O próprio ASM irá abrir as portas corretamente para cada servidor criado.

### Firewall de anti-virus
* Você precisa abrir as portas listadas acima para TCP e UDP.
* Pode ser necessário também indicar o caminho do executável do servidor: seu-local-de instalacao/ShooterGame/Binaries/Win64/ShooterGameServer.exe

Exemplos
[Abrindo portas no firewall do Windows]([Imgur](https://i.imgur.com/gWUcQbZ.png))


## Obtendo Ip local
* Verifique seu ip público no site [What is my ip](https://www.whatismyip.com/what-is-my-public-ip-address/)


## Obtendo Ip público
* Abra a cmd e digite ipconfig
* Anote a numeração que vai ser indicada em ipv4, geralmente 192.168.1.x


## Roteador
### Abrindo portas no roteador
* Abra uma aba no navegador e digite http://192.168.1.0/ ou http://192.168.1.1/
* A senha padrão de acesso é usuário vazio e senha admin.

OBS: essas informações podem mudar de acordo com a marca do seu roteador.
* Configure a abertura(Forwarding Port) e eventos(Port Triggers) para as portas: 7777 e 27015, indicando o seu ip local (ipv4)

Exemplos
[Forwarding](https://i.imgur.com/BNzSdqx.png)

[Port Triggers](https://i.imgur.com/KKW6EPU.png)

Exemplo de um [tutorial](https://www.youtube.com/watch v=DKcHpcbXsLA&fbclid=IwAR0zxTOUFxTXIUIurUBRz81W9eBcivOJA1RaHWUTDNVwQGnzpGn2msTvCG0)


## Mods
### Oficial
* Mapa: [Ebenus Astrum](https://steamcommunity.com/sharedfiles/filedetails/?id=916417001)
* [Structures Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=731604991)
* [Wild Fertilized Eggs No Tame](https://steamcommunity.com/sharedfiles/filedetails/?id=1191739191)
* [Speedy Flyers](https://steamcommunity.com/sharedfiles/filedetails/?id=919470289)
* [Wyvern Mating](https://steamcommunity.com/sharedfiles/filedetails/?id=814833973)
* [Wyvern Milk Substitute](https://steamcommunity.com/sharedfiles/filedetails/?id=819857895)


## Others
* [Better Milk](https://steamcommunity.com/sharedfiles/filedetails/?id=770949087)
* [Wyvern Milk Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=878539458)
