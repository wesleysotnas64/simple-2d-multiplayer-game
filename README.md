# 🕹️ **Simple 2D Multiplayer Game**

Este repositório contém um projeto básico de jogo 2D multiplayer desenvolvido com o Unity utilizando o **Netcode for GameObjects (NGO)**. O objetivo é aprender e aplicar conceitos de jogos multiplayer em uma estrutura simples.

---

## 📌 **Estado do Projeto**

🚧 **Em desenvolvimento**  
Atualmente, o projeto possui:
- Movimentação básica do jogador nos eixos X e Y.
- Conexão entre jogadores sem salas (todos entram automaticamente no jogo ao iniciar).

Próximos passos incluem:
- Melhorar a interface.
- Adicionar mais mecânicas ao jogador.
- Testar a integração com serviços adicionais como Unity Relay.

---

## 🎯 **Objetivo do Projeto**

Este projeto é focado no aprendizado de desenvolvimento de jogos multiplayer no Unity. Ele foi criado para explorar os seguintes tópicos:
- Uso do **Netcode for GameObjects (NGO)** para sincronização de objetos em rede.
- Implementação de lógica de rede em jogos 2D simples.
- Desenvolvimento de um ambiente básico para conectar jogadores.

💡 *Ideal para quem deseja iniciar no desenvolvimento de jogos multiplayer!*

---

## 🎮 **Gameplay**

- Cada jogador controla um personagem 2D que pode se mover livremente nos eixos X e Y.  
- A movimentação é sincronizada em tempo real para todos os jogadores conectados.

📸 **Sugestão de print**: Adicione uma captura de tela mostrando dois jogadores conectados e se movendo.

---

## 🌟 **Próximos Passos**

- Implementar suporte a salas.
- Explorar a integração com serviços adicionais do Unity Multiplayer (UGS).
- Adicionar animações e colisões.

---

## 🖥️ **Como Rodar o Projeto**

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/simple-2d-multiplayer.git
   ```
2. Abra o projeto no Unity (versão mínima recomendada: 2022.3 LTS).  
3. Execute a cena principal no Editor ou construa o projeto.  
4. Teste o multiplayer iniciando como Host em uma instância e como Cliente em outra.

📸 **Sugestão de print**: Inclua aqui uma imagem da tela inicial do jogo com os botões `Start Host` e `Start Client`.

---

## 🛠️ **Tecnologias Utilizadas**

- **Unity** 🔵: Motor principal de desenvolvimento do jogo.  
- **Netcode for GameObjects** 🌐: Biblioteca para gerenciamento da lógica de rede.  
- **Unity Transport** 🚀: Protocolo de comunicação para conexões cliente-servidor.  
