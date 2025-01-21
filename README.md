Phishing para Captura de Senhas do Facebook

Ferramentas

- Kali Linux
- SET (Social-Engineer Toolkit)

Configuração do Phishing no Kali Linux

1. Acesso Root:
Execute o comando: `sudo su`

2. Início do Setoolkit:
Inicie o SET com o comando: `setoolkit`

3. Seleção do Tipo de Ataque:
Escolha a opção: `Social-Engineering Attacks`

4. Escolha do Vetor de Ataque:
Selecione: `Web Site Attack Vectors`

5. Método de Ataque:
Opte por: `Credential Harvester Attack Method`
Em seguida, escolha: `Site Cloner`

6. Obtenção do Endereço IP da Máquina:
Utilize o comando: `ifconfig` ou `ip addr`

7. URL para Clone:
Insira a URL que deseja clonar: `http://www.facebook.com`

Após a execução dos passos acima, o SET clonará a página do Facebook. Os dados inseridos na página clonada serão capturados e registrados no terminal da máquina que executa o ataque.
