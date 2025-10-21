# 🕒 Relógio do Dia

Um projeto simples que exibe a **hora atual** e muda automaticamente o **fundo da tela** conforme o período do dia (manhã, tarde ou noite).  
Desenvolvido com **HTML**, **CSS** e **JavaScript**, o objetivo é praticar manipulação do DOM, horários em tempo real e estilização dinâmica.

---

## 📌 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Funciona](#-como-funciona)
- [Como Usar](#-como-usar)
- [Demonstração](#-demonstração)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Autor](#-autor)

---

## 📝 Sobre o Projeto

O **Relógio do Dia** mostra em tempo real a hora do sistema e altera automaticamente:
- 🌅 **Manhã** → Fundo claro com tons amarelados  
- 🌇 **Tarde** → Fundo alaranjado  
- 🌙 **Noite** → Fundo escuro e azulado  

Além disso, o projeto exibe uma saudação personalizada, como “Bom dia!”, “Boa tarde!” ou “Boa noite!”.

---

## 🛠 Tecnologias Utilizadas

- 🌐 **HTML5** → Estrutura da página  
- 🎨 **CSS3** → Estilização e transições suaves  
- ⚡ **JavaScript (ES6)** → Atualização do horário e lógica de mudança de fundo

---

## 🔍 Como Funciona

A lógica do JavaScript é baseada no **horário atual do sistema**:
```js
const hora = new Date().getHours();

if (hora < 12) {
  // manhã
} else if (hora < 18) {
  // tarde
} else {
  // noite
}
