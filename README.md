# rota6-site

Site público da Rota 6, publicado em https://rota6.com.br pela Hostinger a partir do branch `main` deste repositório.

## Como atualizar as ofertas

Edite só o arquivo `ofertas.json`; a página lê esse arquivo e monta os cards sozinha.

- `atualizado_em`: data da consulta dos preços (AAAA-MM-DD).
- `whatsapp_link` / `instagram_link`: quando preenchidos, os botões passam a apontar para eles.
- Cada item de `ofertas`: `categoria`, `produto`, `loja`, `preco`, `observacao`, `link`, `afiliado` (true quando o link for de afiliado), `destaque` (true para aparecer primeiro).

Regras:
- Nunca colocar preço sem ter conferido na loja na data de `atualizado_em`.
- Link de afiliado sempre com `"afiliado": true`.
- Não usar logo, arte ou fonte oficial da Rockstar.

Este repositório é público e contém apenas o site. Roteiros, skills e o guia ficam no repositório `gta-6`.
