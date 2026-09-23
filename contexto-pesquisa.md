# Contexto da pesquisa

**Autora:** Renata Oliveira Campos — Mestrado Profissional em Economia (IDP)
**Título provisório:** Recomendação de investimentos em renda fixa com IA generativa: adequação ao perfil e fidedignidade da justificativa
**Orientador:** Prof. Dr. Alex Lopes Pereira

> Solução-modelo do exercício ia-6.2 do curso *Agentes de IA*. A pesquisa é a
> mesma persona do exercício ia-3.2 (revisão bibliográfica com `/grill-me`).

## O problema

O investidor pessoa física brasileiro, não qualificado, que escolhe entre
Tesouro Direto, CDB, LCI e LCA no app do próprio banco não tem assessoria
humana: o tíquete não paga o assessor. Recomendadores automáticos resolvem a
escolha do produto, que em renda fixa é quase trivial. O que a IA generativa
acrescenta é a **justificativa em linguagem natural**, e é também ali que ela
introduz o risco: um texto convincente que afirma algo que a ficha do produto
não diz.

## O que já está decidido (herdado da revisão do ia-3.2)

- **Recorte de produtos:** Tesouro Direto, CDB, LCI e LCA — emissor soberano ou
  bancário. Fora: debêntures, CRI/CRA, fundos de crédito privado.
- **Dois construtos, medidos separadamente:**
  1. *adequação ao perfil* — o produto recomendado é compatível com objetivo,
     prazo e tolerância a risco declarados (é a lógica de suitability da CVM);
  2. *fidedignidade da justificativa* — o texto não afirma nada que contrarie a
     ficha do produto, nem afirma o que a ficha não permite verificar.
- **A lacuna, reformulada:** medir fidedignidade em *recomendação* ao
  investidor final, e não em *análise* financeira, onde a literatura de
  alucinação em finanças se concentra. O português é contexto do artefato, não
  a contribuição.
- **Artefato do mestrado profissional:** um protótipo de recomendador com LLM,
  avaliado com perfis sintéticos.

## O que ainda está em aberto

- Se já existe benchmark ou métrica de fidedignidade aplicável a justificativa
  de recomendação financeira — ou se a dissertação vai ter de propor uma.
- Qual é o método de avaliação: anotação humana, LLM-como-juiz, verificação por
  regra contra a ficha, ou uma combinação — e com que validação.
- De onde vêm as fichas de produto que servem de verdade-base, e se elas são
  públicas e estáveis o suficiente para um estudo reprodutível.

## Pergunta de aprofundamento (foco em impacto científico)

**Que contribuição verificável — uma métrica de fidedignidade, um conjunto de
dados anotado ou um achado sobre o trade-off entre adequação e fidedignidade —
tornaria esta dissertação citável fora do nicho da renda fixa brasileira, por
quem estuda explicações geradas por LLM em decisões de alto risco?**
