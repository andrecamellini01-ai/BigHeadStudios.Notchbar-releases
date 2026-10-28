# Política de Privacidade

_Notchbar para macOS · BigHeadStudios · vigente a partir de 28 de outubro de 2026 (Notchbar 2.0)_

O Notchbar é um app que roda no seu Mac. Ele foi feito para **não ter conta, não ter cadastro e não coletar dados**. Esta página descreve, por função, o que o app lê, onde guarda e o que sai do computador — e, em especial, como trata os dados do Google Agenda quando você conecta sua conta.

## Resumo
- Não há conta do Notchbar, telemetria, analytics nem anúncios.
- O conteúdo que o app mostra (música, letras, calendário, bateria, Bluetooth, Foco, agentes do Claude Code, área de transferência, capturas, downloads) é lido no seu Mac e fica no seu Mac.
- As únicas conexões de rede são: a letra da música (LRCLIB), a confirmação da licença, a checagem de atualização, se você conectar, o Google Agenda e, quando você pede “Que música é essa?”, o Shazam. Nenhuma delas recebe conteúdo pessoal além do descrito abaixo.

## O que cada função usa

| Função | Dados lidos | Onde ficam | Sai do Mac? |
|---|---|---|---|
| Player (o que o Mac está tocando) | título, artista, capa, posição, app de origem (Now Playing do macOS) | só em memória | Não |
| Letras | artista, título, álbum e duração da faixa | cache local de letras | Sim: só esses quatro campos, para lrclib.net (desligável em Mídia) |
| Spotify / Música (Automação) | volume, fila, favoritos do app escolhido | só em memória | Não |
| HUD, bateria, Bluetooth, Foco, limpeza do teclado | nível de volume/brilho, carga, acessórios conectados, modo Foco ativo | só em memória | Não |
| Agenda (calendários do macOS) | título, horário, local, link e notas dos eventos dos calendários que você escolher, para montar o lembrete e a aba Hoje | só em memória, enquanto o app roda | Não |
| Agenda (Google, opcional) | lista de calendários e os eventos das próximas horas — veja a seção abaixo | eventos só em memória; um token de acesso no Keychain do app | Sim: pedidos de leitura ao Google, em seu nome. Nada vai para a BigHeadStudios |
| Licença | a sua key, um identificador do Mac (hash, não o número de série), o nome do Mac e a versão do app | Keychain e preferências | Sim: para o servidor de licenças da BigHeadStudios, para confirmar a ativação |
| Atualizações | nenhum dado pessoal | — | Sim: uma consulta diária ao arquivo de versões no GitHub |
| Agentes do Claude Code (opcional) | os eventos que o Claude Code passa aos hooks: pasta do projeto, ferramenta em uso, o comando/arquivo de um pedido de permissão, o fim da resposta | cada evento é um arquivo temporário em `~/Library/Application Support/Notchbar/agents`, apagado assim que o app lê; o resto só em memória | Não |
| Limite do Claude (Limitbar) | os números do `current.json` que o Limitbar grava no seu Mac (percentuais, horários de reset, nomes das contas) | só em memória | Não |
| Copiados (opcional, desligado por padrão) | o que você copia (texto, links, arquivos, imagens); ignora o que vem marcado como senha e cópias em gerenciadores de senha | só em memória — some ao sair do app | Não |
| Capturas e downloads (opcional) | os arquivos novos dessas pastas (só o caminho e a miniatura) | caminhos nas preferências, como a Prateleira | Não |
| Câmera e microfone em uso | se estão em uso e o nome do app que usa | só em memória | Não |
| Equalizador e barras do som (opcional) | o áudio do Mac, processado em tempo real | nada é gravado | Não |
| “Que música é essa?” (sob pedido) | alguns segundos do som ambiente, pelo microfone | nada é gravado | Sim: uma assinatura do áudio (não o áudio) para o Shazam da Apple |
| Tradução da letra (opcional) | as linhas da letra | — | Não: a tradução é feita no próprio Mac (o macOS pode baixar o idioma) |

## Google Agenda (Google Calendar API)

Conectar o Google é opcional. Quando você conecta, o Notchbar pede ao Google a permissão **“Ver eventos de todos os seus calendários”** (escopo `calendar.readonly`) e usa esses dados **apenas** para:

- mostrar a próxima reunião no notch (título, horário, serviço de vídeo) e o botão Entrar com o link do evento;
- listar os eventos do dia na aba Hoje;
- deixar você escolher, nas configurações, quais calendários entram.

**O Notchbar nunca cria, altera, remove nem responde eventos.** Os dados do calendário ficam somente na memória do app enquanto ele está aberto; não são gravados em disco, não são enviados à BigHeadStudios nem a terceiros, não são usados para publicidade e não são lidos por pessoas. O que fica guardado é o **token de acesso** do Google, no Keychain do seu Mac, para o app sincronizar sem pedir login de novo. “Desconectar”, nas configurações, apaga o token e revoga o acesso no Google; você também pode revogá-lo em [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

O uso de informações recebidas das APIs do Google pelo Notchbar segue a [Política de Dados do Usuário dos Serviços de API do Google](https://developers.google.com/terms/api-services-user-data-policy), inclusive os requisitos de **Uso Limitado** (Limited Use).

## O que não fazemos
- Não vendemos, alugamos nem compartilhamos dados pessoais.
- Não usamos cookies, rastreadores ou identificadores de publicidade.
- Não guardamos cópia dos seus calendários, músicas ou mensagens.

## Seus controles
- Cada função é um interruptor nas Configurações do app; desligar apaga o que estava em memória.
- Permissões do macOS (Calendários, Acessibilidade, Automação, Bluetooth, Microfone, Gravação de Áudio, Arquivos e Pastas) podem ser revogadas em Ajustes do Sistema › Privacidade e Segurança.
- Agentes: Configurações › Agentes › Desinstalar tira as linhas do Notchbar do `~/.claude/settings.json`.
- Para remover tudo: apague o app, a pasta `~/Library/Application Support/Notchbar` e o cache de letras em `~/Library/Caches/Notchbar`.

## Mudanças e contato

Se esta política mudar, a data no topo é atualizada e a versão nova fica nesta mesma página. Dúvidas ou pedidos sobre seus dados: suporte — veja o rodapé do site.

---

© 2026 BigHeadStudios. Notchbar é um app independente, sem afiliação com a Apple ou o Google. Google Agenda e Google Calendar são marcas da Google LLC.
