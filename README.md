# Phishing no login do Facebook

Este projeto tem por objetivo entender como acontece o ataque de phishing, do qual ocorre a captura de credenciais dos usuários de uma das maiores redes sociais do mundo. É muito importante se precaver das estratégias de engenharia social no meio virtual, estando atento também aos links de acesso na web. 

### Ferramentas
![Static Badge](https://img.shields.io/badge/Kali%20Linux-black?style=flat&logo=Kali%20Linux&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)
![Static Badge](https://img.shields.io/badge/Setoolkit-black?style=flat&logo=GNOME%20Terminal&logoColor=white&logoSize=auto&link=https%3A%2F%2Fwww.kali.org%2F)

### Configurando o Phishing no Kali Linux

- Necessário mudar na máquina virtual a Configuração de Rede para **Placa em Modo Bridge**, clique em **Ok** e reinicie o Kali Linux. 
- Digite no Terminal Emulator **sudo su**, seguido da sua senha de acesso para ter o privilégio como **root**.
- Digite **setoolkit** para acessar a ferramenta.
- Em seguida selecione o tipo de ataque, no caso **1** no menu, para o item Social-Engineering Attacks e **Enter**.
- É solicitado pela ferramenta os vetores de ataque, no caso **2** ou Website Attack Vectors e **Enter**.
- Digite em seguida o **3** para Credential Harvester Attack Method e **Enter**.
- Digite **2** para o item Site Cloner e **Enter**.
- Você estará rodando um servidor com a página clonada. Precisaremos do IP da sua máquina, no modo Bridge, para acessar a sua máquina e outras. Dê um **Enter**.
- Irá mostrar o IP da sua máquina, dê um **Enter** novamente.
- Informe a URL a ser clonada, **http://www.facebook.com** e aperte **Enter**.
- Abra um **navegador em modo anônimo** e digite o IP da sua máquina. Você terá acesso a página clonada com informações através do terminal no Kali Linux.

### Resutados

![Alt text](./passwd.png "Optional title")
