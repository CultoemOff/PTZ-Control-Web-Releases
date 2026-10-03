# PTZ Control Web — by Culto em Off

**PTZ Control Web – Free PTZ Camera Controller for OBS, vMix & SPresenter**

[Português](README.md) · [English](README.en.md) · [Español](README.es.md)

[⬇️ Download para Windows](https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest)

Controle câmeras PTZ diretamente pelo navegador, dentro do seu software de produção ou como painel independente.

O **PTZ Control Web — by Culto em Off** é uma interface local para controle de câmeras PTZ. Ele foi pensado para igrejas, transmissões ao vivo, produções audiovisuais e equipes que precisam de um controle simples e compacto.

O programa roda localmente no Windows e a interface é acessada pelo navegador. Também pode ser adicionada diretamente ao **OBS Studio como Custom Browser Dock**.

## 📥 Download

Baixe sempre a versão mais recente em:

https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest

Em **Assets**, baixe:

- `PTZ-Control-Web-Setup.exe`
- `SHA256SUMS.txt` — hash SHA-256 para verificação da integridade do instalador.

## 🖥️ Instalação

1. Baixe `PTZ-Control-Web-Setup.exe`.
2. Execute o instalador.
3. Conclua a instalação normalmente.
4. O PTZ Control Web será configurado para iniciar junto com o Windows.
5. Um atalho **PTZ Control Web** será criado para abrir o painel no navegador.

O servidor funciona localmente no computador e não precisa de conexão com a internet para controlar as câmeras da rede local.

## 🌐 Como abrir o PTZ Control Web

Depois de instalar, abra:

`http://127.0.0.1:8765/obs`

Você pode salvar esse endereço nos favoritos do navegador.

Se preferir, utilize o atalho **PTZ Control Web** criado durante a instalação.

> O endereço `127.0.0.1` significa que o servidor está rodando no próprio computador. Por padrão, a interface não fica exposta para outros dispositivos da rede.

## 🎥 Como adicionar no OBS Studio

No OBS Studio, abra:

**Painéis → Painéis de navegador personalizados**

Em instalações em inglês:

**Docks → Custom Browser Docks**

Crie um novo painel usando:

**Nome:** `PTZ Control Web`

**URL:** `http://127.0.0.1:8765/obs`

Clique em **Aplicar**. O painel aparecerá dentro do OBS e pode ser arrastado e encaixado junto aos demais painéis.

## 🎛️ Onde funciona

- **OBS Studio** como Custom Browser Dock
- **vMix**
- **SPresenter**
- navegador
- **Bitfocus Companion**
- controle USB/Gamepad

Como o controle funciona por meio de um servidor local e do navegador, ele não depende de um plugin interno específico do OBS Studio.

## 🎥 Funcionalidades

- Pan, Tilt e Zoom
- movimento diagonal
- Home
- Focus Near / Far
- Autofocus
- velocidade Pan/Tilt ajustável
- presets com gravação, chamada e nomes personalizados
- suporte para até **8 câmeras**
- painel com até **4 câmeras por linha**
- Português, Inglês, Espanhol e Alemão
- tema claro e escuro
- quantidade de presets configurável
- layout horizontal ou vertical
- opção de ocultar controles PTZ
- controle por Gamepad USB
- integração HTTP com Bitfocus Companion
- configurações persistidas localmente
- Auto Tracking em câmeras ONVIF compatíveis

## 📷 Protocolos e perfis

Protocolos suportados:

- **VISCA over IP — UDP**
- **VISCA over IP — TCP**
- **VISCA USB / Serial**
- **ONVIF**

Perfis de fabricantes:

- **Genérico**
- **AVer**
- **Telycam**
- **PTZOptics**
- **Sony**

O perfil **Genérico** pode ser usado em câmeras compatíveis que não estejam listadas.

Alguns recursos, como **Auto Tracking**, dependem do suporte disponibilizado pela própria câmera.

## 🎮 Controle USB / Gamepad

O mapeamento inclui joystick esquerdo para Pan/Tilt, gatilhos para Zoom, botões superiores para Focus, direcional para selecionar presets e botões para chamar, salvar e acionar Autofocus.

## 🔲 Bitfocus Companion

A integração HTTP permite criar botões no Companion para movimento, parada, Zoom, Focus, Autofocus, Home, chamada de presets e gravação de presets.

## 🔐 Segurança

Por padrão, o servidor escuta somente em:

`127.0.0.1`

Isso significa que a interface e a API ficam acessíveis apenas no computador onde o programa está instalado.

As configurações das câmeras ficam armazenadas localmente.

## 🔎 PTZ Camera Controller

PTZ Control Web é um controlador gratuito de câmeras PTZ baseado em navegador para **OBS Studio, vMix e SPresenter**, com suporte a **VISCA over IP (UDP/TCP)**, **VISCA USB/Serial**, **ONVIF**, presets, Pan/Tilt/Zoom, foco, controle USB/Gamepad, Auto Tracking em dispositivos compatíveis e integração HTTP com **Bitfocus Companion**.

**Keywords:** PTZ controller, PTZ camera controller, PTZ web controller, OBS PTZ controller, VISCA controller, VISCA over IP, ONVIF PTZ, USB PTZ controller, Bitfocus Companion PTZ, vMix PTZ, SPresenter PTZ, church livestream PTZ.

## 🎥 Sobre o Culto em Off

O **Culto em Off** é um canal criado para compartilhar conhecimento prático sobre **áudio, vídeo, transmissão e tecnologia para igrejas**.

O conteúdo passa por mesas de som e áudio ao vivo, OBS Studio e streaming, câmeras e PTZ, NDI, iluminação e automação, REAPER, Holyrics, SPresenter, redes, integração de equipamentos e tutoriais de ferramentas usadas nos bastidores de cultos e eventos.

▶️ **YouTube:** https://www.youtube.com/@CultoemOff

---

**PTZ Control Web — by Culto em Off**

Projeto criado por **Jonas — Brasil 🇧🇷**
