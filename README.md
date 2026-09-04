# FieldOps — Gestão de Projetos

Este repositório reúne os artefatos, atividades e documentos desenvolvidos na disciplina de **Gestão de Projetos**, utilizando o **FieldOps — Plataforma de Inspeção em Campo** como objeto de aplicação prática dos conceitos de gerenciamento de projetos.

O objetivo do repositório não é somente registrar o desenvolvimento de uma solução de software, mas documentar sua evolução sob a perspectiva de **planejamento, execução, acompanhamento, controle e encerramento de um projeto**, considerando aspectos como escopo, prazo, qualidade, riscos, stakeholders, comunicação, recursos e integração.

---

## Sobre o projeto

O **FieldOps** é uma plataforma digital voltada ao planejamento, execução, acompanhamento e revisão de inspeções técnicas realizadas em campo.

A solução busca substituir processos descentralizados baseados em formulários impressos, planilhas, mensagens e registros informais por um fluxo digital integrado e rastreável.

A plataforma é composta por:

* aplicativo mobile destinado principalmente aos técnicos de campo;
* interface administrativa web para supervisores e administradores;
* API REST responsável pela centralização das regras de negócio e integração das aplicações;
* infraestrutura de dados responsável pela persistência central, armazenamento local, evidências e auditoria.

O fluxo principal compreende desde a preparação e atribuição de uma inspeção até sua execução em campo, sincronização, revisão e aprovação final.

---

## FieldOps sob a perspectiva de Gestão de Projetos

Na Gestão de Projetos, um projeto é entendido como um esforço temporário realizado para gerar um produto, serviço ou resultado único.

Nesse contexto, o **FieldOps representa o produto resultante do projeto**, enquanto todas as atividades necessárias para planejá-lo, desenvolvê-lo, integrá-lo, validá-lo e entregá-lo constituem o projeto propriamente dito.

O desenvolvimento possui:

* **caráter temporário**, por possuir período determinado para realização;
* **resultado único**, representado pela entrega da plataforma FieldOps;
* **objetivos definidos**, relacionados à digitalização e melhoria do processo de inspeções;
* **recursos limitados**, incluindo equipe, tecnologias, infraestrutura e tempo disponível;
* **riscos e restrições**, que precisam ser identificados e acompanhados;
* **stakeholders**, com diferentes responsabilidades, necessidades e níveis de influência sobre o projeto.

---

## Objetivo geral

Desenvolver uma plataforma integrada capaz de apoiar todo o ciclo de inspeções técnicas realizadas em campo, desde o planejamento e atribuição das atividades até sua execução, sincronização, revisão e aprovação.

O projeto busca tornar esse processo mais **padronizado, confiável, rastreável e eficiente**, centralizando as informações produzidas durante as inspeções e garantindo sua preservação durante todo o fluxo operacional.

---

## Objetivos específicos

Entre os principais objetivos do FieldOps estão:

* digitalizar e centralizar o processo de inspeções técnicas;
* reduzir a utilização de formulários impressos, planilhas e registros descentralizados;
* padronizar as inspeções por meio de modelos e checklists;
* permitir o planejamento, agendamento e atribuição de inspeções;
* permitir que técnicos executem as atividades por meio de um aplicativo mobile;
* identificar equipamentos utilizando QR Code;
* registrar respostas, observações, fotografias, localização e não conformidades;
* possibilitar a execução das inspeções mesmo em situações de conectividade limitada;
* preservar localmente os dados ainda não sincronizados;
* realizar a sincronização das informações de forma confiável;
* evitar perda e duplicidade de registros;
* permitir o acompanhamento das inspeções por supervisores;
* possibilitar revisão, aprovação, reprovação ou solicitação de correções;
* preservar histórico e rastreabilidade das operações;
* melhorar a qualidade das informações utilizadas pelos responsáveis pela operação.

---

## Justificativa

Processos de inspeção realizados por meio de documentos impressos, planilhas e diferentes canais de comunicação dificultam a padronização e o acompanhamento das atividades.

Esse modelo pode ocasionar problemas como:

* perda de informações;
* preenchimentos incompletos;
* dificuldade para organizar evidências;
* demora na consolidação dos resultados;
* baixa rastreabilidade;
* retrabalho;
* necessidade de retorno ao local da inspeção;
* dificuldade para acompanhar não conformidades.

O FieldOps propõe integrar essas atividades em uma única solução digital.

Com isso, espera-se aumentar a confiabilidade e a qualidade das informações coletadas, melhorar a rastreabilidade das inspeções e proporcionar maior visibilidade das operações para técnicos, supervisores e administradores.

---

## Principais entregas

As principais entregas previstas para o projeto são:

### Aplicativo mobile

Aplicação utilizada principalmente pelos técnicos responsáveis pelas inspeções em campo.

Entre suas principais capacidades estão:

* consulta das inspeções atribuídas;
* execução de checklists;
* identificação de equipamentos por QR Code;
* captura de fotografias;
* registro de observações;
* registro de não conformidades;
* captura de localização;
* armazenamento local;
* funcionamento offline;
* sincronização com o servidor.

### Interface administrativa web

Aplicação voltada principalmente para supervisores e administradores.

Deverá permitir:

* gerenciamento de usuários e perfis;
* cadastro de clientes, locais e equipamentos;
* gerenciamento dos modelos de inspeção;
* agendamento e atribuição das atividades;
* acompanhamento das inspeções;
* visualização de respostas e evidências;
* acompanhamento das não conformidades;
* revisão dos resultados;
* aprovação ou reprovação das inspeções.

### API REST

Responsável por centralizar:

* autenticação;
* autorização;
* regras de negócio;
* validações;
* persistência;
* sincronização;
* auditoria;
* integração entre mobile e web.

### Infraestrutura de dados

Responsável pela persistência das informações da plataforma, armazenamento das evidências e suporte ao funcionamento offline do aplicativo.

---

## Escopo do projeto

O escopo principal contempla o seguinte ciclo:

**Configuração administrativa → Modelo de inspeção → Agendamento e atribuição → Disponibilização ao técnico → Execução em campo → Registro de respostas e evidências → Sincronização → Revisão do supervisor → Aprovação ou solicitação de correção**

O MVP deverá ser capaz de demonstrar esse fluxo de ponta a ponta.

---

## Fora do escopo inicial

Para preservar a viabilidade da primeira versão, algumas funcionalidades não fazem parte do MVP, como:

* aplicativo exclusivo para clientes;
* portal público;
* pagamento ou faturamento;
* roteirização automática de equipes;
* transmissão contínua da localização do técnico;
* chamadas de vídeo;
* armazenamento de vídeos longos;
* assinatura eletrônica com validade jurídica;
* relatórios regulatórios avançados;
* integração com ERP;
* diagnóstico automático por inteligência artificial;
* integração com sensores IoT;
* mecanismos avançados de resolução colaborativa de conflitos de sincronização.

A delimitação desses itens é importante para evitar crescimento não controlado do escopo durante a execução do projeto.

---

## Premissas

Para o planejamento do projeto, são consideradas as seguintes premissas:

* a primeira versão terá o Android como plataforma prioritária para validação mobile;
* inicialmente, o sistema será utilizado por uma organização responsável por inspeções realizadas para diferentes clientes;
* cada inspeção possuirá um técnico responsável no MVP;
* o supervisor será responsável pela revisão do resultado;
* equipamentos poderão ser identificados por QR Code;
* as inspeções serão baseadas em modelos previamente configurados;
* o aplicativo deverá preservar dados ainda não sincronizados mesmo após seu fechamento;
* após a sincronização, a API será considerada o registro oficial das informações.

---

## Restrições

O projeto possui restrições funcionais e tecnológicas que devem ser consideradas durante seu planejamento e execução.

Entre as principais estão:

* validação obrigatória da aplicação mobile em Android;
* utilização de Expo, React Native e TypeScript no aplicativo mobile;
* backend desenvolvido em Java com Spring Boot;
* comunicação entre os componentes através de API REST;
* PostgreSQL utilizado como banco de dados central;
* SQLite utilizado para persistência local no aplicativo;
* cada inspeção possuirá apenas um técnico responsável no MVP;
* revisão realizada pelo perfil de supervisor;
* utilização de modelos previamente configurados para execução das inspeções;
* preservação obrigatória dos dados ainda não sincronizados;
* priorização das funcionalidades que compõem o MVP;
* funcionalidades classificadas como fora do escopo não deverão comprometer a entrega do fluxo principal.

---

## Stakeholders

Os principais interessados no projeto são:

| Stakeholder           | Interesse no projeto                                                 |
| --------------------- | -------------------------------------------------------------------- |
| Técnicos de campo     | Executar inspeções de maneira simples, segura e eficiente            |
| Supervisores          | Planejar, acompanhar e revisar inspeções                             |
| Administradores       | Configurar e manter as informações necessárias para operação         |
| Organização operadora | Padronizar e acompanhar os serviços de inspeção                      |
| Clientes atendidos    | Receber informações confiáveis sobre as inspeções realizadas         |
| Equipe do projeto     | Planejar, desenvolver, integrar, testar e entregar a solução         |
| Docente da disciplina | Orientar e avaliar a aplicação dos conceitos de Gestão de Projetos   |
| Instituição de ensino | Acompanhar o desenvolvimento acadêmico e profissional dos estudantes |

---

## Principais riscos

Entre os riscos inicialmente identificados estão:

1. perda de dados durante a execução offline;
2. falhas durante a sincronização entre aplicativo e servidor;
3. duplicidade de registros decorrente de reenvios;
4. problemas de integração entre mobile, web, backend e banco de dados;
5. falhas no armazenamento ou envio de evidências;
6. indisponibilidade de câmera, localização ou outras permissões necessárias;
7. diferenças de comportamento entre dispositivos Android;
8. falhas de autenticação ou autorização;
9. alteração excessiva do escopo durante o desenvolvimento;
10. atrasos decorrentes de dependências entre diferentes frentes do projeto;
11. informações incompletas ou inconsistentes registradas durante uma inspeção;
12. não conclusão de funcionalidades críticas dentro do período disponível.

Esses riscos deverão ser acompanhados ao longo do projeto, permitindo a definição de respostas preventivas ou corretivas quando necessário.

---

## Fatores críticos de sucesso

O sucesso do projeto depende principalmente de:

* conclusão do fluxo principal de inspeção de ponta a ponta;
* integração consistente entre mobile, web, API e infraestrutura de dados;
* preservação das informações registradas em situações de ausência de conexão;
* sincronização sem perda ou duplicação de dados;
* aplicação correta das regras de autenticação e autorização;
* funcionamento dos checklists e registros de evidências;
* experiência adequada para utilização do aplicativo em campo;
* possibilidade de supervisão, revisão e aprovação das inspeções;
* rastreabilidade das operações;
* atendimento aos critérios de aceitação definidos;
* execução de testes dos principais fluxos;
* comunicação eficiente entre os integrantes envolvidos no projeto.

---

# Gestão do Projeto

## Ciclo de vida

A organização do projeto considera as etapas apresentadas no ciclo de vida de gerenciamento:

### 1. Iniciação

Momento em que o projeto é formalizado e seus objetivos iniciais são estabelecidos.

Um dos principais artefatos desta etapa é o **Termo de Abertura do Projeto (TAP)**.

### 2. Planejamento

Nesta etapa são detalhados aspectos relacionados a:

* escopo;
* atividades;
* cronograma;
* recursos;
* riscos;
* stakeholders;
* comunicação;
* critérios de qualidade;
* entregas.

### 3. Execução

Corresponde à realização das atividades planejadas para produzir as entregas do projeto.

No FieldOps, envolve o desenvolvimento e integração das diferentes partes da solução.

### 4. Monitoramento e controle

O projeto deve ser acompanhado continuamente para verificar:

* andamento das atividades;
* cumprimento do escopo;
* qualidade das entregas;
* riscos;
* mudanças;
* impedimentos;
* progresso em relação ao planejamento.

### 5. Encerramento

Ao final do projeto, as entregas deverão ser validadas e o projeto formalmente encerrado, registrando resultados, desafios, decisões e lições aprendidas.

---

## Áreas de gerenciamento aplicadas

A organização do projeto considera as áreas de conhecimento trabalhadas na disciplina.

### Integração

Busca garantir que as diferentes partes do projeto sejam planejadas e conduzidas de forma coordenada.

No FieldOps, isso é especialmente relevante devido à necessidade de integração entre aplicativo mobile, interface web, backend e infraestrutura de dados.

### Escopo

Define aquilo que deverá ou não ser entregue pelo projeto.

A separação entre **MVP** e **fora do escopo** é utilizada como mecanismo para controlar a expansão das funcionalidades.

### Tempo

Envolve definição, sequenciamento e acompanhamento das atividades necessárias para realizar as entregas dentro do período disponível.

### Custos

Considera os recursos necessários para execução do projeto.

Por se tratar de um projeto desenvolvido em contexto acadêmico, não existe atualmente orçamento financeiro formal definido.

### Qualidade

Busca garantir que as funcionalidades desenvolvidas atendam aos requisitos, regras de negócio, critérios de aceitação e condições previstas para o MVP.

### Recursos

Envolve a organização das pessoas, responsabilidades, ferramentas e demais recursos necessários para execução do trabalho.

### Comunicações

Busca garantir que informações relevantes sejam compartilhadas entre os participantes do projeto de maneira clara e adequada.

### Riscos

Envolve identificar eventos que possam afetar os objetivos do projeto, analisar seus impactos e definir formas de resposta.

### Aquisições

No momento, não existem aquisições externas formalmente definidas para o projeto.

Caso sejam necessárias futuramente, deverão ser avaliadas considerando seu impacto no planejamento.

### Partes interessadas

Envolve identificar os stakeholders, compreender suas necessidades e considerar sua influência e interesse ao longo do projeto.

---

## Controle de mudanças

Mudanças são naturais durante a evolução de um projeto, porém alterações relevantes de escopo, requisitos ou arquitetura devem ser avaliadas antes de sua implementação.

Uma solicitação de mudança deve considerar, quando aplicável, seus impactos sobre:

* escopo;
* prazo;
* esforço;
* riscos;
* arquitetura;
* dependências;
* critérios de aceitação;
* entregas previstas.

O objetivo é evitar que alterações não planejadas comprometam a entrega do MVP.

---

## Critérios de sucesso do MVP

O MVP será considerado funcional quando for possível demonstrar o fluxo principal da solução, incluindo:

* configuração dos dados necessários pela interface administrativa;
* criação de um modelo de inspeção;
* criação e atribuição de uma inspeção;
* recebimento da atividade pelo técnico;
* apresentação dinâmica do checklist;
* validação dos itens obrigatórios;
* associação de fotografias aos itens;
* identificação de equipamento por QR Code;
* registro de localização quando autorizado;
* execução da inspeção sem conexão após seu carregamento;
* sincronização posterior;
* prevenção de duplicidades em reenvios;
* revisão dos resultados pelo supervisor;
* aprovação ou reprovação da inspeção;
* proteção das inspeções aprovadas contra alterações comuns;
* disponibilização da API de forma documentada.

---

# Artefatos de Gestão

## Termo de Abertura do Projeto

O **Termo de Abertura do Projeto (TAP)** formaliza a existência do projeto e registra suas principais informações iniciais.

O documento contempla aspectos como:

* objetivo;
* justificativa;
* premissas;
* restrições;
* riscos;
* stakeholders;
* prazo;
* recursos;
* fatores críticos de sucesso;
* responsáveis.

Os documentos relacionados à atividade estão organizados em:

[`Modelo 4.1/`](./Modelo%204.1/)

---

## Documentação do FieldOps

A especificação do projeto contempla documentos e artefatos relacionados a:

* visão geral;
* objetivos;
* problema;
* personas;
* perfis de usuário;
* casos de uso;
* fluxo geral;
* funcionalidades;
* regras de negócio;
* modelo de dados;
* arquitetura;
* API REST;
* aplicativo mobile;
* interface administrativa web;
* backlog do produto;
* roadmap;
* critérios de aceitação;
* Definition of Done;
* critérios de avaliação;
* decisões de escopo;
* exemplos de inspeção;
* diagramas do domínio.

Esses artefatos servem como apoio ao planejamento, desenvolvimento, acompanhamento e validação do projeto.

---

# Contexto acadêmico

Este repositório também funciona como diretório das atividades desenvolvidas durante a disciplina de **Gestão de Projetos**.

A metodologia utilizada na disciplina é baseada em **Project-Based Learning (PBL)**, permitindo aplicar os conceitos estudados em problemas e projetos concretos.

Ao longo do semestre, o projeto deverá ser analisado não apenas pelo resultado final, mas também pelo processo utilizado para chegar até ele, incluindo:

* planejamento;
* organização das atividades;
* execução;
* acompanhamento;
* documentação;
* gestão do backlog;
* análise de riscos;
* evolução das entregas;
* desafios encontrados;
* soluções adotadas;
* análise crítica dos resultados.

A documentação final deverá consolidar a trajetória do projeto desde sua concepção até a entrega.

---

## Disciplina

**Gestão de Projetos**

**Professor:** Prof. Me. Deivison S. Takatu
**Instituição:** SENAI

---

## Equipe

> Preencher com os integrantes responsáveis pelas atividades da disciplina.

* Integrante 1
* Integrante 2
* Integrante 3
* Integrante 4
* Integrante 5

---

## Organização do repositório

```text
GP/
│
├── README.md
│
└── Modelo 4.1/
    └── Documentos referentes ao Termo de Abertura do Projeto
```

A estrutura poderá ser ampliada conforme novas atividades e artefatos forem produzidos durante a disciplina.

---

## Referencial de gerenciamento

Os conteúdos desenvolvidos na disciplina utilizam como referência conceitos de **Gerenciamento de Projetos** e do **PMBOK — Project Management Body of Knowledge**, abordando integração, escopo, tempo, custos, qualidade, recursos, comunicações, riscos, aquisições e partes interessadas.

Esses conceitos serão aplicados progressivamente ao FieldOps durante o desenvolvimento das atividades.

---

## Status

🟡 **Projeto em desenvolvimento**

A documentação e os artefatos deste repositório serão atualizados conforme o avanço das atividades de Gestão de Projetos e a evolução do FieldOps.