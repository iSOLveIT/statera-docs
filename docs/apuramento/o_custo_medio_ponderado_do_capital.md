---
hide:
  - toc
---

# O custo médio ponderado do capital (WACC)

Como foi referido anteriormente, o modelo _free cash flow/WACC_ permite avaliar uma empresa ou projeto de investimento como um todo (i.e., os seus ativos), sendo o _cash flow_ periódico aquele que remunera o capital investido e independente da forma como o investimento é financiado (antes de decisões de financiamento). Este _cash flow_ designa-se então por _free cash flow_ (FCF), onde _free_ significa “livre” ou “disponível”, neste caso disponível para remunerar e reembolsar o capital investido. O capital é investido por acionistas, os quais investem capital próprio – tipicamente representado por ações –, e por credores financeiros, os quais investem endividamento – tipicamente representado por financiamento bancário ou títulos de dívida emitidos em mercado (obrigações ou papel comercial). Se os acionistas são tipicamente remunerados através do pagamento de dividendos, já os credores financeiros são remunerados através dos juros, reembolsos de capital e eventuais comissões cobradas.

A taxa de atualização dos _cash flows_ é a taxa de custo de oportunidade do capital investido, a qual é, por definição, a melhor taxa de retorno obtida em aplicações de risco equivalente que o mercado oferece. Trata-se, por isso mesmo, de uma taxa de mercado que pode ser encontrada no mercado financeiro considerando alternativas de risco similar. Adicionalmente, a taxa de desconto deve ser consistente com os conceitos de _cash flow_ utilizados. Desta forma, e porque o _free cash flow_ fica disponível para remunerar acionistas e credores financeiros, a taxa de atualização deve considerar o retorno exigido por cada um destes financiadores.

O retorno exigido por acionistas e credores financeiros depende do perfil de risco dos contratos que celebram. Os contratos celebrados pelos acionistas conferem direitos residuais aos _cash flows_ (dividendos) e direitos de controlo, atribuindo-lhes, por isso mesmo, um perfil mais agressivo de risco e retorno – numa situação de liquidação da empresa apenas recebem _cash flows_ depois de todos os restantes credores verem os seus créditos liquidados. Já os contratos celebrados pelos credores financeiros conferem direitos contratuais aos _cash flows_ (juros e capital) sem direitos de controlo, atribuindo-lhes, por isso mesmo, um perfil mais defensivo de risco e retorno – credores financeiros enfrentam menor risco porque podem executar a empresa (i.e.; pedir a liquidação dos ativos se não houver suficiente _cash flow_ para pagar os juros e reembolso tempestivo do capital).

Como a remuneração exigida por acionistas e credores financeiros é então distinta (inferior para os credores financeiros por comparação com os acionistas), deve ser utilizada uma média ponderada, designada por taxa de custo médio ponderado do capital ou _weighted average cost of capital_ (_WACC_), em terminologia anglo-saxónica:

<p id="wacc-eq"></p>

$$
WACC = R_E \times W_E + R_D \times W_D \times (1 - T)
$$

onde:

- $WACC$ representa o custo médio ponderado do capital.
- $R_E$ representa a taxa de custo ou de remuneração do capital próprio.
- $W_E = \frac{E}{E + D}$ representa o rácio entre o valor de mercado do capital próprio (_E_) e o valor de mercado da empresa (_V=E+D_).
- $R_D$ representa a taxa de custo da dívida ou de remuneração dos capitais alheios.
- $W_D = \frac{D}{E + D}$ representa o rácio entre o valor de mercado da dívida (_D_) e o valor de mercado da empresa (_V=E+D_).
- $T$ representa a taxa de imposto sobre lucros.

Da [equação acima](#wacc-eq), ressalta a necessidade de estimação das taxas de retorno exigidas por acionistas ($R_E$) e credores financeiros ($R_D$), bem como a estrutura de capital (combinação entre dívida e capital próprio) e a taxa de imposto sobre lucros. No que respeita às taxas de retorno exigidas, os modelos de avaliação de risco utilizados para o cálculo de cada uma das taxas partem de premissas distintas. Para os credores financeiros importa sobretudo o risco de crédito (i.e., o risco de incumprimento ou _default_), enquanto para os acionistas interessa o risco de mercado (i.e., a incapacidade da empresa gerar _cash flows_ suficientes para pagar dividendos/remunerar os acionistas). A análise de cada uma destas componentes será realizada posteriormente.

Cabe ainda salientar que a decisão de investimento em qualquer projeto ou negócio só ocorrerá se o seu valor de mercado – tal como apresentado na de [valor de mercado equação](../enquadramento/decisoes_de_financiamento.md#val-eq)– for maior ou, no limite, igual a zero, o que requer que a taxa de retorno efetiva seja igual ou superior ao _WACC_. Daqui resulta que o _WACC_ não é mais do que a taxa de remuneração mínima esperada por um investidor para afetar recursos a qualquer projeto ou negócio, tendo sempre subjacente um custo de oportunidade do capital; i.e., o retorno esperado num investimento com características semelhantes. Dito de outra forma, para que o _WACC_ traduza apropriada e adequadamente o custo médio ponderado do capital, deverá corresponder à melhor taxa de retorno obtida em aplicações de risco equivalente e que um qualquer investidor utilizaria para atualizar os _free cash flows_ futuros esperados para o melhor investimento alternativo; i.e., numa empresa/projeto (comparável) do mesmo setor de atividade.

Finalmente, importa ainda referir que a estrutura de capitais - os parâmetros $W_E$ e $W_D$ -, é sempre definida a valores de mercado e nunca a valores contabilísticos; i.e., os parâmetros $E$ e $D$ representam o valor de mercado do capital próprio e do capital alheio (dívida), respetivamente, e não o seu valor contabilístico. Mais acresce que é pressuposto da aplicabilidade prática do modelo de avaliação $FCF/WACC$ que a estrutura de capital é aquela que maximizará o valor de mercado da empresa ou do projeto de investimento que se pretende avaliar.




