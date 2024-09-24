# 1. INTRODUÇÃO

A saúde pública no Brasil tem passado por transformações significativas nas últimas décadas, com melhorias observadas nos indicadores de mortalidade e qualidade dos cuidados prestados. Desde a década de 1940, o país registra uma redução contínua nos níveis de mortalidade, um reflexo da transição epidemiológica, marcada pela diminuição das doenças infectocontagiosas e o aumento das doenças crônicas não transmissíveis, particularmente em adultos e idosos (CALAZANS; GUIMARÃES; NEPOMUCENO, 2023).

Essas mudanças revelam a importância de uma **gestão hospitalar eficiente**, que seja capaz de acompanhar essas transformações demográficas e epidemiológicas. Em 2023, o Brasil registrou a menor taxa de mortalidade infantil e fetal por causas evitáveis dos últimos 28 anos, com 202 mil mortes, representando uma redução de 62% em comparação a 1996 (BRASIL, 2024). Esses avanços são atribuídos à melhoria nos cuidados durante a gestação e ao aumento das ações preventivas, evidenciando o impacto positivo de uma gestão hospitalar eficaz.

No entanto, apesar desses progressos, a mortalidade hospitalar, especialmente em instituições públicas, continua a ser um desafio, muitas vezes associada à falta de monitoramento eficaz e ao uso inadequado de ferramentas tecnológicas para a gestão de riscos e a alocação de recursos.

O **Objetivo de Desenvolvimento Sustentável 3 (ODS 3)** da Organização das Nações Unidas (ONU) visa assegurar uma vida saudável e promover o bem-estar para todas as idades. No contexto brasileiro, esse objetivo está diretamente relacionado à necessidade de melhorar a gestão hospitalar, utilizando ciência de dados e tecnologia como ferramentas para reduzir a mortalidade hospitalar.

O uso de **dashboards informacionais** e análises preditivas permite que os gestores hospitalares tomem decisões mais assertivas e antecipem possíveis complicações, promovendo uma intervenção mais rápida e eficaz.

Este projeto propõe desenvolver uma plataforma de gestão hospitalar baseada em **ciência de dados**, visando reduzir a mortalidade hospitalar em instituições públicas. A plataforma integrará ferramentas de análise preditiva e colaborativa, permitindo que gestores de saúde monitorem em tempo real as principais causas de mortalidade e compartilhem boas práticas por meio de fóruns dedicados. A proposta é que, por meio dessa plataforma, a gestão hospitalar no Brasil se torne mais proativa e colaborativa, resultando em uma melhoria significativa na qualidade dos cuidados e na redução da mortalidade.

## 1.2. Problema

A mortalidade hospitalar, especialmente em instituições públicas, é um desafio persistente no Brasil, muitas vezes associada à ausência de monitoramento eficaz e à subutilização de ferramentas tecnológicas. A gestão hospitalar reativa, sem o uso adequado de ciência de dados, impede a antecipação de riscos, resultando em uma qualidade de cuidado comprometida e maiores taxas de mortalidade.

Este projeto propõe a criação de uma plataforma inovadora, baseada em **dados preditivos e colaborativos**, para otimizar a gestão hospitalar, monitorar as principais causas de mortalidade e promover a troca de boas práticas entre gestores de saúde. Com isso, busca-se uma abordagem mais proativa e integrada para a redução da mortalidade hospitalar e a melhoria da eficiência dos cuidados prestados.

## 1.3. Hipóteses

- A utilização de uma plataforma de gestão hospitalar baseada em ciência de dados pode reduzir significativamente a mortalidade hospitalar.
- O uso de dashboards e análises preditivas auxiliará os gestores a tomar decisões mais assertivas.
- A criação de um fórum para troca de boas práticas entre profissionais de saúde otimizará os processos hospitalares.

## 1.4. Objetivo

O objetivo principal deste projeto é reduzir a mortalidade hospitalar em instituições públicas por meio do desenvolvimento de uma plataforma de gestão hospitalar que integre **ciência de dados**, **análises preditivas** e **dashboards informacionais**. Essa ferramenta visa apoiar os gestores na antecipação de riscos e na tomada de decisões mais assertivas, promovendo uma gestão proativa e eficiente dos recursos hospitalares.

### 1.4.1 Objetivos específicos

- Reduzir a mortalidade hospitalar.
- Proporcionar ferramentas de gestão baseadas em dados.
- Promover a colaboração entre profissionais de saúde.
- Implementar análises preditivas para antecipação de riscos.
- Melhorar a qualidade do atendimento hospitalar.
- Garantir a segurança dos dados.
- Criar um ambiente colaborativo entre gestores e equipes de saúde.

## 1.5. Justificativa

A mortalidade em hospitais públicos é um problema grave no Brasil, muitas vezes relacionada à ausência de monitoramento e gestão adequados. Este projeto justifica-se pela necessidade de integrar **ciência de dados** na gestão hospitalar, visando otimizar o uso de recursos e melhorar a eficiência dos cuidados prestados. Além disso, o projeto está alinhado com o **ODS 3 da ONU**, que visa promover saúde e bem-estar para todos.

# 2. REFERENCIAL TEÓRICO

## 2.1. Objetivo de Desenvolvimento Sustentável 3 e Saúde Pública

O **Objetivo de Desenvolvimento Sustentável 3 (ODS 3)** estabelecido pela Organização das Nações Unidas (ONU) visa assegurar uma vida saudável e promover o bem-estar para todas as idades até 2030. Entre os seus objetivos principais estão a redução da mortalidade infantil, a erradicação de doenças transmissíveis, a promoção da saúde mental e a redução da mortalidade prematura por doenças não transmissíveis através da prevenção e tratamento (NAÇÕES UNIDAS NO BRASIL, 2024).

No Brasil, apesar dos avanços significativos, como a redução da mortalidade infantil e fetal por causas evitáveis, os desafios permanecem, especialmente devido às desigualdades regionais e às deficiências estruturais do sistema de saúde (CALAZANS; GUIMARÃES; NEPOMUCENO, 2023).

## 2.2. Gestão Hospitalar e o Uso de Dados

A **gestão hospitalar eficiente** é essencial para garantir a qualidade dos cuidados e a otimização dos recursos em instituições de saúde, especialmente nas públicas. Um dos grandes desafios dessa gestão é o uso inadequado de tecnologias de monitoramento e a falta de planejamento contínuo, o que pode resultar em diagnósticos tardios, tratamentos inadequados e, consequentemente, em maiores taxas de mortalidade (VASCONCELOS; SILVA, 2021).

## 2.3. Análises Preditivas na Saúde

As **análises preditivas** são uma das ferramentas mais poderosas quando se trata de otimizar a gestão hospitalar e reduzir a mortalidade. Essas análises utilizam algoritmos de **aprendizado de máquina** e **inteligência artificial** para prever desfechos clínicos e identificar padrões de risco, baseando-se tanto em dados históricos quanto em dados em tempo real.

# 3. METODOLOGIA

## 3.1. Coleta e Integração de Dados

Os dados utilizados serão provenientes de fontes confiáveis, como empresas especializadas em **Diagnosis Related Groups (DRG)**, oferecendo informações anonimizadas sobre internações hospitalares e causas de mortalidade.

### Desenvolvimento de APIs de Integração

- Serão criadas APIs para a coleta e integração contínua de dados de diferentes fontes, consolidando as informações para posterior análise.

### Armazenamento Seguro de Dados

- Implementação de um sistema de armazenamento seguro para garantir a confidencialidade, integridade e disponibilidade dos dados.

# 4. RECURSOS

## 4.1. Pessoal Necessário

- **Gestores de Projeto**: Responsáveis pela coordenação geral, planejamento estratégico e monitoramento do progresso do projeto.
- **Desenvolvedores de Software**: Especialistas em programação e desenvolvimento, encarregados de construir e manter as funcionalidades do sistema.
- **Cientistas de Dados**: Focados na coleta, análise e interpretação de grandes volumes de dados.
- **Especialistas em Segurança da Informação**: Responsáveis pela proteção de dados sensíveis.
- **Designers de UX/UI**: Criadores de interfaces intuitivas, focados em melhorar a experiência dos usuários.

## 4.2. Seleção e Alocação de Software

- **Plataformas de Desenvolvimento**: Ferramentas e ambientes como frameworks para desenvolvimento web e linguagens de programação.
- **Ferramentas de Análise de Dados**: Softwares como Python, R, ou plataformas de **Machine Learning**.
- **Sistemas de Monitoramento e Alertas**: Ferramentas para monitoramento em tempo real como **Prometheus**, **Grafana**, ou **Splunk**.

# 5. CRONOGRAMA

# REFERÊNCIAS

- BRASIL. Mortalidade infantil e fetal por causas evitáveis no Brasil é a menor em 28 anos. Disponível em: [https://www.gov.br/saude/pt-br/assuntos/noticias/2024/marco/mortalidade-infantil-e-fetal-por-causas-evitaveis-no-brasil-e-a-menor-em-28-anos](https://www.gov.br/saude/pt-br/assuntos/noticias/2024/marco/mortalidade-infantil-e-fetal-por-causas-evitaveis-no-brasil-e-a-menor-em-28-anos). Acesso em: 08 set. 2024.
