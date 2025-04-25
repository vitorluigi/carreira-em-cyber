# Computação em Nuvem e Cibersegurança

A Computação em Nuvem está cada vez mais presente em diversos setores - da indústria à saúde, passando por fintechs e startups. Para profissionais de cibersegurança, compreender o funcionamento da nuvem deixou de ser um diferencial e passou a ser uma habilidade mandatória.

A seguir, compartilho os **principais tópicos de estudo**, suas descrições e sugestões de **materiais complementares gratuitos em inglês/português** para se aprofundar.

---
## Livros recomendados

- [Cloud Computing for Dummies](https://a.co/d/g6G1vI9) – Conceitos base ideal para quem está começando  
- [AWS em Ação](https://a.co/d/5XAHxRw) – Ótima referência prática sobre uso da AWS em projetos reais

---

## Vídeos Recomendados

- [Flexmind – YouTube Cloud Security Playlist (legendas)](https://www.youtube.com/@FlexMindLearning/playlists)
- [AWS Brasil – Canal oficial com aulas práticas em português](https://www.youtube.com/@AWSBrasil)
- [Inside a Cloud Data Center (vídeo legendado)](https://www.youtube.com/watch?v=ae_DKNwK_ms)

---

## Cursos Recomendados
- [Introdução a Cloud Computing pela IBM no Coursera](https://www.coursera.org/learn/introduction-to-cloud)
- [Master Program em Cloud Computing](https://www.edx.org/micromasters/usmx-umgc-cloud-computing)
- [Fundamentos de AWS - Udemy (gratuito)](https://www.udemy.com/course/fundamentos-da-aws/)
- [Fundamentos do Azure - Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/azure-fundamentals/)
- [Google Cloud Fundamentals - Coursera com legendas em português](https://www.coursera.org/learn/gcp-fundamentals)

---

## 1. Provedores de Nuvem (Cloud Providers) - AWS, Azure, GCP

Estude e se especialize ao menos um dos principais provedores de nuvem:
- **AWS (Amazon Web Services)**
- **Microsoft Azure**
- **Google Cloud Platform (GCP)**

## 2. Modelos de Serviço e Implantação

- **SaaS, PaaS, IaaS**: Compreenda como diferentes serviços são oferecidos.
- **Modelos de Implantação**: Pública, privada, híbrida e multicloud.

**Material de apoio:**
- [Repositório com extensa lista de e-books para Iniciantes](https://github.com/cloudcommunity/Free-Books)

## 3. Responsabilidade Compartilhada (Shared Responsibility Model)

É fundamental entender até onde vai a **responsabilidade do provedor** de nuvem e onde começa a **sua responsabilidade ou da sua organização**, especialmente em termos de segurança, configurações e dados.

- [Artigo da AWS explicando o modelo](https://aws.amazon.com/pt/compliance/shared-responsibility-model/)

## 4. IAM (Gerenciamento de Identidade e Acesso)
Dica: As provas de certificação dos principais provedores de Cloud focam muito em IAM.

- Gerenciamento de usuários, funções, permissões e políticas.
- Princípios como menor privilégio, autenticação multifator (MFA) e segregação de funções.

**Material de apoio:**
- [Guia IAM da AWS em português](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/introduction.html)
- [Start with GCP IAM official doc](https://cloud.google.com/iam/docs/overview)
- [Usando IAM de forma segura](https://cloud.google.com/iam/docs/using-iam-securely)

## 5. Microsserviços e Containers

Estude como os sistemas distribuídos modernos utilizam **microsserviços** e **containers** (Docker, Kubernetes) e os desafios de segurança atrelados.

- [Segurança em Containers - boas práticas, dicas, pontos de atenção](https://www.youtube.com/watch?v=2sZZmiGEPPo)

## 6. Criptografia e Proteção de Dados na Nuvem

- Criptografia em repouso e em trânsito
- KMS (Key Management Service)
- Controle de acesso a dados sensíveis

**Material de apoio:**

- [Artigo "Criptografia de dados na segurança em nuvem - Como funciona?"](https://tivit.com/criptografia-de-dados/)
- [Google Cloud Key Management Service (KMS)](https://medium.com/@habbema/google-cloud-key-management-service-kms-f45a2680207e)

## 7. Redes em Nuvem (Cloud Networking)

Entenda:
- VPCs (Virtual Private Cloud), sub-redes, gateways, balanceadores de carga, grupos de segurança, VPNs e NAT
- Segurança de perímetro e segmentação de rede

**Material de apoio:**

- [AWS re:Invent 2022 - Dive deep on AWS networking infrastructure - NET402](https://www.youtube.com/watch?v=HJNR_dX8g8c)
- [Introdução a AWS Networking](https://www.youtube.com/watch?v=XZbvQWkpJTI&pp=ygUOYXdzIG5ldHdvcmtpbmc%3D)

## 8. Fundamentos adicionais importantes

- Governança e Compliance em Nuvem: Conheça normas como ISO 27001, GDPR, LGPD e as boas práticas de governança em ambientes cloud.
- Zero Trust Architecture: A arquitetura moderna de segurança assume que nenhuma entidade é confiável por padrão.
- DevSecOps: Segurança integrada ao pipeline de desenvolvimento.

**Material de apoio:**

- [DevSecOps Learnig Path](https://www.cloudskillsboost.google/paths/76?locale=pt_BR)
- [LGPD para administradores de rede - YouTube](https://www.youtube.com/watch?v=Dwx5D4S1a6k&pp=ygUTbGdwZCBlcXVpcGVzIGRlIHRpIA%3D%3D)
