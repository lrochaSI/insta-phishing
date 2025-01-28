# Teste de Ataque de Phishing
Foi criado para execução de um desafio de código no Bootcamp de Cibersegurança da DIO

O objetivo desse projeto é criar uma página falsa para coleta de usuário e senha de uma rede social

"Você é um especialista em segurança da informação. E está ensinando automatizar o processo de criação de páginas falsas." 


### Ferramentas
- Kali Linux
- setoolkit

### Passo a Passo
Acessar a máquina Kali Linux, logar como root utilizando o comando: ``` sudo su ```

Depois acesse a ferramenta com o comando ``` setoolkit ```

Na sequência escolha as opções:
- Tipo de ataque: ``` Social-Engineering Attacks ```  Digite 1
- Vetor de ataque: ``` Web Site Attack Vectors ``` Digite 2
- Método de ataque: ```Credential Harvester Attack Method ``` Digite 3
- Método de ataque: ``` Site Cloner ``` Digite 2

Utilizei o IP da máquina pois estava em modo Bridge

- URL para clone: http://www.facebook.com

Quando finalizar, abra o navegador na maquina real e acesse o IP escolhido para hospedagem

Digite um usuário e senha para testar a captura

### Resultados

![Image](https://github.com/user-attachments/assets/4360a8a7-403e-45f9-9a28-0c2513511ca6) ![Image](https://github.com/user-attachments/assets/0edd3dbd-6387-4755-918e-477c984d7b7d)
