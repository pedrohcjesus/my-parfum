# Compras: Mercado Livre primeiro, Amazon depois

Preço de referência dos perfumes. Regra do repositório: **Mercado Livre em primeiro lugar, Amazon em segundo, outros canais não**. Entre vários anúncios do mesmo perfume, vale o **mais barato de vendedor confiável**.

*Preços coletados em 07/11/2026. Mudam todo dia, e os links podem sair do ar. Confira antes de comprar.*

## Como escolhi o anúncio

1. Só frasco **novo** do tamanho certo (100 ml, ou 90 ml quando é o único), sem kit, refil, decant, miniatura ou "inspirado em".
2. Entre os mais baratos, abri o anúncio e conferi o vendedor: **selo MercadoLíder** e **número de vendas**.
3. Se o anúncio mais barato é de vendedor sem selo e com poucas vendas, listo também o mais barato **com selo MercadoLíder**.
4. O selo "Loja oficial" que aparece no texto da página nem sempre é confiável; só considero quando o próprio anúncio mostra "Loja oficial".

Um preço muito abaixo da mediana é sinal de alerta de **falsificação**, sobretudo em perfumes árabes populares (o Fragrantica registra risco de falsificação no Hawas Ice e no Hawas Black).

## Preços verificados no Mercado Livre

| Perfume | Mais barato confiável | Vendedor | Mediana | Anúncio |
|---|--:|---|--:|---|
| Natura **Homem Essence** 100 ml | **R$ 156,51** | JLCOSMETICS, MercadoLíder, +10 mil vendas | R$ 178 | [abrir](https://www.mercadolivre.com.br/deo-parfum-natura-homem-essence-100ml/up/MLBU3530238188) |
| Khadlaj **Shiyaaka Snow** 100 ml | **R$ 246,90** | BELOCOSMETICOSLTDA, MercadoLíder, +1.000 vendas | R$ 308 | [abrir](https://www.mercadolivre.com.br/khadlaj-shiyaaka-snow-eau-de-parfum-100ml/up/MLBU5810135052) |
| Maison Viegas **Heaven** 100 ml | R$ 252,86 (sem selo, +50 vendas) · **R$ 256,58 com MercadoLíder** | Zayen Perfumaria, +1.000 vendas | R$ 299 | [abrir](https://www.mercadolivre.com.br/maison-viegas-heaven-100ml-original/up/MLBU3858077431) |
| Rasasi **Hawas for Him** 100 ml | **R$ 178,19** | Rocha Importados, loja oficial, MercadoLíder Platinum, +50 mil vendas | R$ 231 | [abrir](https://www.mercadolivre.com.br/perfume-rasasi-hawas-for-him-masculino-edp-100ml/up/MLBU3758648651) |
| Natura **Essencial Único** masculino **90 ml** | cerca de **R$ 172 a R$ 175** | vendedor não verificado | n/d | buscar "essencial único masculino 90ml" |

Observações:
- **Heaven:** os R$ 129 do site da marca não aparecem no Mercado Livre. Lá, o preço é de R$ 253 a R$ 299.
- **Shiyaaka Snow:** a estimativa anterior de R$ 266 a R$ 340 estava alta; no Mercado Livre sai por cerca de R$ 247.
- **Hawas for Him:** um dos anúncios baratos é na verdade o "Hawas for Him Malibu", outro perfume. Confira o nome exato.
- O **Essencial Único** é vendido em **90 ml**, não 100 ml, então o preço por ml é maior do que parece.

## Preços estimados (não verificados no Mercado Livre)

Depois de cerca de uma dúzia de buscas e aberturas de anúncios seguidas, o Mercado Livre passou a pedir login (bloqueio automático) e eu **parei, sem tentar contornar**. Para os três abaixo, só tenho valores soltos do Google, sem confirmar vendedor nem tamanho.

| Perfume | Faixa estimada | Leitura |
|---|---|---|
| Rasasi **Hawas Ice** 100 ml | R$ 200 a R$ 300 | O Fragrantica cita "inflação de preço por causa do hype" e **alto risco de falsificação** (424 votos). Compre só de vendedor MercadoLíder com muitas vendas. |
| Natura **Kaiak Aero** 100 ml | R$ 90 a R$ 120 | Bem barato. |
| Afnan **Supremacy Collector's Edition** 100 ml | R$ 315 a R$ 570 | **Acima do seu teto de R$ 300.** |

Para fechar esses três, abra o Mercado Livre no Safari, faça login e peça para eu repetir a consulta. Eu não coloco senha nem entro na sua conta.

## Como repetir a consulta

Com a skill `claude-for-safari`, use **uma aba nova, em primeiro plano** (o Safari não carrega abas escondidas), faça **no máximo 3 a 4 buscas por vez** e espere alguns minutos entre rodadas. A busca está em `lista.mercadolivre.com.br/<termos-com-hifen>`, e os anúncios são os itens `li.ui-search-layout__item`. Preço atual em `.poly-price__current` e, no anúncio, vendedor, selo MercadoLíder e vendas.
