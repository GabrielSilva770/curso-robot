# 🤖 Projeto Robot Framework com BDD

Este repositório contém um projeto de **automação de testes utilizando Robot Framework**, estruturado no **padrão BDD (Behavior Driven Development)**. O objetivo principal do projeto é validar o **processo de cadastro por meio do preenchimento de formulários**, garantindo que o fluxo funcione corretamente tanto em cenários positivos quanto negativos.

---

## 🎯 Objetivo do Projeto

* Automatizar testes de **cadastro de usuários** via formulário
* Validar se o processo de cadastro é realizado corretamente com dados válidos
* Verificar comportamentos do sistema em casos de **preenchimento incorreto**
* Aplicar boas práticas de automação com **BDD**, organização de código e reutilização de componentes

---

## 🧪 O que é testado

* Preenchimento correto do formulário de cadastro
* Confirmação de sucesso no processo de cadastro
* Validações de erro quando:

  * Campos obrigatórios não são preenchidos
* Execução de múltiplos cenários de cadastro utilizando **banco de massa de dados**

---

## 🗂️ Estrutura do Projeto

O projeto está organizado de forma a facilitar a manutenção, reutilização e clareza dos testes:

* **main.robot**
  Arquivo principal responsável por orquestrar a execução dos testes.

* **setup_teardown.robot**
  Contém as configurações de **Setup** e **Teardown**, garantindo a preparação e limpeza do ambiente antes e após cada execução.

* **Arquivos de teste (BDD)**
  Cenários escritos seguindo o padrão **Given / When / Then**, facilitando a leitura e entendimento do comportamento esperado do sistema.

* **Banco de Massa de Dados**
  Utilizado a biblioteca FakerLibrary para geração de varios valores para executar múltiplos cadastros automaticamente, variando os dados de entrada e validando diferentes cenários.

---

## 🧱 Boas Práticas Aplicadas

* Uso do padrão **BDD** para melhor legibilidade dos testes
* Separação de responsabilidades (main, setup/teardown, cenários)
* Reutilização de keywords
* Testes positivos e negativos
* Automação orientada a dados (Data Driven Tests)

---

## 🚀 Tecnologias Utilizadas

* **Robot Framework**
* **Bibliotecas do Robot (Browser/Selenium, FakerLibrary, etc.)**
* **BDD (Behavior Driven Development)**

---

## 📌 Considerações Finais

Este projeto faz parte do meu processo de aprendizado e evolução na área de **Qualidade de Software e Automação de Testes**. Ele demonstra a aplicação prática dos conceitos aprendidos, com foco em organização, clareza e confiabilidade dos testes automatizados.

Fique à vontade para explorar, clonar o repositório e acompanhar minha evolução 🚀
