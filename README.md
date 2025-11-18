# Car Scrapping + Tkinter V2 — Atualização com Tela de Login

**Feito por Vinicius Santos-Tech**

Este projeto realiza web scraping do preço do Fiat Fastback utilizando Selenium, salva os dados em Excel, envia notificação via WhatsApp e exibe tudo em uma interface gráfica Tkinter.

## 🔄 Atualização: Tela de Login Antes da Interface Principal

Esta atualização adicionou uma tela de login feita com CustomTkinter, exibida antes do sistema principal.

## 📊 O que mudou

### **Antes**
- A interface principal (Tkinter) era aberta imediatamente ao executar o programa
- Não existia autenticação

### **Agora**
- O sistema inicia mostrando uma tela de login
- O usuário deve digitar:
  - **Usuário:** Vinicius
  - **Senha:** 12345

#### **Se o login for válido:**
- A mensagem de sucesso é exibida
- A janela de login é fechada automaticamente  
- A interface principal do projeto é aberta

#### **Se o login for inválido:**
- A mensagem de erro é mostrada

> **Nota:** A interface original não sofreu nenhuma alteração visual. Ela apenas foi movida para dentro de uma função chamada após o login ser validado.

## 🛠 Tecnologias Utilizadas

- Python
- CustomTkinter
- Tkinter
- Selenium
- Pandas
- PyWhatKit
- ChromeDriverManager

