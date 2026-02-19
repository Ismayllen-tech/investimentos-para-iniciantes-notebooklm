# 🧪 Log de Experimentos com Prompts

## Experimento 1 — Resumo Geral
* Prompt usado:
Crie um resumo estruturado (em seções) sobre investimentos para iniciantes, cobrindo: (1) objetivo de investir, (2) risco x retorno, (3) liquidez, (4) renda fixa x renda variável, (5) Tesouro Direto. Use apenas as fontes carregadas e inclua citações.

* Objetivo do prompt:
Obter uma síntese organizada dos principais conceitos presentes nas fontes, servindo como base para o miniguia final.

* Resumo da resposta do NotebookLM:
O NotebookLM apresentou um resumo dividido em cinco seções principais:
1 - Objetivo de investir — Explicou que investir visa preservar e aumentar o patrimônio ao longo do tempo, especialmente acima da inflação, citando materiais do Banco Central e da CVM.
2 - Risco x Retorno — Destacou que investimentos com maior potencial de retorno apresentam maior risco, reforçando a relação direta entre essas variáveis conforme explicado pela CVM.
3 - Liquidez — Definiu como a facilidade de converter um ativo em dinheiro sem perdas significativas, com exemplos como Tesouro Selic (alta liquidez).
4 - Renda fixa x renda variável — Diferenciou previsibilidade e menor risco da renda fixa versus volatilidade e maior potencial de ganho da renda variável.
5 - Tesouro Direto — Apresentou Tesouro Selic, IPCA e Prefixado, explicando para que tipo de investidor cada um é mais indicado.

* Citações indicadas pelo NotebookLM:
Guia da Comissão de Valores Mobiliários — seção sobre tipos de investimento
Material do Banco Central — cidadania financeira e planejamento
Guia do Tesouro Direto — explicação dos títulos públicos

* Análise crítica:
A resposta foi bem estruturada e organizada por tópicos, facilitando a compreensão. As citações reforçaram a confiabilidade do conteúdo. O resumo cumpriu o objetivo de consolidar conceitos centrais das fontes. Como melhoria, poderia incluir exemplos numéricos para ilustrar risco e retorno na prática.


## Experimento 2 — Perfil do Investidor
* Prompt usado:
Com base nas fontes carregadas, descreva os perfis de investidor conservador, moderado e arrojado. Para cada perfil, apresente pelo menos três características e exemplos de investimentos mais adequados. Inclua citações das fontes.

* Objetivo do prompt:
Identificar como as fontes classificam os perfis de investidor e relacionar cada perfil aos tipos de ativos recomendados, reforçando o conceito de adequação ao risco

* Resumo da resposta do NotebookLM:
O NotebookLM estruturou a resposta em três categorias:
1️⃣ Perfil Conservador
Prioriza segurança e preservação do capital
Prefere baixa volatilidade
Busca previsibilidade e alta liquidez
Exemplos indicados: Tesouro Selic, CDBs conservadores
2️⃣ Perfil Moderado
Aceita algum nível de risco
Busca equilíbrio entre segurança e rentabilidade
Diversifica entre renda fixa e renda variável
Exemplos indicados: Tesouro IPCA, fundos balanceados, pequena exposição a ações
3️⃣ Perfil Arrojado
Alta tolerância à volatilidade
Foco em crescimento de patrimônio no longo prazo
Aceita oscilações significativas
Exemplos indicados: Ações, fundos imobiliários, ETFs
O modelo reforçou que a escolha deve estar alinhada ao nível de tolerância ao risco e aos objetivos financeiros do investidor.

* Citações indicadas pelo NotebookLM:
Guia da Comissão de Valores Mobiliários — seção sobre tipos de investimento
Material do Banco Central — cidadania financeira e planejamento
Guia do Tesouro Direto — explicação dos títulos públicos

* Análise crítica:
A resposta apresentou organização clara e alinhamento conceitual entre as fontes. Demonstrou convergência institucional na definição dos perfis de investidor. A estrutura em tópicos facilitou a compreensão. Como melhoria, poderia incluir um exemplo prático de alocação percentual para cada perfil, se presente nas fontes.

## Experimento 3 — Títulos do Tesouro
* Prompt usado:
Explique Tesouro Selic, Tesouro IPCA e Tesouro Prefixado para iniciantes. Para cada título, descreva: (1) como funciona, (2) para quem é indicado, (3) principais riscos, e (4) o que pode acontecer se houver venda antes do vencimento. Utilize apenas as fontes carregadas e inclua citações.

* Objetivo do prompt:
Compreender as diferenças entre os principais títulos públicos oferecidos pelo Tesouro Direto e analisar seus riscos, indicações e funcionamento, com base nas fontes institucionais.

* Resumo da resposta do NotebookLM:
O NotebookLM organizou a resposta por tipo de título:
1️⃣ Tesouro Selic
Funcionamento: acompanha a taxa básica de juros (Selic).
Indicado para: reserva de emergência e investidores conservadores.
Risco: baixo risco de mercado, pois sofre pouca oscilação.
Venda antecipada: geralmente apresenta menor impacto negativo, sendo o mais estável entre os três.
2️⃣ Tesouro IPCA
Funcionamento: rende IPCA (inflação) + taxa fixa definida na compra.
Indicado para: proteção contra perda do poder de compra no longo prazo.
Risco: oscilações no curto prazo devido à marcação a mercado.
Venda antecipada: pode gerar ganho ou perda dependendo das taxas no momento da venda.
3️⃣ Tesouro Prefixado
Funcionamento: taxa fixa definida no momento da aplicação.
Indicado para: quem acredita que a taxa contratada será vantajosa até o vencimento.
Risco: maior sensibilidade à variação das taxas de juros.
Venda antecipada: pode gerar perdas se as taxas subirem após a compra.
A resposta destacou o conceito de marcação a mercado como fator determinante nas oscilações dos títulos prefixados e indexados à inflação.

* Citações indicadas pelo NotebookLM:
Guia do Tesouro Direto — seção explicativa sobre tipos de títulos
Comissão de Valores Mobiliários — explicação sobre risco e renda fixa
Banco Central — orientação sobre taxa Selic

* Análise crítica:
A resposta foi estruturada de forma didática e comparativa, facilitando a compreensão das diferenças entre os títulos. A inclusão da explicação sobre marcação a mercado demonstra profundidade conceitual. As citações sustentaram adequadamente as definições e riscos apresentados. Como possível melhoria, poderia incluir um exemplo numérico ilustrando os efeitos da venda antecipada.

## Experimento 4 — Checklist
* Prompt usado:
Crie um checklist em 10 passos para começar a investir com segurança, desde o planejamento financeiro até a primeira aplicação. Utilize apenas as fontes carregadas e inclua citações.

* Objetivo do prompt:
Transformar os conceitos teóricos das fontes em um guia prático e sequencial para iniciantes, conectando educação financeira à ação concreta.

* Resumo da resposta do NotebookLM:
O NotebookLM estruturou o checklist em etapas progressivas:
1️⃣ Eduque-se financeiramente
2️⃣Transforme sonhos em projetos
3️⃣ Elabore um orçamento detalhado
4️⃣Busque o superávit financeiro
5️⃣Elimine dívidas caras
6️⃣ Construa sua Reserva de Emergência
7️⃣Descubra seu Perfil de Investidor.
8️⃣Escolha uma instituição financeira autorizada
9️⃣ Entenda o tripé dos investimentos
🔟 Realize sua primeira aplicação
O modelo destacou que o planejamento financeiro é pré-requisito para qualquer estratégia de investimento.

* Citações indicadas pelo NotebookLM:
Banco Central — seção sobre planejamento financeiro
Comissão de Valores Mobiliários — orientação ao investidor iniciante
Tesouro Direto — recomendações para primeiros investimentos
FGV — organização financeira pessoal

* Análise crítica:
A resposta foi clara, prática e bem organizada em sequência lógica. Conectou conceitos teóricos com aplicação prática, reforçando a importância da reserva de emergência antes de investir. As citações deram suporte às recomendações. Como melhoria, poderia detalhar melhor os critérios para diversificação com exemplos percentuais, caso as fontes abordem esse aspecto.

## Experimento 5 — Erros Comuns
* Prompt usado:
Liste 10 erros comuns de investidores iniciantes mencionados ou inferidos a partir das fontes carregadas. Para cada erro, explique por que ele é problemático e como pode ser evitado. Inclua citações.

* Objetivo do prompt:
Identificar comportamentos inadequados frequentemente associados a iniciantes e relacioná-los às orientações preventivas presentes nas fontes institucionais.

* Resumo da resposta do NotebookLM:
O NotebookLM apresentou uma lista estruturada com explicação e correção para cada erro. Entre os principais:
1️⃣ Achar que domina o assunto sem estudo prévio (Falsa sensação de conhecimento
2️⃣ Não ter metas claras (Investir sem um "projeto")
3️⃣ Confundir desejos com necessidades
4️⃣ Não construir uma reserva de emergência antes de investir
5️⃣ Ignorar o próprio perfil de investidor
6️⃣ Acreditar em promessas de alta rentabilidade com baixo risco
7️⃣ Realizar resgate antecipado de títulos sujeitos à volatilidade
8️⃣ Falta de diversificação da carteira
9️⃣ Não considerar os custos e impostos envolvidos
🔟 Seguir dicas de influenciadores sem senso crítico
O modelo destacou que a maioria dos erros decorre da falta de planejamento e educação financeira.

* Citações indicadas pelo NotebookLM:
Comissão de Valores Mobiliários — orientações ao investidor iniciante
Banco Central — planejamento financeiro e consumo consciente
Tesouro Direto — recomendações para primeiros investimentos

* Análise crítica:
A resposta foi coerente e alinhada às orientações das fontes. Demonstrou capacidade de inferência responsável a partir dos conteúdos institucionais. As explicações conectaram erro e solução de forma clara. Como melhoria, poderia especificar quais erros são explicitamente mencionados nas fontes e quais foram inferidos, para maior rigor acadêmico.
