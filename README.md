<h1 align="center">IA - Agentes Inteligentes</h1>

<h3 align ="center">Agente Reativo Simples</h3>

<p align="justify">Atividade de Inteligência Artificial que consiste na implementação de um agente reativo simples que simule a atuação de um aspirador de pó inteligente. Foi dado as configurações iniciais (localização inicial do robô e posições de sujeira) dos possíveis ambientes. A partir desses dados, foi proposto a execução do aspirador para todas as configurações dadas e a determinação de métricas de desempenho e pontuações para avaliar a racionalidade do agente.</p>

<p align="center">
  <img src="./images/estados-agente.png" width="470""</img>
  <br>Possı́veis estados do agente aspirador de pó.
</p>

<h2 align="left">Compilação e Criação do Ambiente Virtual</h2>

- OS: Ubuntu 22.04.1 LTS | Python 3.10.6

<h3>Requisitos</h3>

- Python 3
- Pip

sudo apt install python3 \
sudo apt install python3-pip \
sudo pip3 install --upgrade pip

<h3>Criação do Ambiente Virtual</h3>

-> Dentro do diretório raiz do projeto
- sudo pip3 install virtualenv
- virtualenv environmentName -> cria ambiente
- source environmentName/bin/activate -> ativa ambiente
- pip3 install pandas
- pip3 install openpyxl
- deactivate

-> Se estiver utilizando Visual Studio Code instale a extensão Jupyter
