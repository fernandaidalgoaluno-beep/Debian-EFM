# Debian-EFM

# Projeto Integrador I

Projeto desenvolvido para a disciplina de Projeto Integrador I, com o objetivo de apresentar, instalar, configurar e demonstrar uma distribuição Linux em ambiente virtualizado.

A distribuição escolhida pelo grupo foi o Debian, utilizando o Oracle VM VirtualBox como ferramenta de virtualização.

# 1. Objetivo

O projeto possui como objetivo apresentar as principais características do Debian, demonstrar sua instalação e utilização em uma máquina virtual, apresentar comandos essenciais do sistema e configurar um ambiente voltado à programação.

Entre as atividades desenvolvidas estão:
- Instalação do Debian em uma máquina virtual;
- Configuração do ambiente do sistema;
- Apresentação de comandos básicos de terminal;
- Criação e navegação entre diretórios;
- Instalação de programas e pacotes;
- Configuração de um ambiente de programação;
- Desenvolvimento e execução de programas em C e Python;
- Registro dos testes e resultados;
- Organização dos arquivos e evidências do projeto.

# 2. Distribuição escolhida - Debian

O Debian é uma distribuição GNU/Linux de código aberto, conhecida por sua estabilidade, grande quantidade de pacotes disponíveis e ampla utilização em diferentes contextos.

Neste projeto foi utilizada a versão Debian GNU/Linux 13 (Trixie).

O ambiente gráfico utilizado foi o GNOME.

# 3. Ambiente de virtualização

Para executar o Debian, foi utilizado o Oracle VM VirtualBox, que permitiu a instalação do sistema operacional em uma máquina virtual sem substituir o sistema operacional principal do computador.

A máquina virtual foi utilizada para realizar as configurações, testes, instalações e execução dos programas apresentados neste projeto.

# 4. Ambiente de Programação

O ambiente de programação foi preparado para permitir o desenvolvimento e a execução de programas em Linguagem C e Python.

- Linguagem C

Para compilação dos programas em C, foi utilizado o GCC (GNU Compiler Collection).

A instalação e verificação do compilador foram realizadas através do terminal do Debian.

Exemplos de verificação:
  gcc --version

A compilação do programa foi realizada utilizando:
  gcc media.c -o media

A execução foi realizada com:
  ./media

- Python

Para execução dos programas em Python foi utilizado o Python 3. A versão instalada pode ser verificada por meio do comando:
  python3 --version

A execução do programa foi realizada com: 
  python3 media.py

- Git

O Git foi instalado e sua versão foi verificada através do comando:
  git --version

O Git foi utilizado como ferramenta relacionada ao gerenciamento e organização do projeto e do repositório.

# 5. Comandos utilizados

Durante o processo de configuração e demonstração do ambiente, foram utilizados comandos básicos do terminal do Debian. Sendo eles:

Navegação:
- pwd
- ls
- cd

Criação de diretórios:
- mkdir
- mkdir -p

Atualização do sistema:
- sudo apt update
- sudo apt upgrade -y

Instalação de pacotes:
- sudo apt install build-essential -y

Outros pacotes e ferramentas utilizados no ambiente também foram instalado através do gerenciador de pacotes do Debian, no terminal.

# 6. Programa em C

Nesta etapa, foi desenvolvido um programa simples em C para receber duas notas, calcular a média e informar se o aluno foi aprovado ou reprovado.

O programa funciona da seguinte forma:
1. Solicita a primeira nota;
2. Solicita a segunda nota;
3. Calcula a média aritmética
4. Verifica se a média é maior ou igual a 6;
5. Apresenta o resultado.

O código está disponível no diretório: C/media.c

# 7. Programa em Python

Foi desenvolvido também um programa equivalente em Python.

O programa recebe duas notas, calcula a média e informa a situação do aluno, como foi visto no programa em Linguagem C.

O código está disponível no diretório: Python/media.py

# 8. Testes Realizados

Os programas foram executados no Debian para verificar o funcionamento do ambiente de programação.

Os testes foram registrados por meio de capturas de tela, durante o uso do terminal no Debian. Os registrados foram armazenados em uma pasta e estão disponíveis no diretório: Testes Realizados/

Dentro da pasta, é possível visualizar registros da configuração do ambiente, instalação das ferramentas, verificação das versões, códigos desenvolvidos e execução dos programas.

# 9. Considerações Finais

A configuração do ambiente permitiu realizar a execução dos programas em Linguagem C e Python dentro do Debian virtualizado, através da Oracle VirtualBox. Os testes realizados demonstraram o funcionamento do compilador GCC, do Python 3 e das ferramentas utilizadas durante o desenvolvimento.

O repositório agrupa os códigos e os testes utilizados na demonstração do ambiente de programação do projeto.
