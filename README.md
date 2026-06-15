# OMNI Observer 🎮🎥

O **OMNI Observer** é uma ferramenta inteligente e automatizada de controle de câmera de espectador para **Counter-Strike 2 (CS2)**. Desenvolvido para narradores, produtores de conteúdo e observadores de campeonatos, o aplicativo utiliza dados táticos em tempo real (GSI) e integração avançada com o HLAE para proporcionar a melhor experiência de transmissão.

---

## 🚀 Principais Funcionalidades

* **Auto Observer (Foco por IA):** Seleciona automaticamente qual jogador focar com base em telemetria em tempo real (se está plantando/defusando a C4, trocando tiros, proximidade de inimigos, etc.).
* **Câmera Cinemática (HLAE):** Carregamento dinâmico e execução de caminhos de câmera fluidos (*campaths*) no fim do round ou via atalhos, criando transições de nível profissional.
* **Gerenciador de Câmeras Estáticas:** Atalhos rápidos configuráveis (F3 a F8) para posicionar a câmera instantaneamente em pontos-chave do mapa (Spawns, Bomb Sites A/B, Meio do mapa, Visão aérea).
* **Painel de Controle Intuitivo:** Interface desktop nativa para gerenciar pesos de prioridade de foco, ajustar tempos de cooldown e ativar sua licença.

---

## 🛠️ Como Funciona?

O aplicativo conecta-se ao CS2 usando duas portas de comunicação nativas do jogo:
1. **GSI (Game State Integration):** O CS2 envia dados da partida (quem está vivo, vida, posição, status do round) para o OMNI Observer em tempo real.
2. **Netcon (Network Console):** O OMNI Observer conecta-se ao console interno do CS2 para executar comandos de troca de câmera de forma instantânea e segura (sem risco de banimento VAC, pois utiliza recursos nativos do jogo).

---

## 📦 Como Instalar (Para Usuários)

1. Baixe a versão estável mais recente na aba **Releases** deste repositório (arquivo `.zip`).
2. Extraia o conteúdo do arquivo em uma pasta de sua preferência.
3. Abra a pasta extraída e execute o arquivo **`OMNI Observer.exe`**.
4. No painel que se abre, clique em **Instalar GSI CFG** para configurar a integração com o seu CS2 de forma totalmente automática.
5. Inicie seu CS2 com a flag `-netconport 2121` nas opções de inicialização da Steam.
6. Pronto! A integração estará ativa e o controle estará na tela.
