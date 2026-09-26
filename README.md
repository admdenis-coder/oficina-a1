# Oficina A1

Sistema web para um pequeno negócio de impressão 3D com Bambu Lab A1: pedidos de clientes, compras de filamento e estoque, cálculo de custo por impressão e preço de venda sugerido.

## Como usar
Abra o site publicado pelo GitHub Pages (Settings → Pages → Branch `main`, pasta `/root`) ou abra o `index.html` direto no navegador.

Os dados ficam salvos no navegador de quem usa (localStorage). Para levar os dados para outro aparelho, use **Parâmetros de custo → Baixar backup / Restaurar backup**.

## Premissas de custo (editáveis no app)
- Energia: 95 W de média imprimindo PLA ([Bambu Lab Wiki](https://wiki.bambulab.com/en/a1/manual/faq))
- Mão de obra: técnico júnior de impressão 3D, cerca de R$ 2.300/mês ([Jooble](https://br.jooble.org/salary/impress%C3%A3o-3d), [Glassdoor](https://www.glassdoor.com.br/Sal%C3%A1rios/tecnico-de-impressao-3d-sal%C3%A1rio-SRCH_KO0,23.htm))
- Depreciação: A1 a R$ 3.290 com 4.000 h de vida útil
- Preço = custo ÷ (1 − margem − taxa de venda)
