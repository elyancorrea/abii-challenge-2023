# ABII CHALLENGE 2023
Repositório com arquivos referentes a competição ABII challenge 2023.

## Executando a aplicação do cronômetro

Esta aplicação permite interagir com o crônometro da prova e também simular o comportamento esperado do drone.
Dúvidas podem ser centralizadas na aba Issues deste repositório.

## Requisitos

* Uma instância do node-red em execução no computador.
* Conectividade com o broker MQTT.

## Como Abrir um Arquivo `flows.json` no Node-RED e Instalar Nodes Ausentes

Este tutorial orientará você sobre como abrir um arquivo `flows.json` no Node-RED e como instalar nodes ausentes usando o Palette Manager.

### Passo 1: Acesse a Interface Web

Abra um navegador da web e vá para o endereço [http://localhost:1880](http://localhost:1880) (ou o endereço onde você configurou o Node-RED).

### Passo 2: Importe o Fluxo

1. Na interface do Node-RED, clique no ícone de menu no canto superior direito (geralmente parece três linhas horizontais empilhadas) e selecione "Import".

2. Isso abrirá a janela "Import Nodes". Aqui, você pode selecionar o arquivo `flows.json` que deseja importar. Clique no botão "Selecionar um arquivo para importar" e escolha o arquivo `flows.json` em seu sistema.

3. Após selecionar o arquivo, clique no botão "Import" na janela "Import Nodes".

4. O Node-RED irá carregar o fluxo a partir do arquivo `flows.json`. Você verá os nodes e conexões no canvas principal.

### Passo 3: Instale Nodes Ausentes

Se o fluxo importado contiver nodes que não estão instalados em seu ambiente Node-RED, siga estas etapas:

1. No Node-RED, clique no ícone de menu novamente e selecione "Manage palette" (Gerenciar paleta).

2. Na guia "Install" (Instalar), você verá uma barra de pesquisa. Digite o nome do node que está faltando.

3. Clique em "Install" ao lado do node desejado, no caso, `node-red-contrib-hourglass` e `node-red-dashboard`.

4. Aguarde enquanto o Node-RED baixa e instala os nodes.

5. Após a instalação bem-sucedida, os nodes estarão disponíveis no seu canvas para uso.

### Passo 4: Faça o deploy

## Como Abrir um Arquivo `flows.json` no Node-RED e Instalar Nodes Ausentes

Este tutorial orientará você sobre como abrir um arquivo `flows.json` no Node-RED e como instalar nodes ausentes usando o Palette Manager.

### Passo 1: Acesse a Interface Web

Abra um navegador da web e vá para o endereço [http://localhost:1880](http://localhost:1880) (ou o endereço onde você configurou o Node-RED).

### Passo 2: Importe o Fluxo

1. Na interface do Node-RED, clique no ícone de menu no canto superior direito (geralmente parece três linhas horizontais empilhadas) e selecione "Import".

2. Isso abrirá a janela "Import Nodes". Aqui, você pode selecionar o arquivo `flows.json` que deseja importar. Clique no botão "Selecionar um arquivo para importar" e escolha o arquivo `flows.json` em seu sistema.

3. Após selecionar o arquivo, clique no botão "Import" na janela "Import Nodes".

4. O Node-RED irá carregar o fluxo a partir do arquivo `flows.json`. Você verá os nodes e conexões no canvas principal.

### Passo 3: Instale Nodes Ausentes

Se o fluxo importado contiver nodes que não estão instalados em seu ambiente Node-RED, siga estas etapas:

1. No Node-RED, clique no ícone de menu novamente e selecione "Manage palette" (Gerenciar paleta).

2. Na guia "Install" (Instalar), você verá uma barra de pesquisa. Digite o nome do node que está faltando.

3. Clique em "Install" ao lado do node desejado, no caso, `node-red-contrib-hourglass` e `node-red-dashboard`.

4. Aguarde enquanto o Node-RED baixa e instala os nodes.

5. Após a instalação bem-sucedida, os nodes estarão disponíveis no seu canvas para uso.

### Passo 4: Salve o Fluxo

Certifique-se de salvar o fluxo após importá-lo e fazer qualquer alteração. Para fazer isso, clique no ícone de disquete (Salvar) no canto superior direito da interface do Node-RED.
