# Fundamentos de Redes

Exceto para funções focadas exclusivamente em Auditoria e Conformidade, quase todo profissional de segurança precisa ter um entendimento **básico a intermediário de Redes de Computadores** para se destacar em sua área.
Se você estiver começando na área de cibersegurança, dominar esses fundamentos de redes será essencial para compreender camadas superiores como Segurança de Aplicações, Pentest, Cloud, DevSecOps e muito mais.

## Livros recomendados

- [PDF - Apresentação sobre conceitos básicos de redes](https://www.ece.uvic.ca/~itraore/elec567-13/notes/dist-03-4.pdf)  
- [Computer Networking: A Top-Down Approach – Kurose e Ross](https://a.co/d/7MiYAGD) (Esse foi minha referência durante a graduação. Recomendo fortemente a leitura)  
- [Redes de computadores para leigos](https://a.co/d/gp5vfKp)  

---
## Vídeos recomendados

- [É assim que acontece a comunicação](https://www.youtube.com/watch?v=q0S75nKpmcw)  
- [Curso Completo de Redes de Computadores (em inglês)](https://www.youtube.com/watch?v=qiQR5rTSshw&t=14s)  

---
## 🎓 Cursos recomendados

- [Computer Networking – Georgia Tech na Udacity](https://www.udacity.com/course/computer-networking--ud436)  
- [Bits and Bytes of Computer Networking – Google (Coursera)](https://www.coursera.org/learn/computer-networking)  

---
## Conceitos Fundamentais de Redes - Definições e exemplos que você encontrará no mercado

• IPv4 / IPv6
São protocolos de endereçamento IP usados para identificar dispositivos em uma rede. O IPv4 usa endereços de 32 bits (ex: 192.168.0.1), enquanto o IPv6 usa 128 bits (ex: 2001:0db8::1).
Exemplo de mercado: Provedores de nuvem como AWS, GCP e Azure oferecem suporte a IPv6 para escalar serviços globalmente, principalmente onde o IPv4 está esgotado. Você utilizará essas notações para configurar interfaces ou VPN. Também utilizará na análise de logs e identificação da origem de ameaças

• Conceito de CIDR (Classless Inter-Domain Routing)
É um método de representação de endereços IP com maior eficiência, permitindo blocos de endereço flexíveis (ex: 192.168.0.0/24).
Exemplo de mercado: Utilizado em firewalls e roteadores corporativos para definir regras de acesso e segmentação de rede.

• Endereçamento IP e Subnetting
Alocação de endereços IP e subdivisão de redes em sub-redes menores.
Exemplo de mercado: Empresas segmentam a rede interna em sub-redes para departamentos como RH, Financeiro, TI, etc., isolando o tráfego.

• IPs Públicos vs Privados
IPs públicos são roteáveis na internet; privados (ex: 192.168.x.x) são usados apenas em redes internas.
Exemplo de mercado: Serviços web usam IPs públicos; dispositivos internos (como impressoras e servidores locais) usam IPs privados.

• Modelo TCP/IP
É uma arquitetura de comunicação dividida em quatro camadas usadas para transferência de dados em redes. É o modelo que sustenta a estrutura da Internet de hoje.
Exemplo de mercado: Toda comunicação na internet (HTTP, FTP, DNS, SSH) é baseada nesse modelo.

• DMZs (Zonas Desmilitarizadas)
Segmento de rede isolado que hospeda serviços acessíveis externamente, como servidores web.
Exemplo de mercado: E-commerces colocam servidores de aplicação e web na DMZ para manter a rede interna protegida.

• Redes Zero Trust
Modelo de segurança que não confia em nenhum usuário ou dispositivo por padrão, exigindo autenticação contínua.
Exemplo de mercado: Implementação de autenticação multifator (MFA), passkey e verificação de identidade para todos os acessos, mesmo internos.

• Portas e Protocolos Comuns
Portas são canais lógicos usados por protocolos para comunicação (ex: 22/SSH, 443/HTTPS).
Exemplo de mercado: Empresas usam firewalls para permitir apenas portas específicas, bloqueando serviços não autorizados. Rodar um scan de portas para identificar os serviços que estão rodando em uma estrutura na fase de Recon em um Pentest.

• Criptografia - Módulos e Funções
São conjuntos de funções matemáticas para segurança de dados (hash, cifragem, assinatura digital).
Exemplo de mercado: Aplicativos bancários usam HMAC, AES e RSA para proteger transações.

• Como funciona o DNS
Sistema que traduz nomes de domínio em endereços IP. Pense no modelo endereço e CEP. Um carteiro só entregará sua mercadoria em casa pelo nome da rua e demais dados e não apenas pelo identificado do CEP.
Exemplo de mercado: Ao digitar www.google.com, seu navegador consulta um servidor DNS para obter o IP correto.

• Como funciona o SSL
É um protocolo para criptografar comunicação entre cliente e servidor utilizando o HTTP.
Exemplo de mercado: Sites de e-commerce usam SSL/TLS para proteger dados de pagamento.

• Ameaças Comuns de Rede

MiTM (Man-in-the-Middle ou homem no meio)
Tipo de interceptação de comunicação entre duas partes sem que percebam.
Exemplo: Captura de credenciais em conexões HTTP abertas ou análise de um tráfego web durante um pentest.

Sniffing de rede
Captura de pacotes de dados para análise de informações sensíveis.
Exemplo: Uso de ferramentas como Wireshark em redes Wi-Fi abertas.

Ataques ao TCP
Exploram a estrutura do protocolo TCP (ex: SYN Flood).
Exemplo: Ataques de negação de serviço para sobrecarregar servidores.

DoS/DDoS (Deny of service - Negação de serviço)
Sobrecarga de sistemas com tráfego falso para que não responda ou responda com lentidão as requisições dos clientes.
Exemplo: Botnets lançando DDoS contra sites de apostas ou fintechs.

• Firewalls e SDN (Redes Definidas por Software)
Firewalls controlam o tráfego de rede; SDN separa controle e encaminhamento de pacotes para gestão flexível.
Exemplo de mercado: Empresas utilizam SDN em datacenters para responder rapidamente a incidentes.

• Solução de Problemas de Rede

*Internet lenta ou fora do ar*
Causa comum: Problemas no DNS, interferência de sinal, rota corrompida.
Exemplo: Diagnóstico com ping, traceroute e testes em outro dispositivo.

*Wi-Fi com problema*
Causa comum: Congestionamento de canal, sinal fraco ou senha incorreta.
Exemplo: Alterar canal no roteador, usar 5GHz, redefinir a conexão.

*Redes abertas e vulneráveis*
Risco: Tráfego não criptografado e vulnerabilidade a sniffing ou hijacking.
Exemplo: Evitar conexões públicas sem VPN.
