<h1>Phishing para captura de senhas</h1>

<h3>Ferramentas necessárias</h3>
<li>Kali Linux</li>
<li>setoolkit</li>

<h3>Configurando o Phishing no Kali Linux</h3>

Primeiro de tudo é necessário ter acesso root, para isso use o comando: <code>sudo su</code> <br>
Iniciando a ferramenta setoolkit, basta inserir esse comando no terminal: <code>setoolkit</code> <br>
Tipo de ataque: <code>1 - Social-Engineering Attacks</code> <br>
Vetor de ataque: <code>2 - Web Site Attack Vectors</code> <br>
Método de ataque: <code>3 - Credential Harvester Attack Method</code> <br> 
Método de ataque: <code>2 - Site Cloner</code> <br>
para encontrar o endereço ip da sua máquina só usar este comando no terminal: <code>ifconfig</code> <br>
agora so inserir uma URL para clonar, aqui esta um exemplo: https://www.facebook.com <br>
Resultado esperado: <br>
![foto do resultado da aplicação](CyberSec/passwd.png "Resultado das senhas obtidas")
