<h1 align="center">
  💣 Campo Minado (Minesweeper) em Java
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge" alt="Java Swing"/>
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge" alt="Status"/>
</p>

<p align="center">
  Recriação do clássico jogo Campo Minado, desenvolvido com interface gráfica nativa em Java Swing. Este projeto foi construído com foco em aplicar conceitos sólidos de Programação Orientada a Objetos (POO) e Design Patterns.
</p>

---

## 📸 Demonstração

> **Aviso:** [Arraste o seu print do jogo rodando aqui e apague esta frase. O GitHub vai gerar um link automático para a sua imagem!]

---

## 🎯 Funcionalidades

- **Interface Gráfica Completa:** Tabuleiro interativo e painel de status construídos com `JFrame` e `JPanel`.
- **Interação com Mouse:** 
  - `Botão Esquerdo`: Revela o campo.
  - `Botão Direito`: Adiciona/Remove a bandeira (🚩) de marcação.
- **Lógica de Propagação:** Abertura automática de campos vizinhos vazios e seguros.
- **Sistema de Game Over e Vitória:** Detecção automática de explosões ou resolução completa do tabuleiro.

## 🧠 Arquitetura e Conceitos Aplicados

Este projeto não foca apenas em funcionar, mas em como foi estruturado "por baixo dos panos":

- **Design Pattern Observer:** Utilizado para desacoplar a lógica do jogo da interface visual. A interface assina os eventos lógicos e aguarda ser notificada.
- **Generics (`<T>`):** Implementado para segurança de tipagem de dados durante o processamento de listas e pares ordenados.
- **Encapsulamento (Getters/Setters):** Proteção das variáveis de estado do campo, garantindo que regras de negócio não sejam burladas.
- **Tratamento de Eventos (Listeners):** Uso de `MouseListener` para captura e processamento das ações do jogador.

## 🚀 Como executar o projeto

1. Certifique-se de ter o **Java JDK** (versão 8 ou superior) instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/Joaomelo06/campo-minado-swing.git](https://github.com/Joaomelo06/campo-minado-swing.git)
