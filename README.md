# Horto Ville III | Página de apresentação

Página de apresentação do empreendimento, com fotos sem textos, planta de implantação, condições "a partir de", vídeo de localização e botão de cadastro para o lançamento (26 e 27 de novembro, exclusivo para cadastrados), que leva ao WhatsApp do corretor Klebson Souza (CRECI-BA 37964).

## Arquivos (todos na raiz do repositório)

`index.html`, `hv3-trajeto.mp4`, `hv3-trajeto-capa.jpg`, `hv3-aerea.jpg`, `hv3-entrada.jpg`, `hv3-playground.jpg`, `hv3-pets.jpg`, `hv3-esporte.jpg`, `hv3-implantacao.jpg`, `hv3-klebson.jpg`, `.nojekyll`

## Vídeo de localização e trajeto

O vídeo `hv3-trajeto.mp4` (sobrevoo vertical, cerca de 20 MB) já está ligado à página. Para trocar, substitua o arquivo mantendo o mesmo nome ou altere `VIDEO_MP4` / `VIDEO_YOUTUBE` / `MAPS_URL` no bloco "EDITE AQUI", no final do `index.html`.

Se for subir pelo navegador do GitHub, cada arquivo pode ter até 25 MB. Mantenha o vídeo abaixo disso.

## Outros ajustes

- WhatsApp e mensagem do cadastro: variáveis `WHATSAPP` e `MENSAGEM`, no mesmo bloco.
- Datas do lançamento e contagem regressiva: procure `Contagem regressiva` no final do `index.html` e ajuste as datas (formato `2026-11-26T00:00:00-03:00`).
- Pixel do Facebook: cole o código no comentário `META PIXEL` dentro do `<head>`. Cada clique no botão registra o evento `Contact`.
- Valores, desconto à vista (20%), regra dos 40% e dúvidas frequentes: edite as seções "Condições especiais de pagamento", "Como funciona" e "Dúvidas frequentes" do `index.html` quando a tabela ou as regras mudarem.
- O botão do WhatsApp é fixo: barra na base da tela no celular e botão flutuante no computador.

## Publicação

Settings > Pages > Deploy from a branch > `main` > `/ (root)`. O `index.html` precisa ficar na raiz, não dentro de uma pasta.
