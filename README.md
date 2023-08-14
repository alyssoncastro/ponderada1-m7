# PONDERADA SEMANA 1 - M7 Atividade 1: Configurando o ambiente para a execução de uma aplicação em contêiner 
Alysson C. C. Cordeiro
---
Siga como foi que eu fiz:

### 1° Siga estas etapas para iniciar a aplicação:
Baixe e instale o Docker Desktop em seu sistema a partir deste link: https://www.docker.com/products/docker-desktop/
Baixe o instalador do Docker para o seu sistema operacional a partir do site oficial: https://www.docker.com/get-started

### 2° Execute o instalador e siga as instruções para instalar o Docker.
### 3° Criação do Repositório no Docker.
### 4° Execute e ative tudo que é necessário para rodar como o python, o 'Activate' no script do Venv
---
---
### 5° Com o Docker Desktop em execução, abra o prompt de comando (CMD) e insira o seguinte comando:
´´´´
docker pull alyssoncordeiro/testando 
´´´´
Isso irá recuperar a imagem do contêiner.
### 6° após o download, execute o seguinte comando:

docker run -p 8000:8000 alyssoncordeiro/testando 
Assim, a aplicação será iniciada. Abra um navegador da web e acesse "http://localhost:8000" para visualizar meu currículo.

#### OBS: QUAND0 FOR EXECULTADO, VAI DAR UMA PORTA ERRADA "5000", ENTÃO DÊ UM CRTL + C PARA PARAR. ENTÃO PARARÁ A PORTA 5000 E A 8000 COMECA FUNCIONAR




