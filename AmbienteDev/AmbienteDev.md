Dia 16/01/2022 
essas anotações foram realizadas pelo nano no sistema operacional windows pela Janela do GitBash, isso foi feito pensando em usar terminais e sistemas operacionais sem interface de 
visualização GUI (Graphic User Interface), confesso que estudar assim me faz se sentir um verdadeiro programador

		Aula com Maik Brito

		Aula 1 - Abertura e ferramentas basicas

	Computador 
precisamos de um computador para fazer essa trilha.

	Editor de texto

visual studio code
irei usar visual studio code

Sublime


	navegador
Chrome
Edge
Firefox
Safari

		Aula 2 - Sugestão de editor online
Para acompanhar o o curso usando apenas um editor de web

https://codepen.io/
https://codesandbox.io/

--
isso não faz parte do curso!! isso é sobre o editor nano!! para colar o link acima no nano tive que verificar isso nesse link

comando para colar da area de transferência "Ctrl + Shift + v" e depois "Shift + Insert", para inserir o caractere "+" do teclado numérico preciso digitar "Shift +"

https://qastack.com.br/superuser/1262153/how-to-paste-into-nano-from-clipboard

sempre que digito o comando "Ctrl Shift v" ele aparece escrito "^v" que preciso apagar manualmente e depois digitar "Shift insert" para colar o link
--

JavaScript Vanilla é o javascript puro.

O CodeSand é mais proximo do que fazemos em nossa máquina.

		Aula 3 - Instalando o Browser no Windows.
Já tenho o Edge instalado em minha máquina 

dicas sobre uso do microsoft edge
https://microsoftedgetips.microsoft.com/pt-br/?form=MT000N

link para download do novo Microsoft Edge
https://support.microsoft.com/pt-br/microsoft-edge/baixe-o-novo-microsoft-edge-baseado-em-chromium-0f4a3dd7-55df-60f5-739f-00010dba52cf

		Aula 4 - Instalando o Visual Studio Code

link do download do Visual Studio Code
https://code.visualstudio.com/Download


		Aula com Jakelyne

		Aula 5 - Instalando o Node JS no Windows

link do download Node JS 

https://nodejs.org/en/download/

existem duas versões para download, a LTS é uma versão consolidada que possui poucos bugs garantindo um desempenho e poucos problemas, a versão current é a versão para entusiastas onde 
estão sendo implementados novos recursos e por conta disso pode possuir muitos bugs, para estudar o melhor é baixar a versão lts que é o que faremos.

O node não estava instalado eu coloquei ele no meu pc, uma delicinha de programa!


		Aula com Mayk Brito

		Aula 6 - Instalando o Edge no Linux

apenas assisti e futuramente irei praticar na minha máquina virtual quando eu ter um ssd maior.

O Mayk usou o Debian Ubuntu 

acredito que esse foi o link que o Mayk usou
https://www.debugpoint.com/2020/10/how-to-install-edge-ubuntu-linux/

lembre-se de sempre usar os comandos 

sudo apt update
comando para atualizar os repositórios

sudo apt upgrade 
comando para aplicar as atualizações

um artigo que explica melhor os comandos acima 
https://qastack.com.br/ubuntu/222348/what-does-sudo-apt-get-update-do#:~:text=A%20execu%C3%A7%C3%A3o%20sudo%20apt%2Dget%20update%20(ou%20sudo%20aptitude%20update,instalados%20%2C%20de%20fontes%20da%20Internet.

dizem que o edge é mais leve que o Chrome.

		
		Aula 7 - instalando o VS code no Linux

link do download do Visual Studio Code
https://code.visualstudio.com/Download

a instalação possui duas etapas

o download feito pelo link disponível acima

e depois ir no diretório (pasta) que o download está e executar alguns comandos que podem ser conferidos na aula
https://app.rocketseat.com.br/node/ambiente-de-dev-de-outro-mundo/lesson/linux-instalando-vs-code

será necessário ver as instruções na documentação se suar versão for diferente do debian ubuntu

		Aula com Jakelyne

		Aula 8 - Instalando o Node JS em Linux


Foi usado o terminal no Linux para realizar a instalação

devemos usar o curl para fazer a instalação

antes de realizar qualquer instalação usamos os comandos
sudo apt-get update
sudo apt-get upgrade

Instalamos esse aplicativo através do comando
sudo apt install curl

ctrl + l para limpar o terminal 

agora será realizado o download do nvm que é um gerenciador de versões do NodeJS no Ubuntu

o comando para isso é
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

consegui esse link de instalação acima no seguinte link:
https://fabiojanio.medium.com/nvm-gerencie-m%C3%BAltiplas-instala%C3%A7%C3%B5es-do-node-js-6fcd0f13aaf7

eu sempre deixo as fontes de links que me ajudaram a resolver um problema para prestigiar a pessoa que me ajudou, eu amo a comunidade e sempre busco valorizar suas ajudas, considero 
necessário sempre deixar as fontes originais das coisas que acesso para resolver minhas dificuldades, acredito ser um tipo de honestidade intelectual.

o curl busca o conteudo no caminho https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh

o bash é um comando que executa o arquivo install.sh

agora precisamos usar o comando para gerar o arquivo bash.rc
source ~/.bashrc

esse comando recarrega o arquivo no caminho ~/.bashrc

o comando que mostra todas as versões dísponiveis do node, assim podemos usar a versão que a empresa que estamos usa.
nvm list-remote

o nvm ajuda a gente usar varias versões para varios projetos sem a necessidade de ficar instalando e desinstalando as versões do node, assim basta olhar a lista e escolher, as versões em 
verde são as versões estaveis do node, escolhemos a versão e usamos o botão direito do mouse na versão selecionada no terminal e escolhemos a opção copy.

depois usamos o comando
nvm install 
na frente do nvm install colamos usando botão direito do mouse e a opção "paste", que cola a versão do node que escolhemos.

npm ou yarn é o gerenciador de pacotes que podemos usar no nodejs

nvm use "versão do node"
Comando que diz para a máquina qual versão desejamos usar. Instalamos a versão antes como mostrado no passo anterior

node -v 
comando que verifica se o programa existe e qual versão que existe.

com o node instalado podemos usar seus comandos em nosso projeto


		Aula com Mayk Brito

		Aula 9 - Instalando o Chrome no MacOS

não tem mac nem acesso a esse computador então apenas assisti as aulas e não poderei praticar por hora.

link para download do Google Chrome
https://www.google.com/intl/pt-BR/chrome/

		Aula 10 - Instalando o VS code no MacOS

link do download do Visual Studio Code
https://code.visualstudio.com/Download

acesse o link faça o download do arquivo encontre o arquivo execute ele no MacOS


