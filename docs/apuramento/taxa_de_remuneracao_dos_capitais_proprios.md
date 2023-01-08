---
hide:
  - toc
---

# Taxa de remuneração dos capitais próprios

O modelo *Capital Asset Pricing Mode*l (_CAPM_), desenvolvido por Treynor (1962), Sharpe (1964), Lintner (1965) e Mossin (1966), é a metodologia comumente utilizada para a determinação do retorno exigido por um investidor num determinado ativo financeiro. De acordo com o _CAPM_, o prémio de risco vem expresso em função de um coeficiente de risco sistemático, também designado por coeficiente beta de risco sistemático.[^1] No entanto, o CAPM, como qualquer outro modelo financeiro, tem subjacente um conjunto de pressupostos, a saber:[^2] (_i_) os mercados são completos, não apresentam fricções e são de concorrência perfeita; (_ii_) os investidores são tomadores de preços; (_iii_) os ativos são perfeitamente divisíveis e líquidos; (_iv_) ausência de restrições às atividades de venda de ativos de curto e longo prazo; (_v_) ausência de custos de transação ou impostos e de oportunidades de arbitragem; (_vi_) os investidores são avessos ao risco e maximizam, com referência a um só período, a utilidade esperada da sua riqueza terminal; (_vii_) a seleção de carteiras de ativos por parte dos investidores é efetuada de acordo com o critério da média-variância; (_viii_) as atividades de obtenção e concessão de financiamento são irrestritas e executadas a uma taxa isenta de risco exógena e não estocástica; e (_ix_) os investidores apresentam expectativas homogéneas sobre a distribuição de probabilidade dos títulos e, consequentemente, sobre a média, variância e covariância dos retornos dos ativos financeiros.

Sob os pressupostos supra, os referidos autores demonstraram que os retornos esperados ex ante de um ativo financeiro pode ser determinado, em equilíbrio, por:

<p id="eqn_5"></p>

$$
E\left( R_{I} \right) = R_{F} + \left\lbrack {E(R}_{M}) - R_{F} \right\rbrack \times \frac{cov(R_{I};R_{M})}{\sigma_{M}^{2}}
$$

onde:

- $E(R_I)$ representa o retorno esperado a um período do ativo financeiro _I_.
- $R_F$ representa uma medida do retorno do ativo isento de risco a um período.
- $E(R_M)$ representa o retorno esperado a um período da carteira de mercado.
- $cov(R_{I};R_{M})$ representa a covariância entre o retorno do ativo _I_ e o retorno da carteira de mercado _M_.
- $\sigma^{2}_M$ representa a variância do retorno da carteira do mercado.[^3]

Este modelo baseia-se na hipótese de que a taxa de retorno (_ex ante_) exigida pelos investidores em qualquer ativo é linear e dada pela soma da taxa de retorno do ativo isento de risco $R_F$ com um ajustamento pelo risco, designado por prémio de risco. O quociente entre a covariância do retorno do ativo I e do retorno da carteira do mercado e a variância do retorno da carteira do mercado é designado por coeficiente beta de risco sistemático ($\beta$) de um ativo individual _I_:

<p id="eqn-6"></p>

$\beta_{I} = \frac{cov(R_{I};R_{M})}{\sigma_{M}^{2}}$

O _CAPM_ é relevante porque se consubstancia num poderoso e intuitivo instrumento de medida do risco e da relação entre retornos esperados e risco. No entanto, a aplicação prática do modelo reveste-se de fortes dificuldades como resultado de assentar em muitos pressupostos caracterizadores de um mercado de capitais sem imperfeições nem atritos no seu funcionamento e que não se encontram no ‘mundo real’ \[_vide_ Fama e French (2004)\].

O retorno exigido por um acionista depende do risco que enfrenta, o qual tem que ver com o tipo de contrato que estabelece: contrato financeiro de ações. Na aferição deste risco é prática generalizada utilizar o CAPM; ou seja, a taxa de retorno exigida $(R_E)$ é determinada de acordo com o grau de risco sistemático do ativo, sendo então função do retorno de um ativo sem risco $(R_F)$ e de um prémio de risco $(R_{M} - R_{F}) \times \beta$:

<p id="eqn-7"></p>

$R_{E} = R_{F} + (R_{M} - R_{F}) \times \beta$

Desta forma, o retorno exigido por um acionista depende, e porque os restantes parâmetros são constantes num determinado momento do tempo, do coeficiente beta ou coeficiente de risco sistemático. Tal retorno será tão mais elevado quanto maior for este coeficiente; i.e., quanto maior for o risco de uma ação maior será o

$\beta$ e, por isso mesmo, maior será o retorno exigido por um acionista. Em termos económicos, o coeficiente beta não é mais do que uma medida de sensibilidade do retorno esperado do ativo face a variações unitárias do retorno da carteira de mercado.

Na prática, como não existem ativos sem risco nem a carteira de mercado, são utilizadas aproximações ao cálculo destas medidas. Quanto à taxa sem risco ($R_F$), esta deverá observar os atributos básicos do ativo sem risco; i.e., com volatilidade nula ou muito próxima deste valor, sem risco de crédito, ou de outra qualquer natureza, como sejam o risco de prazo ou o risco de liquidez, e de reinvestimento e duração idêntica aos _cash flows_ que visa atualizar. A opção mais consensual passa pela utilização de Obrigações do Tesouro de cupão zero de longo prazo ou com a mesma maturidade do investimento e denominadas na mesma moeda. No que respeita à taxa de retorno esperada do mercado ($R_M$), é vulgar a utilização de um índice de mercado de ações com elevado número de ativos como aproximação, já que existe uma relação positiva entre os níveis de diversificação de carteira e o número de oportunidades de investimento em ativos de risco. Esta taxa representa então a taxa de variação (relativa) esperada de índices de mercado, tais como o Euro Stoxx 600 para a Europa ou o S&P 500 para os EUA.

Finalmente, o coeficiente beta de risco sistemático pode ser determinado com base em duas metodologias, a saber: (_i_) método conceptual – determinação da covariância do retorno da ação e do mercado e divisão pela variância do retorno do mercado; (_ii_) método de regressão – através, p.e., do modelo do índice único. Contudo, as duas metodologias exigem que a ação seja transacionada em mercado bolsista, o que não é na grande maioria das vezes o caso. Quando tal acontece, a solução passa pelo conceito de ativo de referência, ativo real ou financeiro que possui duas características de base: (_i_) ativo no mesmo setor de atividade do ativo a ser avaliado; e (_ii_) existência de dados históricos de mercado disponíveis que permitam a determinação de um beta do negócio. Inúmeras entidades financeiras fazem estes cálculos e oferecem betas para empresa cotadas, para setores de atividade e para diferentes regiões (e.g., Standard & Poors, Bloomberg, Merryl-Lynch, Barra, Value-Line, Damodaran e REFINITIV).[^4]

Para o setor de atividade selecionado (Green & Renewable Energy), sugere-se uma taxa de remuneração dos capitais próprios de 7,86%, tal como se constata pela análise da [Tabela 1](#tbl-1). 

<p markdown id="tbl-1">**Tabela 1 - Taxa de remuneração dos capitais próprios**</p>

| Componentes                                       |  $R_E$ |
|:--------------------------------------------------|-------:|
| $r_F$ = taxa de juro isenta de risco [^1]         |  2,50% |
| $r_M - r_F$ = prémio de risco de mercado          |  6,12% |
| $\beta_A$ = beta dos ativos                       |   0,64 |
| $\beta_E$ = beta dos capitais próprios            |   0,88 |
| $D/(E + D)$ = estrutura de capital                | 32,52% |
| $r_E$ = taxa de remuneração dos capitais próprios |  7,86% |

!!! note

    1. A taxa de juro isenta de risco inclui o prémio de risco soberano. 
    2. A metodologia de estimação de cada parâmetro apresentado, bem como os pressupostos de base utilizados, estão plasmados em cada uma das secções seguintes.

[^1]:
     O risco total de um ativo financeiro pode ser dividido em risco não sistemático ou específico e em risco sistemático ou de mercado. O primeiro corresponde ao nível de risco suscitado por fatores de risco específicos do ativo e que pode ser reduzido ou mesmo eliminado por uma diversificação adequada (risco diversificável). Já o segundo corresponde ao nível de risco suscitado por fatores de risco de impacto global, que afetam os retornos de todos os ativos, e que não pode ser reduzido com qualquer estratégia de diversificação (risco não diversificável).

[^2]:
    Tal como refere Perold (2004), “_These assumptions represent a highly simplified and idealized world, but are needed to obtain the CAPM in its basic form._”

[^3]: Para análise do desenvolvimento matemático do CAPM ver Copeland e Weston (1988)

[^4]:
    Para mais detalhe ver, entre outros, Damodaran (2001, 2006) e Koller _et al_. (2010). Ver ainda o website do Professor Aswath Damodaran com vários exemplos da aplicação do CAPM à determinação da taxa de retorno exigida para o investimento numa ação; i.e., da taxa de retorno exigida por um acionista: <https://pages.stern.nyu.edu/~adamodar/>
