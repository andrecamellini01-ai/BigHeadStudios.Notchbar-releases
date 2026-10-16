<p align="center">
  <img src="assets/icon.png" width="112" alt="Ícone do Notchbar">
</p>

<h1 align="center">Notchbar</h1>

<p align="center">
  <b>Seu notch, vivo.</b><br>
  A música do Mac a um passar de mouse — e o HUD do Mac no lugar do quadrado cinza.<br>
  Spotify, Música, YouTube no navegador, qualquer app · letra sincronizada · volume, brilho, bateria, AirPods e Foco.
</p>

<p align="center">
  <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/Notchbar.dmg"><img alt="Baixar para macOS" src="https://img.shields.io/badge/Baixar_para_macOS-Notchbar.dmg-FF5A32?style=for-the-badge&labelColor=17161A"></a>
  <a href="#preço"><img alt="Licença vitalícia US$ 2,99" src="https://img.shields.io/badge/Licença_vitalícia-US%24_2%2C99-E8A046?style=for-the-badge&labelColor=17161A"></a>
</p>

<p align="center">
  <img alt="Versão" src="https://img.shields.io/badge/vers%C3%A3o-1.3.0-17161A?style=flat-square">
  <img alt="macOS 13 ou mais novo" src="https://img.shields.io/badge/macOS-13%2B-17161A?style=flat-square">
  <img alt="Apple Silicon e Intel" src="https://img.shields.io/badge/Apple_Silicon_%2B_Intel-universal-17161A?style=flat-square">
  <img alt="Teste grátis de 48 horas" src="https://img.shields.io/badge/teste-48h_grátis-17161A?style=flat-square">
  <img alt="Permissões opcionais" src="https://img.shields.io/badge/permissões-opcionais-17161A?style=flat-square">
</p>

<p align="center">
  <a href="#todas-as-versões"><b>Todas as versões e notas de lançamento →</b></a>
</p>

<p align="center">
  <img src="assets/states.png" width="880" alt="Notchbar: fechado tocando, mouse em cima e bandeja aberta">
</p>

---

<!-- NEWS:START -->
## Novidades da 1.3.0

Mídia completa — e o notch vira o HUD do Mac.

#### Mídia
- **Letras sincronizadas.** Nova aba **Letra** na bandeja: a linha atual em destaque, rolando no tempo da música; clique numa linha para pular até ela. Fonte: LRCLIB (grátis, sem conta), com cache local. Só artista, título, álbum e duração saem do Mac.
- **Volume na bandeja.** Barrinha de volume embaixo dos controles: do **Spotify/Música** quando é um deles que toca (via Automação), senão o volume do **Mac**.
- **Fila e extras.** Aba **Fila**: no Música, as próximas 5 faixas do playlist (clique para tocar) e **♥ curtir**; no Spotify, **aleatório** e **repetir** (o Spotify não expõe fila nem “salvar” para outros apps).
- **Fonte selecionável.** No canto da bandeja, escolha **Automática** (o que o Mac toca), **Spotify** ou **Música** — resolve o YouTube no navegador “roubando” o Now Playing.
- **Bandeja tingida** com a cor da capa (dá para desligar).
- **Gestos:** scroll horizontal sobre o notch = avançar/voltar 5 s; scroll vertical = volume do Mac; duplo clique na capa = próxima faixa (e, opcionalmente, duplo clique no notch fechado).
- **Atalhos globais** (opcionais): ⌃⌥Space tocar/pausar · ⌃⌥] próxima · ⌃⌥[ anterior · ⌃⌥→ +10 s · ⌃⌥← −10 s · ⌃⌥N abre/fecha a bandeja. Sem permissão especial.

#### Sistema (novo)
- **HUD de volume e brilho no notch**, no lugar do quadrado cinza do macOS. Opcional; exige **Acessibilidade** (é a única forma de interceptar as teclas antes do sistema). Play/pause e luz do teclado continuam com o macOS.
- **Bateria:** ao conectar/desconectar o carregador, o notch mostra % e tempo até cheia/restante; avisos em **20%** e **10%**.
- **Bluetooth:** “AirPods Pro conectados · 87%” ao conectar fones e acessórios (bateria quando o macOS publica).
- **Modo Foco** ativo aparece no notch fechado quando nada está tocando (nome e ícone do seu Foco).
- Nova aba **Sistema** nas Configurações para ligar/desligar cada um; aba **Mídia** para fonte, letras, gestos, atalhos e Automação.

#### Permissões (todas opcionais e explicadas na hora)
- **Automação** (Spotify/Música): só para volume do app, fila, curtir, aleatório/repetir e fonte explícita.
- **Acessibilidade**: só para o HUD de volume/brilho.
- Nada de conta ou telemetria. Bateria, Bluetooth e Foco são lidos localmente.

#### Notas
- Licença vitalícia cobre toda a série 1.x.

<sub>[Notas completas](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.3.0.md) · [Todas as versões](#todas-as-versões)</sub>
<!-- NEWS:END -->

## Escondido no notch. Vivo quando você precisa.

O Notchbar mora no notch do MacBook e não ocupa nada da tela. **Passe o mouse** e ele reage com uma expandidinha. **Clique** e uma bandeja desliza por trás do notch com a capa, o nome da música, o artista, a barra de progresso e os controles — tingida com a cor da capa.

## Dynamic Island no Mac

Tocou algo? Com o notch fechado, a **capa aparece à esquerda** e um **equalizador à direita**, na cor do álbum. Pausou, e alguns segundos depois tudo volta a sumir no notch.

O notch fechado também avisa o que acontece no Mac — volume, brilho, carregador, fones conectados, Modo Foco — e some de novo sozinho.

## Tudo o que toca no Mac

| | |
|---|---|
| **Spotify, Música, Podcasts** | capa, título, artista, álbum |
| **Chrome, Safari, Arc, Edge, Firefox** | YouTube, SoundCloud, Deezer web, cursos, podcasts no navegador |
| **Controles** | −10 s · anterior · play/pause · próxima · +10 s · arraste a barra para pular · volume |
| **Abas da bandeja** | **Player** · **Letra** · **Fila** |

Se aparece na Central de Controle do macOS, aparece no Notchbar.

## Pule 10 segundos, em qualquer player

**−10 s** e **+10 s** ao lado de faixa anterior e próxima — no Spotify, no Música, num podcast ou num vídeo do YouTube no navegador. Toques seguidos somam (3 toques = 30 s). Se o player não deixa pular (uma transmissão ao vivo, por exemplo), os botões ficam apagados.

<p align="center">
  <img src="assets/controls.png" width="760" alt="Bandeja aberta com um vídeo do YouTube no Chrome: botões −10 s, faixa anterior, play/pause, próxima faixa e +10 s">
</p>

## Letra sincronizada

Aba **Letra** na bandeja: a linha que está tocando fica em destaque e a letra rola no tempo da música. **Clique numa linha** para pular até ela. Sem letra sincronizada para a faixa, aparece a letra simples.

As letras vêm do [LRCLIB](https://lrclib.net) (grátis, sem conta) e ficam em cache no seu Mac. Só artista, título, álbum e duração saem do Mac — e dá para desligar em Configurações › Mídia.

## Volume, fila e fonte

- **Volume na bandeja:** a barrinha embaixo dos controles mexe no volume do **Spotify** ou do **Música** quando é um deles que toca; senão, no volume do **Mac**.
- **Fila (aba Fila):** no **Música**, as próximas 5 faixas da playlist (clique para tocar) e **♥ curtir**. No **Spotify**, **aleatório** e **repetir** — o Spotify não deixa outros apps verem a fila nem salvar músicas.
- **Fonte:** no canto da bandeja, escolha **Automática** (o que o Mac toca), **Spotify** ou **Música**. Resolve o caso do vídeo no navegador “roubando” o lugar da sua música.

Volume do app, fila, curtir, aleatório/repetir e fonte fixa usam a permissão de **Automação** do macOS (pedida na primeira vez, explicada na hora). Sem ela, o resto funciona igual.

## Gestos e atalhos

| Gesto | O que faz |
|---|---|
| Scroll **horizontal** sobre o notch | avança / volta 5 s |
| Scroll **vertical** sobre o notch | volume do Mac |
| **Duplo clique** na capa | próxima faixa |
| Duplo clique no notch fechado (opcional) | próxima faixa |

**Atalhos globais** (opcionais, em Configurações › Mídia), sem nenhuma permissão:

| Atalho | Ação |
|---|---|
| ⌃⌥Space | tocar / pausar |
| ⌃⌥] · ⌃⌥[ | próxima · anterior |
| ⌃⌥→ · ⌃⌥← | +10 s · −10 s |
| ⌃⌥N | abre / fecha a bandeja |

## O notch vira o HUD do Mac

| | O que aparece no notch | Padrão |
|---|---|---|
| **Volume e brilho** | barrinha elegante no notch, no lugar do quadrado cinza do macOS | desligado (pede **Acessibilidade**) |
| **Bateria** | ao ligar/tirar o carregador: % e tempo até encher ou restante; avisos em **20%** e **10%** | ligado |
| **Bluetooth** | “AirPods Pro conectados · 87%” ao conectar fones e acessórios (a bateria, quando o macOS publica) | ligado |
| **Modo Foco** | o nome e o ícone do Foco ativo, com o notch fechado e nada tocando | ligado |

Tudo liga e desliga em Configurações › **Sistema**. No HUD, play/pause e a luz do teclado continuam com o macOS; o brilho vale para a tela do Mac. Se algo falhar (uma saída de som sem volume, por exemplo), a tecla volta para o macOS — o Notchbar nunca “engole” uma tecla sem fazer o que ela pede.

## Nada atrás do notch

Nenhum botão, texto ou capa fica escondido atrás da câmera: tudo vive dos lados e abaixo do notch. As configurações ficam no canto superior esquerdo da bandeja aberta — abas **Geral**, **Mídia**, **Sistema**, **Licença** e **Sobre**.

Em monitor externo ou num Mac sem notch, aparece um notch virtual (dá para desligar).

## Instalar em 1 minuto

1. [**Baixe o Notchbar.dmg**](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/Notchbar.dmg), abra e arraste o Notchbar para **Aplicativos**.
2. Abra o app. O macOS vai bloquear na primeira vez — clique em **OK**.
3. Vá em **Ajustes do Sistema › Privacidade e Segurança**, role até **Segurança** e clique em **Abrir Mesmo Assim**.
4. Na janela seguinte, clique em **Abrir**. A bandeja aparece no notch para mostrar onde o Notchbar mora.

<details>
<summary><b>Por que o macOS bloqueia na primeira vez?</b></summary>
<br>
O Notchbar é distribuído fora da App Store. O macOS pede que você aprove uma vez qualquer app baixado dessa forma. As atualizações seguintes instalam por dentro do app, sem esse passo.
</details>

## Preço

| | Teste | Vitalícia |
|---|:---:|:---:|
| **Preço** | grátis | **US$ 2,99** — pagamento único |
| **Duração** | 48 horas | para sempre |
| **Todos os recursos** | ✓ | ✓ |
| **Atualizações 1.x** | — | ✓ |
| **Macs** | 1 | até 2 |
| **Funciona offline** | ✓ | ✓ (confirma online na ativação) |

<!-- TROQUE o link abaixo pelo seu checkout (Stripe Payment Link, Lemon Squeezy, Gumroad…) -->
**[Comprar licença vitalícia →](COLE_AQUI_O_LINK_DO_CHECKOUT)**

A key chega no e-mail da compra. No Notchbar: abra a bandeja › ícone de ampulheta › cole › **Ativar** (precisa de internet nessa hora).

## Privacidade

- **Sem nenhuma permissão, o Notchbar já funciona:** player, ±10 s, letras, gestos, atalhos, bateria e Foco. Ele lê o mesmo “Tocando agora” da Central de Controle, **só no seu Mac**.
- **Permissões opcionais**, pedidas só quando você liga o recurso e explicadas na hora:

| Permissão | Para quê | Sem ela |
|---|---|---|
| **Automação** (Spotify/Música) | volume do app, fila, curtir, aleatório/repetir, fonte fixa | volume do Mac e o resto do player |
| **Acessibilidade** | HUD de volume e brilho no notch (única forma de pegar as teclas antes do macOS) | o quadrado cinza do macOS continua |
| **Bluetooth** (o macOS pode perguntar) | aviso de fones/acessórios conectados e a bateria deles | sem o aviso de Bluetooth |

- Nada de conta nem analytics. Rede: a checagem diária de atualização (um arquivo estático neste repositório), a confirmação da licença (só a key, um código do Mac — um hash —, o nome do Mac e a versão do app) e, com as letras ligadas, a busca no LRCLIB (artista, título, álbum e duração).

## Todas as versões

Cada versão continua disponível para download, com as suas notas. O app avisa sozinho quando sai uma nova (ícone verde no canto da bandeja) e se atualiza por dentro, conferindo a integridade do download.

<!-- VERSIONS:START -->
| Versão | Data | Download | Notas | SHA-256 |
|---|---|---|---|---|
| **1.3.0** **(atual)** | 16/10/2026 | [Notchbar-1.3.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.3.0.dmg) | [v1.3.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.3.0.md) | `b1d12dda45e9…` |
| **1.2.2** | 15/10/2026 | [Notchbar-1.2.2.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.2.2.dmg) | [v1.2.2](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.2.2.md) | `7c746af721d3…` |
| **1.2.1** | 15/10/2026 | [Notchbar-1.2.1.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.2.1.dmg) | [v1.2.1](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.2.1.md) | `2401340eaa33…` |
| **1.2.0** | 15/10/2026 | [Notchbar-1.2.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.2.0.dmg) | [v1.2.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.2.0.md) | `0ca48df14b0e…` |
<!-- VERSIONS:END -->

## Perguntas frequentes

<details>
<summary><b>Funciona no meu Mac sem notch?</b></summary>
<br>
Sim. O Notchbar desenha um notch virtual no topo da tela, que se comporta igual.
</details>

<details>
<summary><b>Some quando eu uso um app em tela cheia?</b></summary>
<br>
Sim, de propósito: em tela cheia o Notchbar sai do caminho.
</details>

<details>
<summary><b>O que acontece depois das 48 horas?</b></summary>
<br>
A bandeja passa a mostrar só “Ativar licença” e “Comprar”. Cole a key e tudo volta na hora.
</details>

<details>
<summary><b>Por que o Notchbar pede Automação ou Acessibilidade?</b></summary>
<br>
Só se você ligar os recursos que precisam delas. <b>Automação</b> é como o macOS deixa um app conversar com o Spotify e o Música (volume do app, fila, curtir). <b>Acessibilidade</b> é a única forma de pegar as teclas de volume e brilho antes do macOS, para o HUD aparecer no notch. Sem elas, todo o resto funciona.
</details>

<details>
<summary><b>A letra não aparece. Por quê?</b></summary>
<br>
A letra vem do LRCLIB, um acervo aberto: nem toda faixa está lá (podcasts e vídeos quase nunca). Precisa de internet na primeira vez que a faixa toca; depois fica em cache. Confira também se as letras estão ligadas em Configurações › Mídia.
</details>

<details>
<summary><b>Dá para ver a fila do Spotify?</b></summary>
<br>
Não: o Spotify não mostra a fila nem deixa salvar músicas para outros apps. No Spotify, a aba Fila tem aleatório e repetir; no Música, as próximas 5 faixas e o ♥ curtir.
</details>

<details>
<summary><b>O HUD de volume substitui o do macOS?</b></summary>
<br>
Sim, se você ligar (Configurações › Sistema) e permitir Acessibilidade. Desligou, o quadrado cinza do macOS volta na hora.
</details>

<details>
<summary><b>Em quantos Macs posso usar?</b></summary>
<br>
Em até **2 Macs** seus ao mesmo tempo. Trocou de Mac? No antigo: Licença › Remover licença deste Mac — a vaga fica livre para o novo.
</details>

---

<p align="center"><sub>Também da BigHeadStudios: <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases"><b>Limitbar</b></a> — seus limites do Claude na barra de menu.</sub></p>

<sub>© 2026 BigHeadStudios. Notchbar é independente, sem afiliação com a Apple ou com os apps que controla. Leitura de mídia via <a href="https://github.com/ungive/mediaremote-adapter">mediaremote-adapter</a> (BSD-3-Clause).</sub>
