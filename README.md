<p align="center">
  <img src="assets/icon.png" width="112" alt="Ícone do Notchbar">
</p>

<h1 align="center">Notchbar</h1>

<p align="center">
  <b>Seu notch, vivo.</b><br>
  A música do Mac a um passar de mouse, o HUD do Mac no lugar do quadrado cinza, a próxima reunião com botão Entrar — e, na 2.0, o <b>Claude Code pedindo permissão</b>: você aprova ali mesmo.<br>
  Spotify, Música, YouTube no navegador · letra com karaokê e tradução · Meet, Zoom e Teams na hora · timer e Pomodoro · limite do Claude · capturas e downloads · AirPods com três anéis.
</p>

<p align="center">
  <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/Notchbar.dmg"><img alt="Baixar para macOS" src="https://img.shields.io/badge/Baixar_para_macOS-Notchbar.dmg-FF5A32?style=for-the-badge&labelColor=17161A"></a>
  <a href="#preço"><img alt="Licença vitalícia R$ 10 por Pix" src="https://img.shields.io/badge/Licen%C3%A7a_vital%C3%ADcia-R%24_10_%C2%B7_Pix-E8A046?style=for-the-badge&labelColor=17161A"></a>
</p>

<p align="center">
  <img alt="Versão" src="https://img.shields.io/badge/vers%C3%A3o-2.0.3-17161A?style=flat-square">
  <img alt="macOS 13 ou mais novo" src="https://img.shields.io/badge/macOS-13%2B-17161A?style=flat-square">
  <img alt="Apple Silicon e Intel" src="https://img.shields.io/badge/Apple_Silicon_%2B_Intel-universal-17161A?style=flat-square">
  <img alt="Teste grátis de 48 horas" src="https://img.shields.io/badge/teste-48h_grátis-17161A?style=flat-square">
  <img alt="Permissões opcionais" src="https://img.shields.io/badge/permissões-opcionais-17161A?style=flat-square">
</p>

<p align="center">
  <a href="#todas-as-versões"><b>Todas as versões e notas de lançamento →</b></a>
</p>

<p align="center">
  <img src="assets/notchbar-2.0.gif" width="880" alt="Notchbar 2.0 em 18 segundos: a bandeja da música abrindo, a reunião com o botão Entrar, o Claude Code pedindo permissão (Permitir) e o timer ao lado da câmera">
</p>

---

<!-- NEWS:START -->
## Novidades da 2.0.3

O equalizador mostra os valores.

#### Ajustes
- **Equalizador com rótulos.** Cada banda mostra o ganho em dB em cima do fader (“+3”, “−4,5”), atualizando enquanto você arrasta, e a escala +12 · 0 · −12 fica ao lado. Duplo clique no fader continua zerando a banda.

#### Notas
- Nada muda na licença nem nas permissões.

<sub>[Notas completas](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v2.0.3.md) · [Todas as versões](#todas-as-versões)</sub>
<!-- NEWS:END -->

## Escondido no notch. Vivo quando você precisa.

O Notchbar mora no notch do MacBook e não ocupa nada da tela. **Passe o mouse** e ele reage com uma expandidinha. **Clique** e uma bandeja desliza por trás do notch com a capa, o nome da música, o artista, a barra de progresso e os controles — tingida com a cor da capa.

## Novo na 2.0: o Claude Code pede, você aprova no notch

Deixou o agente trabalhando e foi fazer outra coisa? Quando o **Claude Code** pede permissão para rodar um comando ou editar um arquivo, o notch mostra o pedido — com o comando — e os botões **Permitir · Negar · Sempre**. **⌃⌥Y** permite e **⌃⌥X** nega sem tirar a mão do teclado. Sem resposta no prazo, o pedido volta para o terminal como sempre.

<p align="center">
  <img src="assets/agents.png" width="880" alt="O Claude Code pede permissão no notch com Permitir, Negar e Sempre; trabalhando ao lado da música; pronto com o fim da resposta">
</p>

- **Trabalhando:** uma pílula com o projeto ao lado da câmera (com música, a capa fica à esquerda). Clique e volta para a aba certa do Terminal ou do iTerm — ou para o VS Code, o Cursor, o Warp, o Ghostty.
- **Pronto, erro ou esperando você:** o notch abre com o fim da resposta e fica compacto até você olhar.
- **Seção Agentes** na meia roda: todas as sessões, o que cada uma está fazendo e os pedidos pendentes.
- **Como liga:** Configurações › Agentes › **Instalar**. O Notchbar acrescenta só as linhas dele no `~/.claude/settings.json` (com backup) e tira só elas ao desinstalar. Nada sai do Mac.

## Tempo, limites, AirPods e capturas

<p align="center">
  <img src="assets/v2-cards.png" width="880" alt="Pomodoro correndo com o anel ao lado da câmera; limite do Claude em 82% pelo Limitbar; AirPods com três anéis; captura de tela com a miniatura para arrastar">
</p>

- **Tempo:** timer (role para escolher os minutos), cronômetro e **Pomodoro** — no foco, os avisos que não importam esperam a pausa; se uma reunião cai no meio, o notch avisa antes. **⌃⌥T** e **⌃⌥P**.
- **Câmera e microfone em uso**, com o nome do app — e “**Microfone ainda ligado**” se a reunião acabou e o Zoom continuou ouvindo.
- **Limite do Claude:** com o [Limitbar](https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases), o notch mostra quando o limite aperta, conta até liberar e avisa “Sessão liberada”.
- **Capturas e downloads** caem sozinhos na **Prateleira** (a captura aparece no notch para você arrastar direto para o Slack ou o e-mail); downloads com anel de progresso.
- **Copiados:** o que você copiou, para copiar de novo — só na memória, ignorando senhas.
- **Som:** troque a saída (AirPods, monitor, caixa) na bandeja; **Que música é essa?** (Shazam); letra com **karaokê** e **tradução**; **equalizador** do sistema (beta).
- **Próximas 3:** passe o mouse no notch e veja as próximas reuniões do dia numa linha.

## A bandeja: uma meia roda de seções

Na borda esquerda da bandeja mora uma **meia roda**. Recolhida, é só uma coluna de pontos. **Passe o mouse por cima** e ela entra com os ícones das seções; **role** (trackpad ou roda do mouse) para girar, ou clique no ícone. Enquanto ela está aberta, o resto da bandeja recua num fade — a roda é o destaque.

| Seção | O que mostra |
|---|---|
| **Em branco** | nada: a bandeja mais baixa, só com os ícones de configuração |
| **Música** | o player — e, no canto superior esquerdo, a pílula **Reprodução · Letra · Fila** |
| **Som** | saídas de áudio, equalizador e “Que música é essa?” |
| **Hoje** | a agenda do dia, com a próxima reunião em destaque (aparece com a Agenda ligada) |
| **Tempo** | timer, cronômetro e Pomodoro; câmera e microfone em uso |
| **Agentes** | as sessões do Claude Code e os pedidos pendentes (aparece com Agentes ligado) |
| **Prateleira** | arquivos guardados — e **Copiados**, o histórico da área de transferência |

A roda tem sempre o mesmo tamanho e o mesmo lugar, em qualquer Mac: trocar de seção cresce ou encolhe a bandeja para baixo, sem mexer nela.

<p align="center">
  <img src="assets/dial.png" width="640" alt="Bandeja aberta com a meia roda de seções à esquerda: Em branco, Música (selecionada) e Hoje; o player recua num fade">
</p>

## Dynamic Island no Mac

Tocou algo? Com o notch fechado, a **capa aparece à esquerda** e um **equalizador à direita**, na cor do álbum. Pausou, e alguns segundos depois tudo volta a sumir no notch.

O notch fechado também avisa o que acontece no Mac — volume, brilho, carregador, fones conectados, Modo Foco — e some de novo sozinho.

## Tudo o que toca no Mac

| | |
|---|---|
| **Spotify, Música, Podcasts** | capa, título, artista, álbum |
| **Chrome, Safari, Arc, Edge, Firefox** | YouTube, SoundCloud, Deezer web, cursos, podcasts no navegador |
| **Controles** | −10 s · anterior · play/pause · próxima · +10 s · arraste a barra para pular · volume |
| **Seção Música** | pílula **Reprodução** · **Letra** · **Fila** no canto superior esquerdo |

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
| Scroll sobre a **meia roda** (mouse em cima dela) | gira entre as seções |
| Scroll na seção **Tempo** (parado) | escolhe os minutos do timer |
| Arrastar arquivo, texto ou link até o notch | guarda na Prateleira |
| **Duplo clique** na capa | próxima faixa |
| Duplo clique no notch fechado (opcional) | próxima faixa |

**Atalhos globais** (opcionais, em Configurações › Mídia), sem nenhuma permissão:

| Atalho | Ação |
|---|---|
| ⌃⌥Space | tocar / pausar |
| ⌃⌥] · ⌃⌥[ | próxima · anterior |
| ⌃⌥→ · ⌃⌥← | +10 s · −10 s |
| ⌃⌥N | abre / fecha a bandeja |
| ⌃⌥J | entra na próxima reunião (ou abre Hoje) |
| ⌃⌥K | limpeza do teclado (trava as teclas por um tempo) |
| ⌃⌥T · ⌃⌥P | timer (começa/pausa) · Pomodoro |
| ⌃⌥Y · ⌃⌥X | permite · nega o pedido do agente (só existem enquanto há um pedido) |

**Para Atalhos, Raycast e scripts:** `open "notchbar://timer?minutes=25"`, `notchbar://notify?title=Deploy%20ok&color=green`, `notchbar://open?section=agents`, `notchbar://agent?event=done&name=Codex` e mais.

## A próxima reunião, no notch

Ligue em Configurações › **Agenda** e escolha os calendários. Na antecedência que você definir (10 min por padrão), o notch fechado mostra um **lembrete discreto com a contagem** ao lado da câmera; aos **2 minutos** ele abre com o botão **Entrar**, que leva direto ao **Google Meet, Zoom ou Teams** do evento — o link é lido do próprio convite. Na hora, “Agora”, com × para ignorar só aquela reunião. Com música tocando, a capa fica e o lembrete ocupa o lado direito.

<p align="center">
  <img src="assets/agenda.png" width="880" alt="Os três momentos do lembrete: 10 min antes (contagem ao lado da câmera), 2 min antes (cartão com Entrar) e na hora (Agora, com × para ignorar)">
</p>

- **Hoje:** a seção da bandeja com o dia inteiro — o que já passou recua, uma linha **“agora”** separa o passado do que vem (a lista abre rolada até ela), a próxima fica destacada, com **Entrar / Abrir / Mapas** em cada linha e o atalho para o app Calendário.

<p align="center">
  <img src="assets/today.png" width="640" alt="Seção Hoje: dois eventos terminados apagados, a linha agora às 09:52 e a próxima reunião destacada com o botão Entrar">
</p>

- **⌃⌥J** entra na próxima reunião com link (ou abre Hoje).
- **Calendários do Mac:** tudo o que está em Contas da Internet (iCloud, Google, Exchange, Outlook…), via a permissão de Calendários — só leitura.
- **Google direto, se quiser:** Configurações › Agenda › **Conectar Google** — login na página do Google, sem colocar a conta no macOS. Os calendários do Google aparecem junto com os do Mac. (Enquanto o app está em verificação no Google, a conexão é liberada por e-mail de teste; os calendários do Mac funcionam para todo mundo.)

O Notchbar **nunca cria, altera, remove nem responde** eventos. Os eventos ficam só na memória do app, enquanto ele roda; nada é gravado nem enviado. Detalhes em [Privacidade](#privacidade).

## O notch vira o HUD do Mac

| | O que aparece no notch | Padrão |
|---|---|---|
| **Volume e brilho** | HUD preto colado no notch: ícone à esquerda da câmera, % à direita e a barra embaixo, com degradê e brilho suave; arraste para ajustar. 4 cores (Azul, Verde, Amarelo, Vermelho), uma para cada | desligado (pede **Acessibilidade**) |
| **Bateria** | ao ligar/tirar o carregador: % e tempo até encher ou restante; avisos em **20%** e **10%** | ligado |
| **Bluetooth** | “AirPods Pro conectados · 87%” ao conectar fones e acessórios (a bateria, quando o macOS publica) | ligado |
| **Modo Foco** | o nome e o ícone do Foco ativo, com o notch fechado e nada tocando | ligado |

Tudo liga e desliga em Configurações › **Sistema**. No HUD, play/pause e a luz do teclado continuam com o macOS; o brilho vale para a tela do Mac. Se algo falhar (uma saída de som sem volume, por exemplo), a tecla volta para o macOS — o Notchbar nunca “engole” uma tecla sem fazer o que ela pede.

## Nada atrás do notch

Nenhum botão, texto ou capa fica escondido atrás da câmera: tudo vive dos lados e abaixo do notch. As configurações ficam no canto superior esquerdo da bandeja aberta — uma janela com barra lateral e uma **prévia do notch** no topo de cada página, que acompanha o que você muda. A página **Permissões** mostra o estado de cada uma e o botão certo; **Acessibilidade** segue os Ajustes do macOS (reduzir movimento, aumentar contraste, reduzir transparência, VoiceOver).

Em monitor externo ou num Mac sem notch, aparece um notch virtual — completo ou **minimizado** (só um sinalzinho que cresce ao passar o mouse); dá para desligar.

**Várias telas:** escolha se o notch aparece só na principal, só na secundária ou em **todas** — com a tampa fechada e dois monitores, a música, o HUD e os avisos aparecem nos dois ao mesmo tempo.

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
| **Preço** | grátis | **R$ 10** — pagamento único, por Pix |
| **Duração** | 48 horas | para sempre |
| **Todos os recursos** | ✓ | ✓ |
| **Atualizações (inclui a 2.0)** | — | ✓ |
| **Macs** | 1 | até 2 |
| **Funciona offline** | ✓ | ✓ (confirma online na ativação) |

**A compra é dentro do app, por Pix** (Notchbar 2.0.1+): baixe, abra Configurações › Licença › **Comprar — R$ 10**, informe seu e-mail, pague o QR no app do seu banco e anexe o comprovante. Assim que conferirmos (normalmente em poucas horas), a licença **ativa sozinha** — não precisa colar nada. Para o segundo Mac, a mesma key fica em Licença.

Já tem uma key (NB1 ou NB2)? Licença › cole › **Ativar** (precisa de internet nessa hora).

## Privacidade

- **Sem nenhuma permissão, o Notchbar já funciona:** player, ±10 s, letras, gestos, atalhos, bateria e Foco. Ele lê o mesmo “Tocando agora” da Central de Controle, **só no seu Mac**.
- **Permissões opcionais**, pedidas só quando você liga o recurso e explicadas na hora:

| Permissão | Para quê | Sem ela |
|---|---|---|
| **Automação** (Spotify/Música) | volume do app, fila, curtir, aleatório/repetir, fonte fixa | volume do Mac e o resto do player |
| **Acessibilidade** | HUD de volume e brilho no notch (única forma de pegar as teclas antes do macOS) | o quadrado cinza do macOS continua |
| **Bluetooth** (o macOS pode perguntar) | aviso de fones/acessórios conectados e a bateria deles | sem o aviso de Bluetooth |
| **Calendários** (acesso total — o único que o macOS 14+ oferece para ler eventos) | lembrete da próxima reunião, Entrar e a seção Hoje; **só leitura** | sem a Agenda (ou só com o Google direto) |
| **Google** (login na página do Google, opcional) | ler os seus calendários do Google sem passar pelo macOS; **só leitura**, token no Keychain, Desconectar revoga | os calendários do Mac continuam |
| **Microfone** | só no “Que música é essa?” (Shazam), quando você pede | sem o Shazam |
| **Gravação de áudio** (macOS 14.2+) | só no equalizador e nas barras que seguem o som — nada é gravado | sem equalizador |
| **Pastas** (Mesa, Downloads) | capturas e downloads entrando sozinhos na Prateleira | a Prateleira continua por arrastar |
| **Claude Code** (sem permissão do macOS) | Configurações › Agentes › Instalar: um script local e as linhas do Notchbar no `~/.claude/settings.json` | sem os agentes no notch |

- Nada de conta nem analytics. Rede: a checagem diária de atualização (um arquivo estático neste repositório), a confirmação da licença (só a key, um código do Mac — um hash —, o nome do Mac e a versão do app), com as letras ligadas a busca no LRCLIB (artista, título, álbum e duração) e, se você conectar o Google, as leituras do Google Agenda em seu nome — nada disso passa pela BigHeadStudios. Política completa: [privacidade](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/PRIVACY.md).

## Todas as versões

Cada versão continua disponível para download, com as suas notas. O app avisa sozinho quando sai uma nova (ícone verde no canto da bandeja) e se atualiza por dentro, conferindo a integridade do download.

<!-- VERSIONS:START -->
| Versão | Data | Download | Notas | SHA-256 |
|---|---|---|---|---|
| **2.0.3** **(atual)** | 30/10/2026 | [Notchbar-2.0.3.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-2.0.3.dmg) | [v2.0.3](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v2.0.3.md) | `5bf2c42f7cca…` |
| **2.0.2** | 30/10/2026 | [Notchbar-2.0.2.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-2.0.2.dmg) | [v2.0.2](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v2.0.2.md) | `11fbd3368d49…` |
| **2.0.1** | 28/10/2026 | [Notchbar-2.0.1.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-2.0.1.dmg) | [v2.0.1](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v2.0.1.md) | `c705c89b99fd…` |
| **2.0.0** | 28/10/2026 | [Notchbar-2.0.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-2.0.0.dmg) | [v2.0.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v2.0.0.md) | `7c43049d0150…` |
| **1.9.0** | 27/10/2026 | [Notchbar-1.9.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.9.0.dmg) | [v1.9.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.9.0.md) | `3ed52de00023…` |
| **1.8.1** | 20/10/2026 | [Notchbar-1.8.1.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.8.1.dmg) | [v1.8.1](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.8.1.md) | `6a17a2c33df6…` |
| **1.8.0** | 20/10/2026 | [Notchbar-1.8.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.8.0.dmg) | [v1.8.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.8.0.md) | `51ce1253c5d7…` |
| **1.7.0** | 20/10/2026 | [Notchbar-1.7.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.7.0.dmg) | [v1.7.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.7.0.md) | `5194af730925…` |
| **1.6.0** | 17/10/2026 | [Notchbar-1.6.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.6.0.dmg) | [v1.6.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.6.0.md) | `d48fc1e5e97e…` |
| **1.5.1** | 16/10/2026 | [Notchbar-1.5.1.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.5.1.dmg) | [v1.5.1](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.5.1.md) | `975a458e4082…` |
| **1.5.0** | 16/10/2026 | [Notchbar-1.5.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.5.0.dmg) | [v1.5.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.5.0.md) | `4db9cfa7af4b…` |
| **1.4.1** | 16/10/2026 | [Notchbar-1.4.1.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.4.1.dmg) | [v1.4.1](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.4.1.md) | `73a4639c8930…` |
| **1.4.0** | 16/10/2026 | [Notchbar-1.4.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.4.0.dmg) | [v1.4.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.4.0.md) | `69d54faa9c40…` |
| **1.3.0** | 16/10/2026 | [Notchbar-1.3.0.dmg](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/raw/main/versions/Notchbar-1.3.0.dmg) | [v1.3.0](https://github.com/andrecamellini01-ai/BigHeadStudios.Notchbar-releases/blob/main/release-notes/v1.3.0.md) | `b1d12dda45e9…` |
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
A bandeja passa a mostrar só “Ativar licença” e “Comprar”. Comprar abre o Pix dentro do app; com a licença ativa (ou colando uma key), tudo volta na hora.
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
<summary><b>Meus calendários do Google não aparecem.</b></summary>
<br>
Dois caminhos. Se a conta do Google está em Ajustes do Sistema › Contas da Internet com Calendários ligado, ela aparece na lista do Mac (Configurações › Agenda). Se não quer colocar a conta no macOS, use <b>Conectar Google</b> na mesma aba: login na página do Google, só leitura. Enquanto o app está em verificação no Google, esse caminho é liberado por e-mail de teste — peça o seu no suporte.
</details>

<details>
<summary><b>O Notchbar mexe no meu calendário?</b></summary>
<br>
Não. Ele só lê: nunca cria, altera, remove nem responde convites. Os eventos ficam na memória do app enquanto ele roda; nada é gravado nem enviado.
</details>

<details>
<summary><b>O que os Agentes mudam no meu Claude Code?</b></summary>
<br>
Só acrescentam “hooks” no <code>~/.claude/settings.json</code> (com backup ao lado) que avisam o Notchbar pelo próprio Mac — nenhum servidor. O comando só aparece no notch quando o Claude pede permissão; nada é gravado. Se o Notchbar estiver fechado, o script sai na hora e o Claude Code segue igual. Desinstalar tira só essas linhas.
</details>

<details>
<summary><b>O histórico de Copiados guarda minhas senhas?</b></summary>
<br>
Não. Vem desligado; ligado, fica só na memória (some ao sair do app) e ignora o que o macOS e os gerenciadores de senha marcam como senha — e tudo o que é copiado dentro deles.
</details>

<details>
<summary><b>Preciso do Limitbar?</b></summary>
<br>
Só para ver o limite do Claude no notch. O Notchbar lê o arquivo que o Limitbar grava no seu Mac (Limitbar › Integrações › “Gravar current.json”).
</details>

<details>
<summary><b>Em quantos Macs posso usar?</b></summary>
<br>
Em até **2 Macs** seus ao mesmo tempo. Trocou de Mac? No antigo: Licença › Remover licença deste Mac — a vaga fica livre para o novo.
</details>

---

<p align="center"><sub>Também da BigHeadStudios: <a href="https://github.com/andrecamellini01-ai/BigHeadStudios.Limitbar-releases"><b>Limitbar</b></a> — seus limites do Claude na barra de menu (e, com o Notchbar 2.0, no notch).</sub></p>

<sub>© 2026 BigHeadStudios. Notchbar é independente, sem afiliação com a Apple ou com os apps que controla. Leitura de mídia via <a href="https://github.com/ungive/mediaremote-adapter">mediaremote-adapter</a> (BSD-3-Clause).</sub>
