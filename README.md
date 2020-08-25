# Data Science com Python (trabalhando com Pandas)  
  
## Criando o ambiente
  
1. [Instalando o Anaconda](https://www.anaconda.com/products/individual)  
2. Setando na variável PATH:
    - raiz da pasta de instalação da Anaconda
    - pasta "Scripts" da pasta de instalação da Anaconda
3. Abrir o "Anaconda Navigator"
  
### Criando ambientes virtuais
Serve para manter um ambiente estático de versões de python e bibliotecas.  
  
3. No console, `conda create --name <nome_do_ambiente> python=<versao> pandas=<versao>`
    - depois de criar, no Anaconda Navigator, na barra nav tem "environments"... lá estará o ambiente criado
    - para ativar o ambiente: `activate <nome_do_ambiente>`
    - para desativar o ambiente, voltando para o ambiente "root": `deactivate`
    - para ver, via console, os ambientes criados: `conda info --envs`
4. No "Anaconda Navigator":
    - em "Home", combo "Applications on" selecionar o ambiente criado
    - instalar o jupyter notebook novamente para aquele ambiente
  
### Troubleshooting
  
1. Anaconda Navigator não starta.  
Executando no console `anaconda-navigator` para abrir o dashboard de aplicações da Anaconda,  
nota-se pelos erros a falha de importação de bibliotecas.  
Depois de algumas tentativas de anular a verificação de ssl:  
`conda config --set ssl_verify false`  
e depois tentar importar as bibliotecas:  
`conda remove <pacote>`  
`conda install <pacote>`  
a solução foi desinstalar todas as instalações de python e remoção de pastas de configuração.  
Depois restart da máquina e instalação do Anaconda novamente.
  
## Notebooks dos cursos básicos de Numpy e Pandas
  
Arquivos .ipynd  
[Pasta do colab.google.com criado dentro de drive](https://drive.google.com/drive/u/0/folders/1EWpNZwrSbkubb4vSznZO-Odt1ASxe4_x)
