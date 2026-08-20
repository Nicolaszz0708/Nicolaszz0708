# MUDANÇAS E ENCAMINHAMENTOS — OBJETIVOS FUNCIONAIS

Este documento registra os itens retirados da definição dos objetivos funcionais e indica onde cada informação deverá ser retomada posteriormente.

Os itens não foram descartados do projeto. Eles foram removidos deste documento porque representam requisitos, regras, decisões técnicas ou assuntos que ainda precisam ser planejados em etapas posteriores.

---

# 1. RFs / RNFs

## 5.2 — Cadastro e gerenciamento de usuários

### Destino
**Documento 8 — Requisitos Funcionais (RFs)**

### O que será aproveitado
* Cadastro do estudante;
* nome;
* username único;
* senha;
* login;
* acesso aos próprios dados;
* privacidade da conta;
* regra de username sem diferenciação entre letras maiúsculas e minúsculas.

### Observação
Os detalhes de segurança da senha serão tratados também nos **RNFs — Documento 9**.

---

## 5.3 — Regras específicas do questionário

### Destino
**Documento 8 — Requisitos Funcionais**

### Também relacionado a
* **Item 14 — Definição da lógica do questionário vocacional**
* **Item 15 — Estruturação das perguntas e pontuações**

### O que será aproveitado
* organização das perguntas;
* funcionamento do questionário;
* regras de preenchimento;
* comportamento das perguntas;
* apresentação das perguntas ao usuário.

### Observação
A parte relacionada à clareza, facilidade de compreensão e acessibilidade será tratada nos **RNFs** e no **Item 26 — Planejamento da acessibilidade e usabilidade**.

---

## 5.8 — Detalhes dos simulados

### Destino
**Documento 8 — Requisitos Funcionais**

### Também relacionado a
* **Item 18 — Definição dos tipos de simulados**
* **Item 19 — Definição das competências avaliadas em cada simulado**
* **Item 20 — Definição da lógica de correção**
* **Item 21 — Definição do sistema de feedback e desempenho**

### O que será aproveitado
* disponibilização dos simulados;
* simulações de processos seletivos;
* correção;
* registro de desempenho;
* feedback.

### Observação
As regras específicas ainda não estão definidas.

---

## 5.10 — Detalhamento do histórico

### Destino
**Documento 8 — Requisitos Funcionais**

### Também relacionado a
* **Item 28 — Modelagem do banco de dados**
* **Item 29 — Definição das entidades e relacionamentos**
* **Item 30 — Planejamento de armazenamento de dados**

### O que será aproveitado
* respostas do questionário;
* resultados da análise;
* desempenho nos simulados;
* histórico de atividades;
* informações necessárias para acompanhamento da evolução.

---

## 5.11 — Privacidade dos resultados

### Destino
**Documento 9 — Requisitos Não Funcionais (RNFs)**

### O que será aproveitado
* resultados privados por padrão;
* acesso aos resultados pelo próprio usuário;
* controle de acesso;
* ausência inicial de compartilhamento entre usuários.

---

## 5.12 — Auxílio por inteligência artificial

### Destino
**Documento 8 — Requisitos Funcionais**

### Também relacionado a
**Documento 9 — Requisitos Não Funcionais**

### O que será aproveitado como RF
* existência do chatbot;
* possibilidade de solicitar auxílio;
* auxílio na compreensão de perguntas;
* auxílio na compreensão de termos;
* auxílio relacionado aos simulados;
* funcionamento como recurso complementar.

### O que será aproveitado como RNF
* a IA não pode ser uma dependência crítica;
* a plataforma deve continuar funcionando caso a IA esteja indisponível;
* a IA não deve executar as funções principais do sistema.

### Observação
A IA não será responsável por:
* responder o questionário pelo estudante;
* realizar obrigatoriamente a análise principal;
* avaliar currículo;
* corrigir redações.

---

## 5.13 — Segurança e controle de acesso

### Destino
**Documento 9 — Requisitos Não Funcionais (RNFs)**

### O que será aproveitado
* proteção dos dados;
* armazenamento seguro de senhas;
* autenticação;
* controle de acesso;
* proteção de páginas privadas;
* proteção dos resultados;
* validação das informações;
* prevenção de acesso a dados de outras contas.

### Observação
Os mecanismos técnicos específicos serão definidos posteriormente na arquitetura e implementação.

---

## 5.14 — Usabilidade e acessibilidade

### Destino
**Documento 9 — Requisitos Não Funcionais (RNFs)**

### Também relacionado a
**Item 26 — Planejamento da acessibilidade e usabilidade**

### O que será aproveitado
* interface simples;
* navegação intuitiva;
* clareza dos botões;
* organização das informações;
* linguagem adequada;
* facilidade de preenchimento;
* compreensão das perguntas;
* feedback visual;
* responsividade;
* acessibilidade.

---

## 5.15 — Funcionamento independente de serviços externos

### Destino
**Documento 9 — Requisitos Não Funcionais (RNFs)**

### O que será aproveitado
As funcionalidades principais deverão possuir funcionamento próprio e não depender obrigatoriamente de serviços externos.

### Serviços considerados complementares
* API de inteligência artificial;
* hospedagem pública;
* outros serviços externos que possam ser utilizados posteriormente.

---
