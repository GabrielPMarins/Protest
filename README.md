# Painel de Performance de Mídia Paga — Protest

Relatório executivo das campanhas de mídia paga da Protest, feito para leitura rápida do CEO e da
equipe de Marketing. Arquivo único em HTML, funciona offline, sem instalação e sem servidor.

| | |
|---|---|
| **Arquivo** | `KPI_Protest.html` |
| **Versão online** | https://claude.ai/code/artifact/f22fa973-b15c-40ad-8f31-479e16b3b179 |
| **Período coberto** | 01/01/2026 a 21/08/2026 |
| **Dados atualizados em** | 21/08/2026 |
| **Feito por** | UM_digital |

---

## 1. Como abrir

**No computador.** Dê dois cliques no `KPI_Protest.html`. Ele abre no navegador padrão. Pode ser
guardado em qualquer pasta, enviado por e-mail ou colocado numa pasta compartilhada — é um arquivo
só, sem dependências externas.

**Pelo link.** A versão online abre em qualquer dispositivo e está sempre na última versão publicada.
É privada até você compartilhá-la pelo menu da própria página.

**No celular.** O layout se adapta. Os filtros ficam recolhidos numa barra de uma linha no topo;
toque em **Filtros** para abrir e em **Ver o painel** para fechar.

> A exportação para XLSX funciona nas duas versões. Se o navegador bloquear o download na versão
> online, use o arquivo local.

---

## 2. A ideia central: o ciclo de venda é de 192 dias

Este é o ponto que muda tudo na leitura. Entre a primeira conversão de um lead e a assinatura do
contrato passam, em média, **192 dias — cerca de 6,3 meses**. Ou seja: **o dinheiro investido hoje
não vira contrato hoje**.

Avaliar a verba deste mês pela receita deste mês leva à conclusão errada de que o marketing não está
retornando. Por isso o painel divide o período em duas lentes:

| Lente | O que é | O que se lê nela |
|---|---|---|
| **Safra madura** | Leads que entraram há mais de 192 dias | CAC, win rate e ROI **definitivos** — já tiveram a chance completa de fechar |
| **Safra em construção** | Leads dentro da janela do ciclo | **Pipeline gerado** e **receita projetada** — nunca CAC nem ROI |

A barra colorida no topo da aba **Resumo** mostra essa divisão para o período filtrado, com as datas
de corte e a data em que a safra atual termina de maturar.

---

## 3. As seis abas

| Aba | Para quê serve |
|---|---|
| **Resumo** | A leitura de cinco minutos do CEO. Régua do ciclo, oito indicadores executivos, as duas lentes lado a lado, safras por mês, leitura automática do período e metas |
| **Visão executiva** | O detalhamento em cinco blocos: Financeiro, Saúde do funil, Passagem de bastão, Previsibilidade de fechamento e Campanhas e canais |
| **Mídia paga** | Investimento, cliques, CTR, CPC, conversões e a tabela dinâmica de campanhas |
| **Leads e funil** | Conciliação das duas bases, origem, perfil, canal, engajamento, região e a tabela dinâmica de leads |
| **Landing pages** | Visitas, conversões e taxa por página |
| **Resultado comercial** | Reuniões, propostas, motivos de perda e os principais leads do período |

O botão **Atualizar dados**, no topo, abre a área de upload e de premissas. Ela não tem aba própria.

Cada card tem um **?** com a explicação do indicador, a fórmula e como interpretá-lo. Quando algo
não estiver claro, a resposta está ali.

---

## 4. Os filtros

Ficam na barra abaixo do menu e valem para o painel inteiro.

- **Período** — atalhos (todo o período, ano corrente, últimos 3 ou 6 meses, mês atual, mês anterior)
  ou datas livres em *De* e *Até*.
- **Canal** — Google Ads e Meta Ads. Selecionar um canal também reduz a lista de campanhas.
- **Campanha** e **Origem do lead** — **seleção múltipla**. Abra, marque quantas quiser, use
  *Selecionar todas* ou *Limpar*. A origem mostra a contagem de leads ao lado de cada item.
- **Comparar com** — período anterior de mesma duração, mesmo período do ano anterior, intervalo
  personalizado ou **Não comparar**. Editar as datas de comparação muda automaticamente para
  personalizado.
- **Limpar filtros** devolve tudo ao estado inicial.

A linha abaixo dos filtros sempre resume o que está aplicado.

**Granularidade:** os dados de mídia são mensais. Quando o período selecionado corta um mês pela
metade, o valor daquele mês é proporcionalizado pelos dias. Os dados de leads são diários.

---

## 5. Como atualizar

Há dois caminhos. O primeiro é rápido e feito por você; o segundo é completo e refaz o painel
a partir das fontes conectadas.

### Caminho A — subir arquivos no próprio painel

Clique em **Atualizar dados** no topo e arraste os arquivos. Aceita `.xlsx`, `.csv`, `.md`, `.pdf`
e `.png`. Planilhas e CSV substituem os dados; PDF, PNG e Markdown ficam apenas registrados como
material de apoio. Nada sai do seu navegador.

#### O que subir em cada atualização

1. **Base de leads da automação** — exportação da segmentação `[UM_digital] Estudo-leads-gerados-campanhas`,
   com as colunas `Email`, `Nome`, `Telefone`, `Celular`, `Cargo`, `Lead Scoring - Perfil`,
   `Lead Scoring - Interesse`, `Tags`, `Data da primeira conversão` e `Origem da primeira conversão`.
   **É daqui que saem a contagem de leads e a nota de perfil.**

2. **Controle de leads** — planilha com as colunas `DATA`, `Nome do Lead`, `Origem / Campanha`,
   `Proposta Gerada`, `Valor Anual`, `Status do Lead`. Traz o lado comercial: reuniões, propostas
   e contratos.

3. **Campanhas de mídia** — planilha com `mes`, `canal`, `campanha`, `invest`, `cliques`,
   `impressoes`, `conversoes`.

4. **Landing pages** — planilha com `nome`, `visitas`, `conversoes`.

5. **Suba as duas bases na mesma atualização.** O painel cruza uma com a outra por e-mail, telefone
   e nome, e conta cada pessoa **uma única vez** — quem aparece nas duas fontes ou converteu em
   vários materiais não é somado duas vezes.

6. **Confira a lista de arquivos:** o painel indica o que cada um substituiu e quantos duplicados
   foram eliminados.

### Caminho B — atualização completa

Peça **“Atualize o dashboard”** e anexe os arquivos do período. A atualização completa refaz a
coleta nas fontes conectadas — mídia paga, landing pages e documentos de referência — recalcula
tudo e republica o painel no mesmo link, mantendo o histórico de versões.

### Detalhes que evitam retrabalho

- A exportação da segmentação sai em **UTF-16 separada por tabulação**. Não precisa converter: o
  painel reconhece o formato original.
- Datas em `DD/MM/AAAA` ou `AAAA-MM-DD` são aceitas nas duas bases.
- Telefones em qualquer formatação são reconhecidos como o mesmo número: `(21) 98039-9290`,
  `+55 21 980399290` e `980399290` são a mesma pessoa.
- Registros anteriores a **01/01/2026** são descartados automaticamente.
- Para trocar só uma das bases, suba só aquele arquivo: o painel mantém a outra e refaz o cruzamento.

---

## 6. Como cada pessoa é contada uma vez só

As duas bases se sobrepõem: o mesmo lead costuma aparecer na automação e no controle comercial, e
uma mesma pessoa converte em vários materiais ao longo do tempo. O painel resolve isso antes de
qualquer cálculo.

**As chaves de identidade, da mais forte para a mais fraca:**

1. **E-mail** normalizado.
2. **Telefone** normalizado — sem `+55`, sem DDD, comparando os últimos 9 dígitos.
3. **Nome completo**, e só quando é distintivo (duas palavras ou mais, onze caracteres ou mais)
   **e** os dois registros não têm e-mails ou telefones diferentes entre si. Essa última condição é
   o que impede dois xarás de virarem a mesma pessoa.

Ao unir dois registros, o painel mantém a **data da primeira conversão** e completa os campos vazios
de uma fonte com os da outra. Cada lead fica marcado com sua origem: *Ambas as bases*,
*Controle comercial* ou *Base de automação*.

**Situação atual:** 570 registros da automação + 863 do controle comercial = 1.433 linhas, que viram
**889 pessoas distintas** depois de eliminar 544 repetições. Dessas, 307 aparecem nas duas bases,
331 só no comercial e 251 só na automação.

A aba **Leads e funil** tem um bloco chamado *Conciliação das duas bases* que mostra essa cadeia
passo a passo, sempre recalculada para o período filtrado.

---

## 7. Regras de escopo

Definições em vigor. Todas valem para o painel inteiro, em qualquer filtro.

- **Período:** somente 2026 em diante. Qualquer registro anterior a 01/01/2026 fica fora.
- **Campanhas:** apenas as geridas pela agência — as que começam com `UM` — mais a campanha
  `[Tráfego] Post Black Friday - ReactPro`. Hoje são 11 campanhas ativas no recorte.
- **MQL:** lead com nota de perfil **A ou B** na régua de Lead Scoring. A nota vem da plataforma de
  automação; para os poucos leads que existem só no controle comercial, é recalculada pela mesma
  régua (cargo 50%, número de unidades 30%, cidade 20%).
- **Landing pages de agradecimento** não entram na análise.
- **Vendas projetadas = 10% dos MQL**, conforme a metodologia da agência. Não depende de quantas
  propostas já foram emitidas.
- **Canal de aquisição:** vem da origem da primeira conversão registrada na automação. É atribuição
  real, não rateio. Leads sem canal registrado aparecem como *Não identificado*.

---

## 8. Premissas editáveis

Em **Atualizar dados → Premissas de cálculo**. Alterar qualquer campo recalcula o painel na hora,
sem recarregar a página.

| Premissa | Valor atual | O que afeta |
|---|---|---|
| Ticket médio mensal | R$ 2.000 | Reserva do LTV quando não há contratos fechados |
| Margem de contribuição | 16% | LTV e payback |
| Duração do contrato | 12 meses | LTV |
| Conversão esperada de MQL em venda | 10% | Vendas projetadas, CAC projetado, faturamento projetado |
| Ciclo médio de vendas | 192 dias | Corte entre as safras e tempo até o retorno |
| Meta de leads / mês | 50 | Barra de metas |
| Meta de MQL / mês | 30 | Barra de metas |
| **Custo da agência / mês** | **não preenchido** | CAC geral, CPP, CPL, CPLQ, ROI |
| **Custo das ferramentas / mês** | **não preenchido** | CAC geral, CPP, CPL, CPLQ, ROI |

**Sobre os custos fixos.** Agência e ferramentas começam zeradas e **ficam fora de todas as contas**
até serem preenchidas. Enquanto isso, o painel mostra *Investimento em mídia* no lugar de
*Investimento total*, esconde o card de *CAC geral* e avisa, na seção Financeiro, que os indicadores
de custo consideram apenas a mídia. Ao informar os valores, os cards aparecem e tudo se recalcula.

O botão **Restaurar padrão** devolve todas as premissas aos valores originais.

> **Importante:** o LTV usa o ticket **realmente praticado**, não a premissa. A ordem de preferência
> é: ticket médio dos contratos fechados → ticket médio das propostas → premissa. O card sempre diz
> qual base foi usada.

---

## 9. Glossário dos indicadores

### Financeiro

| Indicador | Como é calculado |
|---|---|
| **Investimento em mídia** | Soma do valor gasto em Google Ads e Meta Ads |
| **Investimento total** | Mídia + agência + ferramentas (só aparece com os custos fixos preenchidos) |
| **Receita influenciada** | Valor anual dos contratos fechados com origem nas campanhas |
| **Receita influenciada projetada** | Valor anual das propostas em aberto |
| **ROAS financeiro** | Receita influenciada ÷ investimento |
| **ROI financeiro** | (Receita influenciada − investimento) ÷ investimento |
| **CAC de marketing** | Investimento em mídia ÷ contratos fechados |
| **CAC geral** | Investimento total ÷ contratos fechados |
| **CAC retroativo** | Investimento da safra madura ÷ contratos gerados por ela |
| **CAC projetado** | Investimento ÷ (MQL × 10%) |
| **LTV por contrato** | Ticket praticado × duração × margem |
| **LTV : CAC projetado** | LTV ÷ CAC projetado. Referência de mercado: 3x ou mais |
| **Payback projetado** | CAC projetado ÷ margem mensal do contrato |

### Saúde do funil

| Indicador | Como é calculado |
|---|---|
| **Pipeline gerado** | Soma do valor anual de todas as propostas emitidas |
| **Custo por R$ 1 de pipeline (CPP)** | Investimento ÷ pipeline. O card mostra também a leitura inversa |
| **Taxa de aceite (MQL → SQL)** | Oportunidades abertas ÷ MQL |
| **Win rate (SQL → cliente)** | Ganhos ÷ (ganhos + perdidos) |
| **CPL** | Investimento ÷ leads |
| **CPLQ** | Investimento ÷ MQL |
| **Ciclo de vendas** | Premissa de 192 dias — ainda não medido, ver seção 10 |

### Funil e campanhas

| Indicador | Como é calculado |
|---|---|
| **Leads** | Pessoas distintas geradas pelas campanhas, após a conciliação |
| **MQL** | Leads com nota de perfil A ou B |
| **Oportunidades** | Leads com *Avançou para Contato = Sim* no controle comercial |
| **Conversão lead → MQL** | MQL ÷ leads |
| **Conversão MQL → venda** | Contratos ÷ MQL |
| **Leads no perfil ideal (% ICP)** | Leads de condomínios com 50 unidades ou mais |

---

## 10. O que o painel ainda não mede

Três indicadores dependem de colunas de data que não existem nas bases atuais. O painel prefere
declarar a lacuna a estimar um número que pareceria preciso sem ser. O card *O que ainda não é
medido*, na Visão executiva, mostra isso de forma explícita.

| Indicador | Coluna que falta |
|---|---|
| Tempo de reação comercial | `Data do primeiro contato` |
| Velocidade das etapas do funil | `Data de mudança de etapa` |
| Ciclo de vendas medido | `Data de fechamento` |

Incluindo essas três colunas no controle comercial, os indicadores passam a ser calculados
automaticamente e **o ciclo de 192 dias deixa de ser premissa e vira medição**.

Outra limitação conhecida: as métricas de **visita por landing page** são liberadas pela plataforma
de automação apenas para uma janela recente de 45 dias. O total de conversões por página, esse sim,
cobre todo o período. O painel sinaliza as duas janelas.

---

## 11. Exportar e compartilhar

- **Exportar XLSX** — gera uma planilha com quatro abas: Resumo (todos os indicadores do período,
  incluindo a quebra por safra), Campanhas, Leads e Landing pages. Respeita os filtros aplicados.
- **Exportar PDF** — abre a caixa de impressão do navegador com todas as abas expandidas e um layout
  próprio para papel. Escolha *Salvar como PDF*.
- **Tabelas** — clique nos títulos para ordenar. A última linha traz sempre os totais do período
  filtrado, com soma para valores e média ponderada para taxas como CTR, CPC e custo por conversão.

---

## 12. Situação atual — 01/01/2026 a 21/08/2026

Retrato do momento em que este documento foi escrito, sem os custos de agência e ferramentas.

**Geração de demanda**

| | |
|---|---|
| Investimento em mídia | R$ 36.434 |
| Leads (pessoas distintas) | 889 |
| MQL (perfil A ou B) | 432 — 48,6% da base |
| Oportunidades abertas | 98 |
| Propostas | 44 |
| CPL / CPLQ | R$ 40,98 / R$ 84,34 |

**Financeiro**

| | |
|---|---|
| Pipeline gerado | R$ 637.713 |
| Custo por R$ 1 de pipeline | R$ 0,06 — cada real investido gera R$ 17,50 de pipeline |
| Receita influenciada | R$ 18.577 (2 contratos) |
| CAC de marketing | R$ 18.217 |
| CAC projetado | R$ 843 |
| LTV : CAC projetado | 1,6x |
| Payback projetado | 7,4 meses |
| ROI financeiro | −49% |

**As duas safras**

| | Safra madura (01/01 a 10/02) | Safra em construção (11/02 a 21/08) |
|---|---|---|
| Leads | 87 | 802 |
| MQL | 50 | 382 |
| Propostas | 11 | 33 |
| Contratos | 1 | — |
| Investimento | R$ 3.136 | R$ 33.297 |
| Resultado | ROI +264% | Pipeline de R$ 327.455, matura até 01/03/2027 |

**O que esses números dizem**

- A geração de demanda funciona: 889 leads e 432 qualificados a um custo baixo, com a meta mensal de
  MQL sendo superada.
- O gargalo está entre a qualificação e a oferta: **apenas 9,8% dos MQL viraram proposta**.
- A taxa de aceite de 22,7% indica que boa parte dos leads qualificados pelo marketing ainda não é
  trabalhada pelo comercial.
- A safra madura, a única com leitura definitiva, fechou **positiva** — mas com 87 leads e 1
  contrato, é amostra pequena demais para conclusão firme.
- O ticket praticado nas propostas (R$ 1.694/mês) é bem menor que a premissa de unit economics
  (R$ 2.000/mês), e o dos contratos fechados menor ainda (R$ 715/mês). É esse número, não o da
  premissa, que sustenta o CAC.

---

## 13. Perguntas frequentes

**Os dados mudam sozinhos?**
Não. O painel é um retrato do momento em que foi gerado. Ele só muda quando você sobe arquivos novos
ou pede uma atualização completa.

**Posso mandar o arquivo para alguém?**
Sim. É um arquivo único e autossuficiente. Lembre-se de que ele contém a base de leads com nome,
e-mail e telefone — trate como informação interna.

**Mudei uma premissa sem querer.**
Clique em *Restaurar padrão*, na área de premissas. Nada é salvo entre sessões: recarregar a página
também devolve tudo ao estado original.

**Subi o arquivo errado.**
Recarregue a página. Os uploads ficam só na memória do navegador e não alteram o arquivo original.

**Por que o ROI está negativo se o pipeline é alto?**
Porque o ROI compara receita **já fechada** com investimento, e o ciclo de 192 dias faz a maior parte
das safras ainda não ter tido tempo de fechar. É exatamente para evitar essa leitura equivocada que
existe a divisão entre as duas safras.

---

*Dashboard criado pela UM_digital para a Protest Imóveis & Condomínios.*
