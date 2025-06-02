# 💰 Investment Tool
Essa é uma ferramenta criado com o objetivo de simular investimentos com base no perfil do investidor, sua renda mensal, valor em mente a ser investido, e no rendimento deste valor a longo prazo.

<p align="center">
  <img src="https://github.com/user-attachments/assets/48b8681b-5731-4c80-bc6f-8f12f368971d" alt="cat counting dollar bills">
</p>

O simulador conta com 4 ferramentas:
- Configurações
- Investimento Mensal
- Cenários
- Perfil

# Como Funciona?

## Configurações ⚙️
Essa ferramenta conta o input do investidor referente ao seu salário e rendimento de carteira e, com base nessas informações, será gerado uma sugestão de investimento de 30%.

**Exemplo:**

<table>
  <tr><td>Salário</td><td>R$ 1.500,00</td></tr>
  <tr><td>Rendimento de Carteira</td><td>0,60%</td></tr>
  <tr><td>Sugestão de Investimento (30%)</td><td>R$ 450,00</td></tr>
</table>

Vale ressaltar que a recomendação de investir 30% com base nos valores infomrados é uma regra prática, não fixa. Começar com 5% ou 10% já é válido.

## Investimento Mensal 💸
Após inserir os valores nas **Configurações**, o investidor deve definir um valor a ser investido regularmente por uma certa quantidade de anos. Dessa maneira, a ferramenta retornará o patrimônio acumulado e os dividendos mensais.

**Exemplo:**

<table>
  <tr><td>Valor a Ser Investido?</td><td>R$ 150,00</td></tr>
  <tr><td>Por Quantos Anos?</td><td>5</td></tr>
  <tr><td>Taxa de Rendimento Mensal</td><td>1,08%</td></tr>
  <tr><td>Patrimônio Acumulado</td><td>R$ 12.566,54</td></tr>
  <tr><td>Dividendos Mensais</td><td>R$ 75,40</td></tr>
</table>

## Cenários 💡
Uma vez que a quantidade de anos e valores estão definidos, os cenários darão ao investidor uma visão de quanto de patrimônio acumulado ele terá a longo prazo. Isto é, se o valor definido for investido regularmente.

**Exemplo:**

<table>
    <thead>
    <tr>
      <th colspan="2">Patrimônio Acumulado em...</th>
      <th>Dividendos</th>
    </tr>
  </thead>
  <tbody>
      <tr><td>2 anos</td><td>R$ 4.084,14</td><td>R$ 24,50</td></tr>
      <tr><td>5 anos</td><td>R$ 12.566,54</td><td>R$ 75,40</td></tr>
      <tr><td>10 anos</td><td>R$ 36.492,63</td><td>R$ 218,96</td></tr>
      <tr><td>20 anos</td><td>R$ 168.779,76</td><td>R$ 1.012,68</td></tr>
      <tr><td>30 anos</td><td>R$ 648.325,45</td><td>R$ 3.889,95</td></tr>
  </tbody>
</table>

## Perfil 🧠
Por fim, o investidor poderá selecionar o seu tipo de perfil, podendo escolher entre as seguintes opções:

- Conservador
- Moderado
- Agressivo

Assim que seu perfil for selecionado, será sugerido um percentual a ser investido em cada tipo de FII (Fundo de Investimento Imobiliário), seguido dos valores, tendo o valor definido em **Investimento Mensal** como limite.

**Exemplo:**

<table>
  <tr><td>Perfil</td><td>Agressivo</td></tr>
  <tr><td>Valor a Ser Investido</td><td>R$ 150,00</td></tr>
</table>

<br>

<table>
    <thead>
    <tr>
      <th>Tipo de FII</th>
      <th>Percentual Sugerido</th>
      <th>Valores</th>
    </tr>
  </thead>
  <tbody>
      <tr><td>Papel</td><td>50%</td><td>R$ 75,00</td></tr>
      <tr><td>Tijolo</td><td>10%</td><td>R$ 15,00</td></tr>
      <tr><td>Híbrido</td><td>5%</td><td>R$ 7,50</td></tr>
      <tr><td>FOFs</td><td>5%</td><td>R$ 7,50</td></tr>
      <tr><td>Desenvolvimento</td><td>20%</td><td>R$ 30,00</td></tr>
      <tr><td>Hotelarias</td><td>10%</td><td>R$ 15,00</td></tr>
  </tbody>
</table>

# Considerações Finais 📌
Essa ferramenta de investimento pode ser muito útil tanto para aqueles que gostariam de ter uma noção melhor do quão benéfico investir pode ser a longo prazo, mesmo que o investimento seja um valor consideravelmente baixo.

Por questão de costume (e também de preferência), essa ferramenta foi feita inteiramente em inglês. No entanto, ela pode ser facilmente manuseada através deste README, que está perfeitamente detalhado sobre seu uso e objetivos. Dito isso, a funcionalidade desta ferramenta de investimentos independe do idioma para ser eficaz.
