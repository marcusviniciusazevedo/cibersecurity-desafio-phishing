# Phishing para captura de senhas do Facebook

Este projeto tem por objetivo entender como acontecem o ataque de phishing, do qual ocorre a captura de credenciais dos usuários de uma das maiores redes sociais do mundo.

### Ferramentas
![Static Badge](https://img.shields.io/badge/Kali%20Linux-black?style=flat&logo=Kali%20Linux&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)
![Static Badge](https://img.shields.io/badge/Setoolkit-black?style=flat&logo=GNOME%20Terminal&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)

### Configurando o Phishing no Kali Linux

- Necessário mudar na máquina virtual a Configuração de Rede para Placa em Modo Bridge, clicar em Ok e reiniciar o sistema. 
- Digitar no Terminal Emulator sudo su, seguido da sua senha de acesso ao Kali Linux para ter acesso como root.
- Digitar setoolkit para acessar a ferramenta.
- Em seguida selecionar o tipo de ataque, no caso 1) Social-Engineering Attacks e Enter.
- A ferramenta socilita os vetores de ataque, no caso 2) Website Attack Vectors Enter. Ele demonstra explicações do tipos de ataques. 
- Selecione em seguida o 3) Credential Harvester Attack Method Enter.
- Digite 2) Site Cloner Enter.
- Você estará rodando um servidor com a página falsa, mas para isso ele precisa do IP da sua máquina. Por isso ele precisa ficar no modo Bridge, para acessar a sua máquina de outra máquina. Dê um enter.
- Irá mostrar o IP da sua máquina, dê um Ente
- Informe a URL a ser clonada, http://www.facebook.com e aperte Enter.
- Abra um navegador em anônimo e digite o IP da sua máquina, que acessará a página clonada.

### Resutados

![Alt text](./passwd.png "Optional title")
