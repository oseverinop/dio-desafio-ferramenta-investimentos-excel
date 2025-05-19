
# DESAFIO: Criando uma Ferramenta de Controle de Investimentos com Excel

## Descrição do Desafio
Este laboratório tem como objetivo aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários. A partir de uma compreensão aprofundada sobre como os fundos imobiliários funcionam e as perguntas típicas dos investidores (quanto investir, por quanto tempo, taxa de rendimento, etc.), o desafio consiste em construir uma planilha que ajude o usuário a realizar essas simulações, auxiliando-o a tomar decisões mais informadas sobre seus investimentos. A solução proposta visa automatizar cálculos complexos, como o valor total investido, o patrimônio acumulado e os dividendos mensais, proporcionando ao usuário uma visão clara de seu potencial retorno.

## Objetivos de Aprendizagem
Ao concluir este desafio, você será capaz de:
- Criar ferramentas de simulação de investimentos em Excel;
- Aplicar cálculos financeiros como rendimento mensal e cálculo de dividendos;
- Documentar processos técnicos de forma clara e estruturada;
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.

## Instrutor
- [Felipe Aguiar](https://www.linkedin.com/in/felipeaguiar-exe/)

## Processo de Desenvolvimento da Planilha
O processo de construção da planilha de simulação financeira para fundos imobiliários, detalhado ao longo de diversas etapas e transcrições, representa uma jornada prática na aplicação de ferramentas do Excel para criar uma solução útil e intuitiva. Desde a configuração visual inicial até a implementação de lógicas complexas de simulação baseadas no perfil do investidor, cada fase contribuiu para a criação de uma ferramenta robusta e informativa. Esta descrição visa destacar a progressão desse processo, etapa por etapa, enfatizando as principais ações e os aspectos técnicos mais relevantes (destaques) abordados em cada etapa da construção.



### Etapa 1: Configuração Visual Inicial
- **Ações:** Abertura do Excel, inserção e ajuste de um banner, ocultação das linhas de grade, criação e formatação do cabeçalho e da estrutura básica da tabela de entrada de dados (rótulos, bordas, cores de fundo para campos de entrada e saída).
- **Destaques:** Criação de uma interface visual inicial, separação visual entre entrada de dados e resultados, preparação da estrutura da tabela principal.

### Etapa 2: Implementação dos Cálculos Básicos
- **Ações:** Inserção de dados de exemplo, implementação da fórmula VF (Valor Futuro) para calcular o patrimônio acumulado e uma fórmula simples para estimar os dividendos mensais (1% do patrimônio).
- **Destaques:** Funcionalidade básica de simulação implementada, introdução da função financeira VF, primeiros resultados da simulação visíveis.

### Etapa 3: Adição de Cenários de Investimento
- **Ações:** Criação de uma tabela para simular o patrimônio em diferentes períodos (2, 5, 10, 20, 30 anos) utilizando a função VF, cálculo dos dividendos correspondentes para cada cenário.
- **Destaques:** Expansão da funcionalidade para análise de longo prazo, visualização da evolução do patrimônio em diferentes horizontes de tempo.

### Etapa 4: Introdução de Variáveis Globais
- **Ações:** Criação de uma tabela de configurações para variáveis como salário, rendimento da carteira (taxa mensal) e sugestão de investimento (30% do salário), utilização da variável de rendimento nas fórmulas de cálculo.
- **Destaques:** Tornando a planilha mais dinâmica e personalizável, centralização de parâmetros importantes, preparação para cálculos mais complexos.

### Etapa 5: Nomeação de Intervalos
- **Ações:** Atribuição de nomes descritivos às células (aporte, quantidade_anos, taxa_mensal, etc.) e utilização desses nomes nas fórmulas existentes para melhorar a legibilidade e manutenção.
- **Destaques:** Melhora significativa na clareza e compreensão das fórmulas, boas práticas de organização da planilha.

### Etapa 6: Refinamento Visual e Organização
- **Ações:** Ajustes visuais como inserção de espaçamento, disposição colunar, formatação consistente de números e alinhamento, padronização de fontes, ajustes de largura de colunas e ocultação de colunas desnecessárias.
- **Destaques:** Aprimoramento da estética da planilha, tornando-a mais profissional e fácil de usar, foco na uniformidade visual.

### Etapa 7: Criação do Simulador de Perfil de Investidor
- **Ações:** Introdução do conceito de diferentes tipos de FIIs, criação de uma lista suspensa para selecionar o perfil do investidor (conservador, moderado, agressivo), criação de uma tabela de apoio com percentuais de alocação sugeridos para cada perfil e tipo de FII, utilização da função PROC V com chave composta para buscar dinamicamente os percentuais de alocação.
- **Destaques:** Implementação de um simulador mais avançado considerando o perfil do investidor, uso da função PROCV para busca de dados em tabelas, conceito de tabelas de apoio para organização de dados.

### Etapa 8: Refinamentos e possíveis melhorias
- **Ações:** Refinamentos visuais finais (ocultação de elementos da interface), sugestões para expansão da ferramenta (gráficos, mais projeções), reforço das boas práticas aprendidas.
- **Destaques:** Finalização da ferramenta com foco na usabilidade, incentivo à continuidade do aprendizado e aplicação das técnicas ensinadas.

## Conclusão
Ao longo da construção da planilha de simulação financeira, observamos a evolução de uma simples folha de cálculo para uma ferramenta dinâmica e personalizada. A incorporação de elementos visuais, fórmulas financeiras, cenários de investimento, variáveis globais, intervalos nomeados e, finalmente, um simulador de alocação de carteira baseado no perfil do investidor, demonstra o poder e a versatilidade do Excel. As boas práticas de organização, clareza nas fórmulas e uniformidade visual foram pilares importantes neste processo. O resultado final é uma ferramenta prática e educativa, capaz de auxiliar tanto investidores iniciantes quanto experientes na simulação e planejamento de seus investimentos em fundos imobiliários, reforçando o valor do Excel como uma plataforma flexível para a criação de soluções personalizadas.

---

> Este projeto foi desenvolvido como parte do bootcamp da DIO - Santander - Excel com Inteligência Artificial.
