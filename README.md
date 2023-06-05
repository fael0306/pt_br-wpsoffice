# Pacote de Tradução e Dicionário do WPS Office 2019 para o Linux Mint 20.x

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
