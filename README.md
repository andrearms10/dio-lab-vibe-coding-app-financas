# VibeFinance ONE - Inteligência Financeira Conversacional

## Entregando o Desafio na DIO

O PRD foi refinado na plataforma Adapta.<br>
Fazendo um breve resumo do funcionamento desta plataforma de IA. Na Adpata existe uma IA que é o "front" com o usuário e por trás dela temos diversas IA como: GPT-5, DeepSeek v3.2, Gemini 3 Flash, Grok 4.1, Claude 4.5, Perplexity, Nano Banana, GPT Image, Imagen 4.0, Flux 1.1 Pro, dentre outras.<br>
Então o que existe é uma orquestração, a IA principal, que está no front, que eu a chamo de ONE, recebe as minhas requisições, o ONE verifica qual IA é a melhor para responder e repassa para ela. Quando o ONE recebe a reposta da IA que está no "backend", o ONE repassa para mim.<br>
Dado curioso é que o título do app foi dado pelo One e veja que ele colocou o nome dele no app, rsrsrs.

> ### **Prompt Final** (PRD)
#### 1. Contexto e Visão
O VibeFinance ONE é um ecossistema de organização financeira focado em eliminar a barreira da entrada manual de dados. A visão do produto é aplicar o conceito de automação e padrão para colocar a vida financeira do usuário nos trilhos através de conversas naturais, permitindo uma gestão baseada em monitoração inteligente e **análise de comportamento**.

#### 2. Problema
Os aplicativos financeiros tradicionais falham por exigir esforço cognitivo e manual excessivo. O preenchimento de formulários e a categorização manual geram tédio e abandono. Alem disso, os dados são entregues de forma isolada, sem explicar os padrões temporais e comportamentais do usuário.

#### 3. Publico-Alvo
Iniciantes na organização financeira e profissionais independentes (estilo one person business) que buscam agilidade, apreciam design minimalista e precisam de uma ferramenta que identifique tendências automaticamente.

#### 4. Funcionalidades-Chave
1. Registro Conversacional: Entrada de gastos e ganhos via chat em linguagem natural (Ex: Gastei `R$ 45` com café agora).
2. Classificação Automática: Agente de IA identifica a categoria e o contexto da transação sem intervenção do usuário.
3. Relatório de Padrões Temporais (Análise X/Y):
      - Identificacao de recorrências: No periodo X ha mais gasto com cafeteria, no periodo Y ha mais gasto com taxi.
      - Deteccao de Zonas de Economia: Informativo automatico sobre periodos de baixo gasto para validacao de bons habitos.
4. Acompanhamento de Metas: Definicao e monitoramento de objetivos financeiros de forma proativa.
5. Visualizacao Estrategica: Painel de insights inspirado em Power BI para monitorar habitos e gostos dos clientes internos (o proprio usuario).

#### 5. Design e Estética (Apple-Inspired)
- Minimalismo: Uso rigoroso de espacos em branco (white space) e tipografia limpa.
- Interface Glassmorphism: Elementos translucidos, bordas arredondadas e sombras leves.
- Hierarquia: Informacao direta, sem poluicao visual, com foco total na barra de chat.

#### 6. Plano de MVP e Estratégia de Validação
- Principais Telas: Interface de Chat centralizada, Painel de Metas e Relatorios de padroes.
- Recursos Tecnicos Necessarios: Processamento de Linguagem Natural (NLP), Categorizacao Automatica de transacoes e Motor de Recomendacoes proativas.
- Estrategia de Validacao Inicial: Testes de usabilidade e coleta de feedback com usuarios reais para refinar a precisao dos insights financeiros.
- Linguagem e Tom: Comunicacao acessivel e tom educativo, obrigatoriamente em portugues.
- Dashboards: Implementacao de um Dashboard minimalista focado exclusivamente em Metas Financeiras.
- UI/UX Apple: Aplicacao dos principios de Design da Apple (clareza, simplicidade e elegância) desde o prototipo inicial.
- Esboco de Validação (Métrica): O usuário deve ser capaz de registrar três tipos de gastos diferentes em menos de 20 segundos e visualizar o resumo da categoria imediatamente.

#### Interação com LOVABLE
- Crie um app finanças pessoais com base no seguinte PRD (Documento de Solicitação de Produto)
- faça uma tela de login
- eu publiquei, porem, quando acesso a url do app que é https://chat-your-wealth.lovable.app/ aparece a seguinte mensagem -Publish or update your Lovable project for it to appear here.

-  Site no lovable: https://chat-your-wealth.lovable.app
-  existe um botão review security,será que tem algumproblema de segurança?

---

> ### Prints ou pequenos vídeos das interações com a IA;

- Fiz 3 uploads, a saber: <br>
              - 01 apresentação - faço uma apresentação de todas as telas do app;<br>
              - 02 apresentação - navego no app e demonstro as funcionalidades das entradas e retiradas de recursos, os registros em categorias e atualização no saldo;<br>
              - mobile - faço uma apresentação das telas no modo mobile.<br>

- Abaixo são as telas do app de finanças no modo **Desktop**.

**Tela Principal - interação com a IA**
<img width="1421" height="861" alt="image" src="https://github.com/user-attachments/assets/cab29de0-9e7c-48f5-8d96-c1206aad08a7" />

<br>

**Tela Principal e as interações com o lovable**
<img width="1900" height="906" alt="image" src="https://github.com/user-attachments/assets/78ed6740-672f-43c3-9d30-485bd5b99f7a" />

<br>

**Tela de Visão Geral**
<img width="1460" height="865" alt="image" src="https://github.com/user-attachments/assets/b3656270-e9ac-4d22-8500-4ec4b628990b" />

<br>

**Tela de Metas**
<img width="1452" height="853" alt="image" src="https://github.com/user-attachments/assets/f2f2c872-b90f-4878-abf6-9c02fdbeaaf6" />

<br>

**Tela de Insights e Padrões de gastos ou economias**
<img width="1427" height="892" alt="image" src="https://github.com/user-attachments/assets/7fb0d184-79d7-4af1-a006-903080e42558" />


**Tela de Login - exibição de interação como Lovable, sobre o problema de Publicação **
<img width="1908" height="902" alt="image" src="https://github.com/user-attachments/assets/295784f6-b901-4e66-96ee-cfd71083e159" />


---

 > ### Um resumo do que o seu **App de Finanças Pessoais** faz;
 - O app mantém um registro conversacional de entrada/saída, o que é um diferencial, ainda, atendendo ao requisito principal. Automaticamente essas entradas / saídas são categorizadas e listadas na tela de Visão Geral. Nesta tela temos um resumo
   das Metas Financeiras, registro das transações e o saldo atual.<br>
   A terceira tela é a da Meta Financeira propriamente dita, mas de uma forma detalhada, exibindo o acumulado, o valor que se pretende alcansar e um percentual do acumulado.
   A quarta tela, na minha opinião, é a principal, pois é onde temos os insights da IA sobre a nossa base de dados, mostrando onde o dinheiro está escoando ou onde gasto pouco. Isto aqui é **OURO**, é a IA identificando padrões comportamentais
   e exibindo em uma tela bonita, organizada, com cores suaves. Ainda sobre análise da base financeira, a IA desempanhará o papel do assistente financeiro, lembrando dos recursos não creditados nas metas ou reservas financeiras. Ou parabenizando
   a assiduidade, compromisso cumpridos com as metas e reserva.
   Isso tudo é um organismo vivo, acontecendo ao mesmo tempo, as entradas e saídas e os respectivos registros, sejam nas categorias, no saldo, nas metas, na reserva financeira e os insights e padrões sendo comunicados.
   Um ponto que vale ressaltar, o design do app, foi escolhido um estilo minimalista com cores suaves, ícones pequenos, e uma integração perfeita das quatro telas. Há uma harmonização entre os componentes de tela, onde o que é preciso priorizar a
   visualização é feito, mas de forma delicada e bela, tornando a atividade de controle de gastos, algo prazeroso de realizar.
   

---

> ### Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
      - O core do app, que é justamente **realizar as entradas de dados de forma conversacional** (tela 1 - chat), não somente isso, ele recebe os dados e debita ou credita na conta, alocando numa categoria (tela 2 Visão Geral - dashboard).
      - Um item importante para mim é **PADRÂO**, se você tem padrão, já se tem 50% do caminho percorrido. Se vamos criar uma base, esta precisa ser analisada e precisamos buscar padrões de comportamento, seja de gasto, seja de economia (Tela 4 - Insights Financeiros) ou qualquer outro tipo identificado. Esse tipo de informação é **OURO** que precisa ser analisada, trabalhada pela IA e entregue ao usuário em benefício próprio de uma forma aprazível, leve e interessante.
      - E o que não poderia faltar, as Metas Financeiras (tela 3 - Metas Financeiras), o que faz todo sentido tê-las no seu app de finanças. Terá a IA lembrando que há 2 meses você não credita nenhum recurso na meta de viagem à Europa ou na Reserva de Emergência.
      - É a AI entrando no jogo para mostrar, lembrar, dar dicas, analisar, entregar soluções nunca vistas outrora. Quem melhor para ter essa visão estratégica?
      - Deixo minha assinatura no app, quando procuro padrões, comportamentos, monitoramentos e entregas baseadas em análises comportamentais realizadas por IA.

---
    
> ### O que não funcionou como o esperado?
- Dicas de investimentos, ao questionar por dicas a IA não entendeu;
- A publicação do app, simplesmente não abre, interagi com o Lovable, ele fez as verificações, executei o que ele solicitou, mas que não consegui resolver e
  a limitação dos créditos dificultou


---
        
> ### O que aprendeu sobre conversar com IAs?
- Esse modo mudou completamente a forma de interagir com a IA. Agora necessitamos de um PRD, requistos detalhados. Precisamos de 
    um contexto, informações muito mais elaborados, detalhados, claros em termos de funcionalidades, o que esperar do app ou site, 
    a aparência, estilo, descrição de telas, dentre outros. Com requisitos claros teremos num primeiro momento um protótipo rápido, 
    que após análises e interações teremos um produto final, sem codificação, sem preocupação de hardwares e configurações de ambiente.

