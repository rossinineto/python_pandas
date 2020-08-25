# Data Science com Python (trabalhando com Pandas)  
  
## Criando o ambiente
  
1. [instalando o Anacopnda](https://www.anaconda.com/products/individual)  
2. Setando na variável PATH:
    - raiz da pasta de instalação da Anaconda
    - pasta "Scripts" da pasta de instalação da Anaconda
  
### Troubleshooting
  
1. Anaconda Navegador não starta.  
Executando no console `anaconda-navegador` para abrir o dashboard de aplicações da Anaconda,  
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
