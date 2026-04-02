---
title: "Glossário de Epidemiologia: 25 Termos Essenciais para Pesquisadores em Formação"
description: "Conheça os 25 termos mais importantes da epidemiologia com definições claras, exemplos práticos e fontes científicas. Do básico ao avançado, em um glossário feito para quem pesquisa de verdade."
date: 2026-04-02
author: "Gabriel Olegário e Lucas Santos"
tags: ["Epidemiologia", "Metodologia", "Glossário", "Fundamentos"]
draft: false
---

Se você já abriu um artigo científico, sentiu que estava lendo em outra língua e fechou a aba — este post é para você.

A epidemiologia tem um vocabulário próprio. E aprender esse vocabulário não é frescura acadêmica: é o que separa quem lê um artigo e entende de quem lê um artigo e chuta o que quer dizer. Quando você sabe a diferença entre incidência e prevalência, entre risco relativo e odds ratio, entre viés de seleção e confundimento, você passa a enxergar a estrutura por trás de qualquer estudo — e isso muda tudo.

Esse glossário reúne os 25 termos mais usados na pesquisa epidemiológica, organizados por tema, com definições claras, exemplos práticos e referências reais. Não é uma lista de palavras bonitas para colar no TCC: é uma referência viva que você vai consultar toda vez que bater em uma definição que não está clara.

Marque nos seus favoritos. Você vai voltar aqui.

---

## 1. Os Fundamentos: Epidemiologia e suas Medidas de Ocorrência

### Epidemiologia

A epidemiologia é a ciência que estuda a distribuição, os determinantes e o controle de doenças e agravos à saúde em populações humanas (IRGENS, 2017). A palavra vem do grego: *epi* (sobre), *demos* (povo) e *logos* (estudo). Ou seja, literalmente, o estudo do que acontece sobre o povo.

O que torna a epidemiologia diferente da clínica médica é o foco: enquanto o médico olha para o paciente individual, o epidemiologista olha para populações inteiras. A pergunta não é "o que este paciente tem?" mas "por que essa doença atinge mais esse grupo do que aquele?"

Historicamente, a epidemiologia se concentrou em doenças infecciosas, mas evoluiu para abranger doenças crônicas não transmissíveis, saúde mental, lesões, fatores ambientais e qualquer evento que afete a saúde coletiva (NCBI, 2022).

---

### Incidência

A incidência mede o surgimento de *casos novos* de uma doença em uma população que estava em risco durante um período específico (CDC, 2012). É a medida do *risco* de adoecer.

Existem dois tipos principais:

- **Incidência cumulativa (risco):** proporção de pessoas que desenvolvem a doença em um período fixo.
- **Taxa de incidência (densidade de incidência):** número de casos novos por unidade de tempo-pessoa de observação — útil em estudos longos, onde nem todos os participantes são acompanhados pelo mesmo tempo.

**Fórmula básica:**
`Taxa de incidência = (Nº de casos novos) ÷ (População em risco × tempo de observação)`

**Exemplo prático:** Se 1,5 milhão de pessoas foram diagnosticadas com HIV no mundo em 2021, em uma população global de 7,9 bilhões, a incidência global de HIV foi de 19 casos por 100.000 habitantes naquele ano (NIH, 2022).

---

### Prevalência

A prevalência mede a *proporção* de pessoas que têm uma doença em um determinado momento, incluindo casos antigos e novos (NCBI, 2023). É como uma fotografia: captura quem está doente agora, independentemente de quando adoeceu.

Dois tipos:
- **Prevalência pontual:** casos existentes em um momento específico.
- **Prevalência de período:** casos existentes em um intervalo de tempo.

**A relação entre incidência e prevalência:** prevalência = incidência × duração da doença. Por isso, doenças crônicas (como diabetes ou artrite) tendem a ter alta prevalência mesmo quando a incidência é moderada — as pessoas ficam doentes por muito tempo (CDC, 2012).

**Exemplo:** 38,4 milhões de pessoas viviam com HIV no final de 2021, resultando em uma prevalência global de 486 casos por 100.000 habitantes — muito maior que a incidência, porque pessoas infectadas vivem por décadas com tratamento (NIH, 2022).

> 💡 **Diferença-chave:** Incidência = casos novos (risco). Prevalência = todos os casos existentes (carga). Você usa incidência para entender o risco de adoecer; usa prevalência para dimensionar o impacto da doença na população (NCBI, 2023).

---

### Morbidade

Morbidade é o estado de estar doente, incapacitado ou em má saúde por qualquer causa (NCBI, 2022). O termo funciona como um guarda-chuva: abrange tanto a incidência (quantos adoecem) quanto a prevalência (quantos estão doentes). Na vigilância epidemiológica, as taxas de morbidade são fundamentais para entender como uma doença progride em uma população.

---

### Mortalidade

A mortalidade se refere à ocorrência de mortes em uma população, expressa como taxa: número de óbitos dividido pela população exposta ao risco em um determinado período (NCBI, 2022). Diferente de morbidade, que foca na doença, a mortalidade foca no desfecho mais grave — a morte.

**Taxa de letalidade (case-fatality rate):** proporção de pessoas com uma doença que morrem em decorrência dela. Diferente da taxa de mortalidade, que usa a população total como denominador.

---

## 2. Medidas de Associação e Risco

Estas são as métricas que permitem ao pesquisador responder: "Exposição X aumenta o risco do desfecho Y? Em quanto?"

### Fator de Risco e Desfecho

Antes de calcular qualquer medida, é preciso definir dois conceitos centrais:

- **Desfecho:** o evento de interesse no estudo — pode ser uma doença, um sintoma, óbito ou qualquer evento no processo saúde-doença.
- **Fator de risco:** variável que se supõe estar associada ao desfecho. Pode ser um comportamento (fumar), uma exposição ambiental (poluição) ou uma característica individual (idade, sexo).

A relação entre fator de risco e desfecho é o coração da epidemiologia analítica (CELESTE; FRAGA, 2011).

---

### Risco Relativo (RR)

O risco relativo é a razão entre a incidência do desfecho nos expostos ao fator de risco e a incidência nos não expostos (CELESTE; FRAGA, 2011). Responde à pergunta: "Expostos têm quantas vezes mais risco de desenvolver o desfecho?"

**Fórmula:** `RR = Incidência nos expostos ÷ Incidência nos não expostos`

**Interpretação:**
- RR = 1: sem associação
- RR > 1: fator de risco (exposição aumenta o risco)
- RR < 1: fator protetor (exposição reduz o risco)

O RR é a medida de escolha em estudos de **coorte**, onde é possível calcular incidências nos dois grupos diretamente (CELESTE; FRAGA, 2011).

**Exemplo:** Se fumantes têm incidência de câncer de pulmão de 200/100.000 e não fumantes têm 20/100.000, o RR é 10 — fumantes têm 10 vezes mais risco.

---

### Odds Ratio (OR)

O odds ratio é a razão entre as "chances" (odds) de desenvolver o desfecho no grupo exposto versus o não exposto (AGUIAR et al., 2013). É a medida de associação preferida em **estudos caso-controle**, onde não é possível calcular incidência diretamente.

**Odds** não é o mesmo que probabilidade: é a razão entre a probabilidade de o evento ocorrer e a probabilidade de ele não ocorrer.

A interpretação do OR é análoga ao RR, mas com uma ressalva importante: o OR *superestima* o RR quando a doença não é rara (prevalência > 10%). Para doenças raras, OR ≈ RR (AGUIAR et al., 2013).

> 💡 **Resumo prático:** Use RR em coortes. Use OR em caso-controle. Se a doença é rara, os dois chegam a valores próximos. Se a doença é comum, o OR vai exagerar a magnitude da associação.

---

### Risco Atribuível (RA)

O risco atribuível mede a diferença absoluta de risco entre expostos e não expostos. Enquanto o RR fala em termos relativos ("expostos têm X vezes mais risco"), o RA fala em termos absolutos ("expostos têm Y casos a mais por 100.000"). É especialmente útil para políticas de saúde pública, porque mostra o impacto real de eliminar uma exposição (CELESTE; FRAGA, 2011).

---

## 3. Tipos de Estudo Epidemiológico

Entender os delineamentos é fundamental: cada tipo de estudo tem perguntas que consegue responder e limitações que precisam ser conhecidas.

---

### Estudo Transversal

Observa a população em um único ponto no tempo, medindo simultaneamente a exposição e o desfecho. Resultado típico: **prevalência**. É rápido e barato, mas não permite estabelecer relação temporal — não dá para saber se a exposição veio antes do desfecho (NCBI, 2022).

**Quando usar:** estudos descritivos, levantamentos de prevalência, pesquisas populacionais.

---

### Estudo de Coorte

Acompanha um grupo de pessoas saudáveis ao longo do tempo, avaliando quem desenvolve o desfecho de interesse. Pode ser **prospectivo** (acompanhar para frente) ou **retrospectivo** (usar dados já existentes). A medida de resultado principal é a **incidência** e o **risco relativo** (NCBI, 2022).

O Estudo de Framingham, que acompanhou habitantes de Framingham (EUA) desde os anos 1950 para identificar fatores de risco para doenças cardíacas, é o exemplo clássico de coorte prospectiva (NCBI, 2022).

**Quando usar:** quando se quer estabelecer temporalidade entre exposição e desfecho, especialmente em doenças comuns.

---

### Estudo Caso-Controle

Parte dos casos (pessoas que já têm a doença) e dos controles (pessoas sem a doença), e investiga retrospectivamente a exposição anterior de cada grupo. É o delineamento ideal para **doenças raras** e para estudar múltiplos fatores de risco. O resultado típico é o **odds ratio** (NCBI, 2022).

---

### Ensaio Clínico Randomizado (ECR)

O padrão-ouro da pesquisa intervencionista. Os participantes são alocados aleatoriamente (randomizados) entre o grupo que recebe a intervenção e o grupo controle (placebo ou tratamento padrão). A randomização é o que torna o ECR tão poderoso: ela equilibra fatores conhecidos *e desconhecidos* entre os grupos, controlando vieses de seleção e confundimento ao mesmo tempo (NCBI, 2022).

---

## 4. Viés e Confundimento

Esses dois conceitos são a diferença entre um estudo confiável e um estudo que leva a conclusões erradas.

### Viés

Viés é qualquer erro sistemático no desenho, condução ou análise de um estudo que produz resultados distorcidos (CDC, 2012). Diferente do erro aleatório (que flutua para cima e para baixo), o viés sistematicamente empurra os resultados em uma direção.

Tipos principais:
- **Viés de seleção:** ocorre quando a forma de selecionar os participantes difere entre os grupos de forma não aleatória.
- **Viés de informação:** ocorre quando as informações coletadas diferem sistematicamente entre os grupos (ex: pacientes com câncer lembram melhor de exposições passadas do que pessoas saudáveis — "viés de memória").

---

### Confundimento

Confundimento acontece quando uma terceira variável está associada tanto ao fator de risco quanto ao desfecho, distorcendo a associação observada entre eles (PORTAL ANMSP, 2024).

**Exemplo clássico:** estudos observaram que casados tinham mais câncer que solteiros. Conclusão errada? O casamento causa câncer? Não: o grupo dos casados era, em média, mais velho — e a idade é o verdadeiro fator de risco. A idade é a variável de confundimento neste caso (PORTAL ANMSP, 2024).

Para controlar confundimento, epidemiologistas usam estratégias como análise estratificada, regressão múltipla ou, nos ensaios clínicos, a própria randomização.

---

## 5. Métricas de Carga de Doença

### DALY (Disability-Adjusted Life Year)

DALY, ou anos de vida perdidos ajustados por incapacidade, é a principal métrica usada para medir a carga de doença em populações. Um DALY equivale a um ano de vida saudável perdido (OMS, 2024).

O DALY é calculado pela soma de duas componentes (IHME, 2013):

- **YLL (Years of Life Lost):** anos de vida perdidos por morte prematura.
- **YLD (Years Lived with Disability):** anos vividos com alguma perda de saúde, ponderados pela gravidade da incapacidade.

`DALY = YLL + YLD`

Essa métrica é poderosa porque captura tanto a mortalidade quanto a morbidade. Por isso, ela revela problemas de saúde que as estatísticas tradicionais de mortalidade escondem. Por exemplo, a dor lombar é uma das maiores causas de DALYs globalmente — mas raramente aparece nas listas de "principais causas de morte" (IHME, 2013).

O DALY é a métrica central do **Global Burden of Disease (GBD)**, o maior estudo epidemiológico do mundo, coordenado pelo Institute for Health Metrics and Evaluation (IHME) da Universidade de Washington e publicado regularmente no *The Lancet* (GBD BRASIL, 2024).

> 💡 **Por que isso importa para você?** Se o seu estudo envolve comparação de impacto de doenças, planejamento de políticas de saúde ou alocação de recursos, o DALY é a linguagem que pesquisadores e formuladores de políticas usam. Dominar esse conceito é o que separa quem produz ciência relevante de quem produz ciência ignorada.

---

### QALY (Quality-Adjusted Life Year)

O QALY combina quantidade e qualidade de vida em uma única métrica, sendo muito usado em estudos de custo-efetividade de intervenções em saúde. Um QALY equivale a um ano de vida em perfeita saúde (ROCHA, 2017). A diferença do DALY: o QALY é baseado em preferências dos pacientes, enquanto o DALY usa pesos de incapacidade padronizados.

---

## 6. Epidemiologia Descritiva: Epidemia, Endemia e Pandemia

### Endemia

Endemia é a presença constante de uma doença em uma área geográfica específica, com frequência relativamente estável e esperada para aquela população (CDC, 2012). A malária é endêmica em grande parte da África Subsaariana; a dengue é endêmica em várias regiões do Brasil.

---

### Epidemia

Epidemia é a ocorrência de casos de doença em número maior do que o esperado para aquela população, local e período — um aumento súbito e acima do basal (CDC, 2012). O limiar para chamar algo de epidemia depende do que é "esperado" para aquela doença naquele contexto.

---

### Pandemia

Pandemia é uma epidemia que se espalha por múltiplos países ou continentes, afetando grande número de pessoas (CDC, 2012). A COVID-19 declarada em março de 2020 é o exemplo mais recente e impactante.

---

## Tabela-Resumo: Os 25 Termos em Um Só Lugar

| Termo | Definição Curta | Onde aparece |
|---|---|---|
| Epidemiologia | Estudo da distribuição e determinantes de doenças em populações | Todos os estudos |
| Incidência | Casos novos em uma população em risco por período | Coorte, ECR |
| Prevalência | Total de casos existentes em um momento ou período | Transversal |
| Morbidade | Estado de doença ou incapacidade na população | Vigilância |
| Mortalidade | Ocorrência de mortes na população | Vigilância |
| Taxa de letalidade | Proporção de doentes que morrem | Doenças agudas |
| Fator de risco | Variável associada ao aumento do risco do desfecho | Todos |
| Desfecho | Evento de interesse no estudo | Todos |
| Risco Relativo (RR) | Razão de incidências: expostos / não expostos | Coorte |
| Odds Ratio (OR) | Razão de chances: expostos / não expostos | Caso-controle |
| Risco Atribuível (RA) | Diferença absoluta de risco entre grupos | Políticas públicas |
| Estudo transversal | Medida simultânea de exposição e desfecho | Descritivo |
| Estudo de coorte | Acompanhamento prospectivo de grupos | Analítico |
| Estudo caso-controle | Comparação retrospectiva casos vs. controles | Doenças raras |
| Ensaio Clínico Randomizado | Intervenção com alocação aleatória | Intervencionista |
| Viés | Erro sistemático nos resultados | Todos |
| Viés de seleção | Distorção pela forma de selecionar participantes | Todos |
| Viés de informação | Distorção na coleta de dados entre grupos | Todos |
| Confundimento | Terceira variável distorce a associação observada | Todos |
| DALY | Anos de vida saudável perdidos (YLL + YLD) | GBD, políticas |
| YLL | Anos perdidos por morte prematura | GBD |
| YLD | Anos vividos com incapacidade | GBD |
| QALY | Ano de vida ajustado por qualidade | Custo-efetividade |
| Endemia | Presença constante e esperada de uma doença em uma região | Vigilância |
| Epidemia/Pandemia | Ocorrência acima do esperado, local ou global | Vigilância |

---

## Glossário É Ponto de Partida, Não Destino

Conhecer os termos é o primeiro passo. O segundo é entender como eles se relacionam na prática — como o delineamento escolhido determina qual medida de associação você pode calcular, como o confundimento ameaça qualquer estudo observacional e como o DALY transforma percepções de prioridade em saúde pública.

Se você está em uma iniciação científica, dissertação ou artigo e sente que algum desses conceitos ainda não está sólido, a consultoria metodológica do Laboratório de Epidemiologia existe exatamente para isso: trabalhar diretamente nos pontos que travam o seu projeto.

**[→ Saiba mais sobre a consultoria metodológica do LabEpi](/consultoria/)**

E se você quer ir além do glossário, explore também os nossos artigos sobre tipos de estudo, como calcular e interpretar OR e RR, e como o Global Burden of Disease funciona na prática.

---

## Referências

AGUIAR, P. et al. Odds Ratio: Reflexão sobre a validade de uma medida de referência em epidemiologia. **Acta Médica Portuguesa**, v. 26, n. 5, p. 505–510, set./out. 2013. Disponível em: https://repositorio.insa.pt/bitstream/10400.18/1891/1/Ata%20Med%20Port%202013.pdf. Acesso em: 2 abr. 2026.

BATTISTI, I.; SILVA SMOLSKI, F. Fatores de risco em epidemiologia. In: ANOVA BR. **Conceitos e análises estatísticas com R e JASP**. 2019. Disponível em: https://anovabr.github.io/mqt/fatores-de-risco.html. Acesso em: 2 abr. 2026.

CELESTE, R. K.; FRAGA, S. Medidas de associação em estudos epidemiológicos: risco relativo e odds ratio. **Jornal Português de Gastrenterologia**, [s.l.], 2011. Disponível em: https://lume.ufrgs.br/handle/10183/54354. Acesso em: 2 abr. 2026.

CDC. **Principles of Epidemiology in Public Health Practice: Lesson 3 – Measures of Risk**. Atlanta: Centers for Disease Control and Prevention, 2012. Disponível em: https://archive.cdc.gov/www_cdc_gov/csels/dsepd/ss1978/lesson3/section2.html. Acesso em: 2 abr. 2026.

CDC. **Epidemiology Glossary**. Atlanta: Centers for Disease Control and Prevention, 2024. Disponível em: https://www.cdc.gov/reproductive-health/glossary/index.html. Acesso em: 2 abr. 2026.

GBD BRASIL. **O Estudo GBD**. Disponível em: https://gbdbr.com.br/o-estudo-gbd/. Acesso em: 2 abr. 2026.

IHME. **Estudo de Carga de Doença Global: Gerando Evidências, Informando Políticas**. Seattle: Institute for Health Metrics and Evaluation, 2013. Disponível em: https://www.healthdata.org/sites/default/files/files/policy_report/2013/GBD_GeneratingEvidence/IHME_GBD_GeneratingEvidence_FullReport_PORTUGUESE.pdf. Acesso em: 2 abr. 2026.

IRGENS, L. M. The discovery of the causation of leprosy — scientific reasoning with limited data. **Tidsskrift for den Norske Legeforening**, v. 137, n. 6, p. 474–476, 2017.

NCBI. **Epidemiology Morbidity and Mortality**. Bethesda: National Center for Biotechnology Information / StatPearls, 2022. Disponível em: https://www.ncbi.nlm.nih.gov/books/NBK547668/. Acesso em: 2 abr. 2026.

NCBI. **Prevalence**. Bethesda: National Center for Biotechnology Information / StatPearls, 2023. Disponível em: https://www.ncbi.nlm.nih.gov/books/NBK430867/. Acesso em: 2 abr. 2026.

NIH. **Incidence Rate**. Bethesda: National Library of Medicine, 2022. Disponível em: https://www.nlm.nih.gov/oet/ed/stats/01-200.html. Acesso em: 2 abr. 2026.

OMS. **Global Health Estimates: Leading Causes of DALYs**. Genebra: World Health Organization, 2024. Disponível em: https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/global-health-estimates-leading-causes-of-dalys. Acesso em: 2 abr. 2026.

OUR WORLD IN DATA. **Burden of Disease**. 2024. Disponível em: https://ourworldindata.org/burden-of-disease. Acesso em: 2 abr. 2026.

PORTAL ANMSP. **Controlo do Confundimento**. Disponível em: http://portal.anmsp.pt/03-Investigacao/031-EpiInfoInvestiga/confundimento.htm. Acesso em: 2 abr. 2026.

ROCHA, E. A carga global de doença: fonte de informação para a definição de políticas e avaliação de intervenções em saúde. **Revista Portuguesa de Cardiologia**, v. 36, n. 4, p. 283–285, abr. 2017. DOI: https://doi.org/10.1016/j.repc.2017.02.009.

SCIELO BRASIL. Carga da doença e análise da situação de saúde: resultados da rede de trabalho do Global Burden of Disease (GBD) Brasil. **Revista Brasileira de Epidemiologia**, v. 20, supl. 1, p. 1–3, 2017. DOI: https://doi.org/10.1590/1980-5497201700050001.
