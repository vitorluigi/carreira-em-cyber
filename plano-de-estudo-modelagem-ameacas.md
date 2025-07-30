## Modelagem de Ameaças

> ⚠️ **IMPORTANTE:**  
> Se você trabalha com segurança de produtos, segurança de aplicações ou engenharia de segurança, este plano de estudos é mais essencial para você do que para outros profissionais da área. No entanto, recomenda-se que todo profissional de segurança tenha uma boa compreensão dos fundamentos de modelagem de ameaças.

![Plano de Estudos de Modelagem de Ameaças](images/threat_modelling.png)

> 💡 **Nota:**  
> Leva cerca de 2-3 meses para adquirir um bom entendimento de Threat Modelling com alguma experiência prática.

### O que é Modelagem de Ameaças

Modelagem de ameaças é uma abordagem estruturada para analisar a segurança de uma aplicação, permitindo identificar, quantificar e tratar riscos de segurança associados.  
Com detalhes sobre ameaças e ataques prováveis, a organização toma decisões mais eficazes sobre como priorizar iniciativas de segurança.  
Além disso, as decisões de aceitação de risco são mais informadas e alinhadas aos objetivos do negócio.

> 💡 **DICA:**  
> Além deste material, dê uma revisada no [OWASP Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html) para entendimento básico.

Em resumo:

- **Modelagem de ameaças é o processo** de identificar, analisar e mitigar ameaças de segurança potenciais a um sistema ou organização.
- Envolve identificar os ativos a serem protegidos, analisar as ameaças potenciais e desenvolver estratégias para mitigá-las ou eliminá-las.
- Quanto mais cedo a modelagem for realizada, melhores os resultados, mas é comum encontrar ambientes estabelecidos e com aplicações em produção que também pode ser necessário realizar a modelagem de ameaças para maior entendimento da solução pelo engenheiro de segurança.

### Objetivos da Modelagem de Ameaças

1. Identificar os limites de confiança do sistema
2. Reconhecer os atores que interagem dentro e fora desses limites
3. Entender os fluxos de informação entre os limites
4. Avaliar a persistência das informações dentro e fora dos limites
5. Mapear ameaças que transgridem os limites de confiança
6. Identificar vulnerabilidades nos limites acessados por atores e nos fluxos de informação
7. Conhecer os agentes de ameaça que podem explorar essas vulnerabilidades
8. Avaliar o impacto da exploração
9. Criar uma árvore de decisão para tratamento de riscos

## Conceitos e Termos de Modelagem de Ameaças

![Conceitos de Modelagem de Ameaças](images/mapa_mental_modelagem.png)

### Por que fazer modelagem de ameaças? :point_up:

+ **Identificação proativa de ameaças:** Detecção antecipada de possíveis falhas.
+ **Redução de Custos:** Correções mais baratas quando feitas no início.
+ **Priorização:** Foco nas vulnerabilidades mais críticas.
+ **Compreensão do sistema:** Melhor entendimento das interações e fluxos de dados.

### Metodologias famosas de modelagem de ameaças

1. STRIDE (a mais comum)
2. CVSS (ajuda a pontuar com score os riscos identificados)
3. Lista de ataques (útil para o time de offensive security criar um baseline de teste daquele escopo)
4. PASTA (outra metodologia de modelagem de ameaças)
5. LINDDUN (foco em privacidade)

#### Resultados esperados

+ **Diagramas de Sistema:** Ilustrações completas da arquitetura e fluxos.
+ **Requisitos de Segurança:** Critérios para proteger o sistema.
+ **Lista de Ameaças:** Ameaças com suas estratégias de mitigação.
+ **Demonstração da exploração:** Demosntração realizada através de pentest da explorabilidade do risco (quando aplicável).

## Áreas cobertas pela modelagem

### Ativos

Identificação de dados, sistemas, pessoas e hardware que precisam de proteção.

### Ameaças

Identificação de possíveis ameaças com base em brainstorms, relatórios e especialistas.

### Probabilidade e Impacto

Avaliação de cada ameaça em termos de risco e impacto para priorização.

### Estratégias de Mitigação

Técnicas para reduzir ou eliminar riscos, tanto técnicas (validação de domínio por CSP, uso de rate_limit, validação de parâmetros de entrada no backend, uso de EDR em servidores, etc) quanto não técnicas (treinamentos, políticas).

### Testes e Validação

Verificação da eficácia das estratégias de mitigação. Normalmente crie tarefas para os times de desenvolvimento com os requisitos para ir acompanhando.

### Revisão e Atualização

Modelos devem ser revisados periodicamente para refletir novos cenários.

## Passos para Executar Modelagem de Ameaças

1. **Definir o escopo do sistema e ativos.**
2. **Identificar ameaças.**
3. **Analisar probabilidade e impacto.**
4. **Desenvolver estratégias de mitigação.**
5. **Testar e validar as soluções.**
6. **Revisar e atualizar periodicamente.**

> 💡 **DICA:**  
> Pratique com Apache Juiceshop, WordPress na AWS, ou aplicação com APIs e integrações.

### Diagrama de Exemplo (Amazon Elasticsearch) :tada:

![Exemplo de Modelagem de Ameaças](./images/Amazon_ElasticSearch_Basic_TM.png)

### Próximos Passos

Após entender e praticar:

1. Como aplicar modelagem no SDLC existente?
2. Quais os desafios técnicos esperados?
3. Como torná-la escalável?
4. Como lidar com diferentes tipos de aplicação?
5. Qual metodologia adotar na sua organização?
6. Como validar os achados?
7. Conheça e aplique:
   - modelagem de ameaças ágil
   - modelagem automatizada
   - modelagem rápida
   - modelagem avançada

### Ferramentas para Explorar

1. [OWASP Threat Dragon](https://www.threatdragon.com/#/)
2. [Microsoft Threat Modeling Tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool)
3. [STRIDE GPT](https://stridegpt.streamlit.app/)
4. [Threagile](https://run.threagile.io/)
5. [PyTM](https://github.com/izar/pytm)
6. [draw.io](https://www.drawio.com/)

### Recursos para Aprender e Praticar

1. https://owasp.org/www-project-threat-dragon/
2. https://owasp.org/www-community/Threat_Modeling
3. https://www.simplilearn.com/what-is-threat-modeling-article
4. https://www.synopsys.com/glossary/what-is-threat-modeling.html
5. https://www.eccouncil.org/threat-modeling/
6. https://komsr3ll.medium.com/threat-modelling-attack-vectors-4f4989336588
7. [Mindmap Red Team](https://www.oreilly.com/library/view/hands-on-red-team/9781788995238/55d89c3e-e3f2-414a-872f-37620e9ab43f.xhtml)
8. [MITRE Cyber Threat Modeling](https://www.mitre.org/sites/default/files/2021-11/prs-18-1174-ngci-cyber-threat-modeling.pdf)
9. https://redcanary.com/blog/threat-modeling/
10. https://www.jemurai.com/2020/11/10/risk-and-threat-modeling-with-mind-maps/
11. https://shellsharks.com/threat-modeling
12. [Awesome Threat Modeling (GitHub)](https://github.com/hysnsec/awesome-threat-modelling)
13. [Podcast de Threat Modeling - Chris Romeo](https://open.spotify.com/show/4q9BxNrRb0NWnLBpSmNqoP)
14. [Post no LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7209798162687873026/)
15. [Certificação: Certified Threat Modeling Professional](https://www.practical-devsecops.com/certified-threat-modeling-professional/)
16. [Kubernetes Threat Modeling](https://www.trendmicro.com/vinfo/in/security/news/security-technology/a-deep-dive-into-kubernetes-threat-modeling)
17. [AWS S3 Threat Modeling](https://controlcatalog.trustoncloud.com/dashboard/aws/s3)

### Vídeos :bulb:

1. https://youtu.be/h_BC6QMWDbA  
2. https://youtu.be/GqmQg-cszw4  
3. https://youtu.be/fggB70PxhmA  
4. https://youtu.be/lnvYlg4HOX4  
5. https://youtu.be/GuhIefIGeuA  
6. https://youtu.be/CjzdC0Eerfw  
7. [Curso Pago na Udemy: STRIDE - Taimur](https://www.udemy.com/course/threat-modeling-using-stride-masterclass/?couponCode=IND21PM)

### Livros :books:

1. [Threat Modeling: Design for Security - Adam Shostack](https://amzn.to/3zfKefb)  
2. [Threat Modeling - Izar Tarandach](https://amzn.to/4gEgbif)

