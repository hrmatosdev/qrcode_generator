# Gerador de QR Code

Sistema front-end 100% client-side para gerar QR Codes de URLs, redes sociais e redes Wi-Fi, tudo em um único arquivo HTML.

## Funcionalidades

- **Site / URL** — insira qualquer link para gerar um QR Code
- **Rede Social** — escolha entre Instagram, X/Twitter, Facebook, LinkedIn, WhatsApp, TikTok, YouTube ou Telegram e informe o nome de usuário
- **Wi-Fi** — gere um QR Code que permite conexão automática à rede informando SSID, senha, tipo de segurança (WPA, WEP ou aberta) e se a rede é oculta
- **Download PNG** — baixe o QR Code gerado como imagem

## Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Selecione o tipo de conteúdo no menu suspenso
3. Preencha os campos exibidos
4. Clique em **"Gerar QR Code"** ou pressione **Enter**
5. Pronto! Clique em **"Baixar PNG"** para salvar a imagem

## Tecnologias

- HTML, CSS e JavaScript puros (sem frameworks)
- [qrcodejs](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js) via CDN para renderização dos QR Codes
- Design responsivo com glassmorphism e tema escuro

## Estrutura

```
index.html   — único arquivo do sistema (CSS e JS inline)
```

## Observações

- Nenhuma instalação ou servidor é necessária
- Tudo roda localmente no navegador, sem envio de dados para backend
- O QR Code de Wi-Fi segue o padrão `WIFI:T:tipo;S:ssid;P:senha;H:oculto;;`

# Créditos
- Nome: Henrique Rodrigues de Matos
- e-mail: hrmatosdev@gmail.com
- Instagram: @linkbhtecnologia
- Facebook: @linkbhtecnologiaofc
