# O que é DevSecOps?
DevSecOps integra a segurança em todas as etapas do ciclo de vida de desenvolvimento e operações de software. Em vez de esperar até o final do desenvolvimento para verificar problemas de segurança, como era comum até meados dos anos 2000. O DevSecOps garante que a segurança seja considerada durante todo o processo de desenvolvimento, testes e implantação. A ideia é incorporar a segurança ao processo, tornando-a uma responsabilidade compartilhada entre as equipes de desenvolvimento, segurança e operações.

__Exemplo:__
Exemplo:
Imagine uma equipe desenvolvendo uma aplicação web. Em uma abordagem tradicional, os testes de segurança podem ocorrer apenas quando o aplicativo está quase pronto. No DevSecOps, a segurança é integrada desde o início, com ferramentas automatizadas escaneando o código em tempo real à medida em que é escrito, e as equipes de segurança trabalhando lado a lado com os desenvolvedores para corrigir rapidamente eventuais bugs de segurança.

## O que é CI/CD em DevOps?
Uma das práticas fundamentais no DevOps é o CI/CD, que significa Integração Contínua (CI) e Entrega Contínua (CD). Essas práticas permitem que o código seja desenvolvido, testado e implantado de forma automatizada, garantindo mais agilidade e qualidade no processo de desenvolvimento.

![Diagrama DevOps](https://github.com/vitorluigi/carreira-em-cyber/raw/main/images/devsecops-diagrama.png)
---
## Livros Recomendados 

- [Learning DevSecOps: A Practical Guide to Processes and Tools](https://amzn.in/d/6g2jdBD) [EN] - Apresenta pré-requisitos que conduzem ao sucesso de implementações de segurança no ciclo de desenvolvimento por meio de boas práticas.
- [Dev-Sec-Ops com Jenkins: Criando uma esteira de entrega contínua](https://a.co/d/0LABR1m) [PT] - Exemplifica como construir uma esteira (pipeline) DevSecOps utilizando ferramentas opensource como Jenkins e SonarQube para entrega contínua (CI/CD).
- [DevSecOps na Vida Real: O Guia que Você Deveria Ter Lido Antes](https://a.co/d/fpM4QLZ) [PT] - Prática profunda com ferramentas open source, laboratório real e IA para quem vive o caos de verdade.

---
## Vídeos recomendados

- [DevSecOps (Segurança no Ciclo de Desenvolvimento de Software) // Dicionário do Programador](https://www.youtube.com/watch?v=CCp30BD9uRo)
- [Qual é a diferença entre DevOps e DevSecOps?](https://www.youtube.com/watch?v=pHbMoCSsEfU)
- [TI Para Concursos | DevOps e DevSecOps](https://www.youtube.com/watch?v=PnZmFnOrTv8)

---
## Cursos recomendados

- [DevSecOps Fundamentals on Udemy](https://www.udemy.com/course/devsecops-fundamentals/) [EN] - Um curso para iniciantes entenderem e implementarem práticas de DevSecOps no desenvolvimento de software.
- [DevSecOps com GitHub Actions](https://www.udemy.com/course/devsecops-com-github-actions/?couponCode=ST16MT230625A) [PT] - Como usar DevSecOps na prática, com GitHub Actions, e deploy na AWS.
- [DevSecOps & DevOps with Jenkins, Kubernetes, Terraform & AWS](https://www.udemy.com/course/devsecops-with-terraform-kubernetes-jenkins-aws/?couponCode=ST16MT230625A) [EN] - Implementar SAST, SCA e DAST no Jenkins DevSecOps Pipeline a partir do zero e configurar infra usando Terraform e Kubernetes na AWS.
- [DevSecOps by KodeCloud](https://kodekloud.com/courses/devsecops) [EN] - Um curso prático sobre o domínio de ferramentas e metodologias DevSecOps com laboratórios práticos. 

---
## Papéis e Responsabilidades

- Implementar ferramentas de segurança nos pipelines de integração e entrega contínua (CI/CD) para escanear automaticamente vulnerabilidades e problemas de segurança durante o desenvolvimento.
- Garantir que os desenvolvedores sejam treinados para escrever código seguro e estejam cientes das vulnerabilidades mais comuns (ex: Injeção de SQL, Cross-Site Scripting).
- Automatizar os testes de segurança (ex: Testes Estáticos de Segurança de Aplicações - SAST, Testes Dinâmicos de Segurança de Aplicações - DAST) como parte do processo regular de desenvolvimento.
- Monitorar aplicações em produção em tempo real para identificar problemas de segurança e garantir que correções (patches) sejam aplicadas rapidamente quando vulnerabilidades forem detectadas.
- Incentivar a colaboração entre as equipes de desenvolvimento, segurança e operações, garantindo que a segurança seja uma responsabilidade compartilhada — e não uma etapa posterior do processo.

## Skills Necessárias

- **Ferramentas de automação**: Experiência com ferramentas de CI/CD como Jenkins, GitLab CI, CircleCI e automação de varreduras de segurança dentro do pipeline de desenvolvimento.
- **Ferramentas de teste de segurança**: Conhecimento de ferramentas de SAST, DAST e análise de composição de software (SCA), como SonarQube, Checkmarx ou OWASP ZAP, para identificar vulnerabilidades precocemente no ciclo de desenvolvimento.
- **Codificação segura**: Compreensão dos princípios de codificação segura e capacidade de ensinar os desenvolvedores a programar de forma segura.
- **Colaboração e comunicação**: Habilidade de trabalhar em conjunto com equipes de desenvolvimento, segurança e operações para garantir que a segurança esteja incorporada em todas as fases do desenvolvimento de software.
- **Infraestrutura como Código (IaC)**: Garantir a segurança da infraestrutura em nuvem automatizando a criação e o gerenciamento com ferramentas como Terraform ou AWS CloudFormation, assegurando que a infraestrutura seja segura por design.

---
# 🛡️ Ferramentas DevSecOps

## (SAST) Teste Estático de Segurança de Aplicações

- **SonarQube**: Ferramenta de análise estática de código que suporta várias linguagens de programação.
- **Bandit**: Linter de segurança para código Python.
- **Brakeman**: Scanner de segurança para aplicações Ruby on Rails.
- **SpotBugs**: Ferramenta de análise estática para encontrar vulnerabilidades de segurança em código Java.
- **Semgrep**: Ferramenta leve de análise estática que suporta várias linguagens e frameworks.
- **Coverity**: Análise abrangente de código estático para detectar defeitos e vulnerabilidades em software.
- **Git Secrets**: Detecta segredos e informações sensíveis em commits do Git e impede que sejam incluídos.


## (DAST) Teste Dinâmico de Segurança de Aplicações

- **OWASP ZAP**: Ferramenta open-source para encontrar vulnerabilidades em aplicações web.
- **Nikto**: Scanner de servidores web que detecta versões desatualizadas e problemas de segurança.
- **Arachni**: Scanner de segurança para aplicações web, usado na identificação de vulnerabilidades.
- **Burp Suite**: Plataforma integrada para testes de segurança em aplicações web.
- **Akto e Levo (API Security)**: Ferramentas específicas para escanear e proteger APIs.

## (SCA) Análise de Composição de Software (libs)

- **Snyk**: Plataforma de segurança que escaneia dependências open-source em busca de vulnerabilidades conhecidas.
- **OWASP Dependency-Check**: Ferramenta open-source que identifica vulnerabilidades divulgadas publicamente em dependências.
- **Dependabot**: Verifica automaticamente vulnerabilidades em dependências e cria pull requests para atualizá-las.
- **Retire.js**: Scanner que ajuda a identificar vulnerabilidades conhecidas em bibliotecas JavaScript.
- **npm audit**: Ferramenta de auditoria de segurança para aplicações Node.js, focada em vulnerabilidades de pacotes.

## Segurança para Containers

- **Clair**: Ferramenta open-source para análise estática de vulnerabilidades em containers.
- **Trivy**: Scanner de vulnerabilidades abrangente para containers, Kubernetes e IaC.
- **Checkov**: Ferramenta de análise estática de infraestrutura como código para Terraform, Kubernetes, entre outros.
- **Kube-bench**: Verifica se clusters Kubernetes estão configurados de acordo com as melhores práticas de segurança.
- **Kubesec**: Ferramenta para proteger recursos do Kubernetes escaneando arquivos YAML.
- **Hadolint**: Linter para Dockerfile que verifica boas práticas e vulnerabilidades potenciais.

## Segurança para Infraestrutura como Código (IaC)

- **Terraform-grunt**: Ferramenta para testar a segurança de configurações Terraform.
- **ScoutSuite**: Ferramenta de auditoria de segurança multi-cloud para infraestrutura em nuvem.
- **KICS (Checkmarx)**: Ferramenta open-source para escanear IaC em busca de vulnerabilidades.
- **TFLint**: Linter para detectar erros e problemas de segurança em templates Terraform.
- **Prowler**: Ferramenta de segurança para verificar conformidade com boas práticas na AWS.
- **Terrascan**: Analisador de código estático para IaC que detecta vulnerabilidades.

## Conformidade e Governança

> Conceito de "política como código" e "conformidade como código" sob a perspectiva DevOps e DevSecOps.

- **Chef InSpec**: Framework para definir e testar políticas de segurança e conformidade como código.
- **Open Policy Agent (OPA)**: Motor de políticas de uso geral para aplicação de regras em toda a stack.
- **HashiCorp Sentinel**: Framework de política como código integrado aos produtos da HashiCorp.
- **AWS Config**: Monitora e audita configurações de recursos AWS para manter a conformidade.
- **OpenSCAP**: Conjunto de ferramentas open-source para auditoria de conformidade com padrões de segurança.

## Painéis de Segurança e Análise

- **DefectDojo**: Ferramenta open-source para gestão de vulnerabilidades em aplicações.
- **ELK (Elasticsearch, Logstash e Kibana)**: Stack para centralização de logs e análise.
- **OWASP Dependency Track**: Monitoramento contínuo de vulnerabilidades em dependências de terceiros.
- **JFrog XRay**: Ferramenta de análise de componentes para detecção de vulnerabilidades e problemas de conformidade de licença.
