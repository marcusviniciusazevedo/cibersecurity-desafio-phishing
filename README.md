# Phishing para captura de senhas do Facebook

Este projeto tem por objetivo entender como acontecem o ataque de phishing, do qual ocorre a captura de credenciais dos usuários de uma das maiores redes sociais do mundo.

### Ferramentas
![Static Badge](https://img.shields.io/badge/Kali%20Linux-black?style=flat&logo=Kali%20Linux&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)
![Static Badge](https://img.shields.io/badge/Setoolkit-black?style=flat&logo=GNOME%20Terminal&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)

### Configurando o Phishing no Kali Linux

- Necessário mudar na máquina virtual a Configuração de Rede para **Placa em Modo Bridge**, clicar em **Ok** e reiniciar o Kali Linux. 
- Digite no Terminal Emulator **sudo su**, seguido da sua senha de acesso ao Kali Linux para ter acesso como **root**.
- Digite **setoolkit** para acessar a ferramenta.
- Em seguida selecionar o tipo de ataque, no caso **1** no menu, para o item Social-Engineering Attacks e **Enter**.
- É solicitado pela ferramenta os vetores de ataque, no caso **2** ou Website Attack Vectors Enter. Ele demonstra explicações do tipos de ataques. 
- Selecione em seguida o **3** para Credential Harvester Attack Method e **Enter**.
- Digite **2** Site Cloner e **Enter**.
- Você estará rodando um servidor com a página clonada, mas para isso ele precisa do IP da sua máquina, no modo Bridge, para acessar a sua máquina e outras. Dê um **Enter**.
- Irá mostrar o IP da sua máquina, dê um **Enter** novamente.
- Informe a URL a ser clonada, **http://www.facebook.com** e aperte **Enter**.
- Abra um navegador em modo anônimo e digite o IP da sua máquina. Você terá acesso a página clonada.

### Resutados

![Alt text](./passwd.png "Optional title")
