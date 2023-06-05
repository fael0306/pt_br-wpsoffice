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
