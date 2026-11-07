# Gears of War 2 — Português do Brasil 🇧🇷

Tradução e dublagem PT-BR para o **Gears of War 2** rodando no **COGBox** (PC).

## ⬇️ Download
Baixe na página de **[Releases](https://github.com/Gears2-PTBR/Gears2-PTBR/releases/latest)** o pacote
**`Gears2-PTBR-v1.2.zip`**. É um pacote só, com o jogo inteiro em português:

| Parte | O que tem |
|---|---|
| **Tradução** | Menus, HUD, textos e legendas em português |
| **Dublagem** | 3657 falas da campanha dubladas + 6 vídeos dublados |
| **DualSense** *(opcional, sem DSX)* | Gatilhos adaptáveis por arma, rádio e motosserra no alto-falante do controle |

Um instalador só instala a tradução e a dublagem juntas. O DualSense é uma opção do mesmo instalador.

## 🆕 v1.2
- **DualSense sem DSX e sem app:** agora roda dentro do jogo e é uma opção do instalador.
- A tradução, as vozes e os vídeos são os **mesmos da v1.1b**.
- **Já tem a v1.1b?** Só precisa atualizar se quiser o DualSense novo: abra o `Instalador.exe` da v1.2 e clique em **Só o DualSense**.

## ✅ Requisitos
- COGBox **0.3.7 ou mais novo**
- Gears of War 2 com a **Title Update 6**
- Para o som no DualSense: o controle no **cabo USB**

## 🛠️ Como instalar
1. Extraia o `.zip` dentro da pasta do COGBox e rode o `Instalador.exe`.
2. Confira a pasta do COGBox (a que tem o `CogBox.exe`), marque o DualSense se quiser e clique em **INSTALAR**.
3. No COGBox, em Gears of War 2:
   - aba **About** → marque o mod **Traducao PT-BR**;
   - aba **Gameplay** → **Game language** = **Italian** (o português entra no lugar do italiano).

O botão **Desinstalar** devolve tudo ao original.

## 🎮 DualSense (opcional)
Marque **Instalar também o DualSense** antes de clicar em **INSTALAR**. Já instalou sem ele? Abra o `Instalador.exe` de novo e clique em **Só o DualSense**: o resto fica como está.

**Não tem programa para abrir.** O DualSense é parte do plugin e liga sozinho quando o jogo abre, sem DSX e sem emulação de controle de Xbox. Se você usava a versão antiga, feche o DSX e o app antigo do DualSense, porque eles disputam o controle.

- **Gatilhos:** mudam com a arma na mão.
- **Rádio e motosserra no controle:** só com o **cabo USB**. Com som na TV ou caixa, saem no controle; com fone, o controle fica mudo.
- **Ajustes:** dê dois cliques em `DualSenseConfig.exe`, na pasta do COGBox. Lá você marca qual saída de som é a TV ou caixa e ajusta os volumes. Não precisa deixar aberto, e o que você muda vale na hora, mesmo com o jogo aberto.

Testado com cabo USB no COGBox 0.4.5. O controle precisa ser reconhecido pelo COGBox sem o DSX, o que depende de uma versão recente dele. Por Bluetooth os gatilhos usam outro formato de envio e ainda não foram testados.

## 🔄 Quando o COGBox atualizar
**Não precisa fazer nada.** A dublagem é um plugin que fica ao lado do COGBox
(`version.dll` + `gears2-ptbr.ini` em `Gears2\port-tu6`) e **não substitui nenhum arquivo dele**.
O DualSense vem no mesmo plugin e só lê a memória do jogo. O COGBox pode atualizar à vontade.

**Quem instalou a v1.0 ou a v1.0.1:** rode o `Instalador.exe` da v1.2 uma vez, por cima. Ele troca a
dublagem antiga pelo plugin e devolve o arquivo original do COGBox.

## ℹ️ Sobre
- As vozes foram geradas com IA (ElevenLabs), **sem clonar as vozes dos atores originais**.
- Os vídeos usam voice-over: o áudio original fica baixinho por baixo do português.
- **Nenhum arquivo do jogo é distribuído**: o instalador monta tudo a partir da sua cópia. Os sons da
  motosserra do DualSense também são tirados do seu jogo, no seu PC (com o FFmpeg, que vem junto).
- Feito para o [COGBox](https://github.com/Shagg88/COGBox) do Shagg. O plugin não modifica nenhum arquivo do COGBox.

## ☕ Apoie
Curtiu? O instalador tem um QR Code Pix pra quem quiser pagar um café e incentivar o trabalho.

Feito por **HubertFer**.
