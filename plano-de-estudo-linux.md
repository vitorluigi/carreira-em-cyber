# Competências em Linux para o início da carreira em Cybersecurity

### Livros
1. [Linux Basics for Hackers](https://amzn.in/d/0otpFHj)
2. [Certificação Linux Essentials](https://a.co/d/0aRknOJ)

### Cursos
1. [Introdução aos comandos Linux e Scripts](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting)
2. [Fundamentos do Linux para profissionais de Cyber](https://www.cybrary.it/course/linux-fundamentals-for-security-practitioners/)
3. [Fundamentos de Linux](https://academy.tcm-sec.com/p/linux-fundamentals)

### Videos
1. [Canal Certificação Linux](https://www.youtube.com/c/Certifica%C3%A7%C3%A3oLinux)
2. [60 Comandos em 10 minutos](https://www.youtube.com/watch?v=QG9CeHoQUc0)


## Comandos básicos de Linux
Você não deve levar mais de 2 semanas para se sentir confortável com os comandos básicos do Linux para fazer as atividades diárias.
Bug bouties, pentesters e quase todos os profissionais de segurança focados em tecnologia usam sistemas operacionais como Kali Linux, Parrot OS ou BlackArch Linux, que têm muitas ferramentas de segurança para usar.
Mas para isso, você precisa conhecer o funcionamento básico do Linux e os comandos.
Uma vez que você esteja seguro no domínio dos comandos básicos, comece a utilizar comandos de rede, de administração de sistemas e de segurança.

### Comandos básicos do Linux em ordem alfabética (não estão em ordem de importância).

## awk
Processamento de texto baseado em padrões
- Exemplo: awk '{print $1}' arquivo.txt

## cat
Exibe o conteúdo de arquivos
- Exemplo: cat arquivo.txt

## cd
Muda o diretório atual
- Exemplo: cd /home/usuario

## chmod
Modifica permissões de arquivos/diretórios
- Exemplo: chmod 755 script.sh

## chown
Altera o proprietário de arquivos/diretórios
- Exemplo: chown usuario:grupo arquivo.txt

## cp
Copia arquivos ou diretórios
- Exemplo: cp arquivo.txt /backup/arquivo.txt

## curl
Transferência de dados via URL
- Exemplo: curl https://exemplo.com

## dig
Consulta DNS
- Exemplo: dig google.com

## du
Mostra uso de espaço em disco
- Exemplo: du -sh /home/usuario

## df
Mostra o espaço em disco disponível
- Exemplo: df -h

## echo
Exibe uma mensagem ou variável
- Exemplo: echo $HOME

## export
Define variáveis de ambiente
- Exemplo: export PATH=$PATH:/novo/caminho

## find
Busca arquivos e diretórios
- Exemplo: find / -name "senha.txt"

## grep
Busca texto em arquivos
- Exemplo: grep "erro" /var/log/syslog

## head
Exibe as primeiras linhas de um arquivo
- Exemplo: head -n 10 arquivo.txt

## history
Mostra o histórico de comandos
- Exemplo: history | grep ssh

## host
Consulta DNS
- Exemplo: host github.com

## ifconfig
Configura interfaces de rede
- Exemplo: ifconfig eth0

## kill
Encerra processos
- Exemplo: kill 1234

## less
Visualiza conteúdo de arquivos com paginação
- Exemplo: less /var/log/syslog

## locate
Busca arquivos rapidamente
- Exemplo: locate bashrc

## ls
Lista arquivos e diretórios
- Exemplo: ls -la /etc

## man
Mostra o manual de comandos
- Exemplo: man ls

## mkdir
Cria diretórios
- Exemplo: mkdir nova_pasta

## more
Visualiza conteúdo de arquivos com paginação
- Exemplo: more arquivo.txt

## mount
Monta sistemas de arquivos
- Exemplo: mount /dev/sdb1 /mnt

## mv
Move ou renomeia arquivos/diretórios
- Exemplo: mv velho.txt novo.txt

## nslookup
Consulta DNS
- Exemplo: nslookup example.com

## ping
Testa conectividade de rede
- Exemplo: ping 8.8.8.8

## ps
Lista processos em execução
- Exemplo: ps aux | grep apache

## pwd
Mostra o diretório atual
- Exemplo: pwd

## rm e rmdir
Remove arquivos e diretórios
- Exemplo: rm arquivo.txt ou rmdir pasta

## scp
Copia arquivos entre computadores via SSH
- Exemplo: scp arquivo.txt user@host:/destino/

## sed
Editor de texto em linha
- Exemplo: sed 's/velho/novo/g' arquivo.txt

## service/systemctl
Gerencia serviços do sistema
- Exemplo: sudo systemctl restart nginx

## sort
Ordena linhas de texto
- Exemplo: sort nomes.txt

## ssh
Conecta-se a outro computador via SSH
- Exemplo: ssh user@192.168.0.10

## sudo
Executa comandos como superusuário
- Exemplo: sudo apt update

## tail
Exibe as últimas linhas de um arquivo
- Exemplo: tail -f /var/log/syslog

## tar
Compacta e descompacta arquivos .tar
- Exemplo: tar -czvf backup.tar.gz pasta/

## top
Monitora processos em tempo real
- Exemplo: top

## touch
Cria arquivos vazios
- Exemplo: touch novo_arquivo.txt

## uname
Mostra informações do sistema
- Exemplo: uname -a

## uniq
Remove linhas duplicadas
- Exemplo: uniq arquivo.txt

## wget
Baixa arquivos da internet
- Exemplo: wget https://exemplo.com/arquivo.zip

## whois
Consulta informações de domínios
- Exemplo: whois openai.com

## whatis
Descrição rápida de um comando
- Exemplo: whatis ls

## w
Mostra quem está logado no sistema
- Exemplo: w

## wc
Conta palavras, linhas e caracteres
- Exemplo: wc -l arquivo.txt

## zip
Compacta arquivos em .zip
- Exemplo: zip backup.zip arquivo1.txt arquivo2.txt

# Comandos que profissionais de segurança (principalmente AppSec e Pentesters) precisam conhecer:

## **netcat**
Ferramenta versátil para leitura, escrita e depuração de conexões de rede.
Exemplo: nc -v google.com 80 – testa a conectividade com o servidor da Google na porta 80.

## **nslookup**
Realiza consultas DNS, útil para verificar endereços IP de domínios.
Exemplo: nslookup example.com – retorna o IP do domínio example.com.

## **host**
Consulta simplificada de DNS, semelhante ao nslookup.
Exemplo: host example.com – retorna IP e registros DNS.

## **dig**
Ferramenta avançada para consulta de DNS, exibindo detalhes sobre resolução de nomes.
Exemplo: dig google.com – mostra registros DNS do domínio google.com.

## **netstat**
Exibe conexões de rede ativas, tabelas de roteamento e estatísticas.
Exemplo: netstat -tuln – lista portas TCP e UDP abertas.

## **traceroute**
Exibe o caminho percorrido por pacotes até um destino.
Exemplo: traceroute google.com – mostra os saltos até o domínio google.com.

## **nmap**
Ferramenta de varredura de rede que detecta hosts e serviços ativos.
Exemplo: nmap -sS 192.168.1.1 – escaneia portas TCP de forma stealth.

## **nikto**
Scanner de vulnerabilidades para servidores web.
Exemplo: nikto -h http://example.com – busca vulnerabilidades no site.

## **fierce**
Scanner de DNS usado para enumeração de subdomínios e redes.
Exemplo: fierce -dns example.com – enumera subdomínios do domínio.

## **dirb**
Realiza brute force de diretórios e arquivos ocultos em servidores web.
Exemplo: dirb http://example.com/ – busca por caminhos ocultos.

## **apt**
Gerenciamento de pacotes no sistema (ex. APT em Debian).
Exemplo:
- **Instalar**: sudo apt install nmap
- **Atualizar**: sudo apt update
- **Upgrade**: sudo apt upgrade
- **Remover**: sudo apt remove nmap

## **find**
Busca arquivos e diretórios com critérios variados.
Exemplo: find / -name "senha.txt" – busca por arquivos com esse nome.

## **grep**
Filtra conteúdo com base em padrões (útil para logs e arquivos grandes).
Exemplo: grep "ERROR" /var/log/syslog – mostra linhas com "ERROR".

## **ifconfig**
Mostra ou configura interfaces de rede.
Exemplo: ifconfig eth0 – exibe detalhes da interface eth0.

## Aprender o básico de expressões regulares
Expressões regulares (regex) são padrões usados para buscar ou substituir textos.
Exemplo: grep -E '^user[0-9]+' users.txt – encontra linhas começando com "user" seguido de números.

## **start and stop services**
Comandos para iniciar/parar/reiniciar serviços no sistema.
Exemplo:
- Iniciar: sudo systemctl start apache2
- Parar: sudo systemctl stop apache2
- Reiniciar: sudo systemctl restart apache2

## **Compreensão básica de /opt, /tmp e diretórios de logs (/var/log)**

- /opt: diretório usado para instalar softwares adicionais.
- /tmp: arquivos temporários, normalmente apagados após reboot.
- /var/log: armazena arquivos de log do sistema e de serviços.

Exemplo: cat /var/log/auth.log – visualiza tentativas de autenticação no sistema.

## Executar scripts em diversas linguagens (Python, Ruby, Go, etc.)
Saber rodar scripts básicos em múltiplas linguagens é essencial para automatizar tarefas.

Exemplos:
Python: python3 script.py
Ruby: ruby script.rb
Go: go run script.go
