# Pacote de Tradução e Dicionário do WPS Office 2019 para o Linux Mint 20.x

<div align="center">
<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/y/vaamonde/pt_br-wpsoffice?style=plastic">
<a href="https://github.com/vaamonde/pt_br-wpsoffice/stargazers"><img src="https://img.shields.io/github/stars/vaamonde/pt_br-wpsoffice" alt="Stars Badge"/></a>
<a href="https://github.com/vaamonde/pt_br-wpsoffice/network/members"><img src="https://img.shields.io/github/forks/vaamonde/pt_br-wpsoffice" alt="Forks Badge"/></a>
<a href="https://github.com/vaamonde/dpt_br-wpsoffice/pulls"><img src="https://img.shields.io/github/issues-pr/vaamonde/pt_br-wpsoffice" alt="Pull Requests Badge"/></a>
<a href="https://github.com/vaamonde/pt_br-wpsoffice/issues"><img src="https://img.shields.io/github/issues/vaamonde/pt_br-wpsoffice" alt="Issues Badge"/></a>
<a href="https://github.com/vaamonde/pt_br-wpsoffice/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/vaamonde/pt_br-wpsoffice?color=2b9348"></a>
<a href="https://github.com/vaamonde/pt_br-wpsoffice/blob/master/LICENSE"><img src="https://img.shields.io/github/license/vaamonde/pt_br-wpsoffice?color=2b9348" alt="License Badge"/></a>
</div>

## **Links Oficiais do Linux Mint e do WPS Office:**
Site do Linux Mint: https://www.linuxmint.com/​<br>
Blog do Linux Mint: https://blog.linuxmint.com/​<br>
Site do WPS Office: https://www.wps.com/

## **Alternativas de Pacote Office para o Linux Mint:**
Site do Libre Office: https://pt-br.libreoffice.org/<br>
Site do Free Office.: https://www.freeoffice.com/pt/<br>
Site do Only Office.: https://www.onlyoffice.com/pt/

## **Pacote de Dicionário Customizado para o WPS Office:**
Github: https://raw.githubusercontent.com/rafaelsc/IntelliJ.Portuguese.Brazil.Dictionary/master/portuguese-brazil.dic 

## **Playlist do YouTUBE com todos os Vídeos do Linux Mint 20.x:**
Link da Playlist: https://www.youtube.com/playlist?list=PLozhsZB1lLUOKXT6TIhjwPWBNpUoExsNF

O pacote de Tradução e Dicionário do WPS Office 2019 para o Linux Mint 20.x foi retirado da versão do WPS Office para Windows. Infelizmente a comunidade que era responsável pela tradução e o dicionário da versão Community do WPS Office para GNU/Linux não está mais disponibilizando no site oficial do WPS Office os pacotes de tradução e o dicionário.

Esse script foi testado na versão do WPS Office 2019 release 11.1.0.x no Linux Mint 20.x, antes de executar o script faça a instalação e configuração básica do Pacote .DEB do WPS Office 2019 do site oficial: https://www.wps.com/

## Procedimentos para utilizar esse script no Linux Mint:

#01_ Primeira etapa: Acessar o Terminal e verificar a versão do Linux Mint

	Atalho: Ctrl + Alt + T
	localectl
	cat /etc/os-release

#02_ Segunda etapa.: Instalar o software Git:

	sudo apt update
	sudo apt install git

#03_ Terceira etapa: Clonar o projeto do Github

	git clone https://github.com/vaamonde/pt_br-wpsoffice

#04_ Quarta etapa..: Acessar o repositório clonado localmente

	cd pt_br-wpsoffice/

#05_ Quinta etapa..: Executar o script de atualização do Tradutor e Dicionário

	bash install.sh

#06_ Abrir o WPS Office e verificar se a Tradução e o Dicionário está funcionando

	wps

## Procedimentos para corrigir a Falha de Acentuação do WPS Office 2019 no Linux Mint

#01_ Abrir o WPS Office

	_ na tela inicial do WPS Office clicar em: Global Settings
	_ selecionar: settings
	_ em Settings Other clicar em: Settings Other Options Popup Component
	_ alterar para: Multi-Module Mode <OK>
	_ na tela de Restart WPS to see changes clicar em: <OK>
	_ Fechar o WPS Office e testar a acentuação no Write e Spreadsheets
