## IA Generativa: 
Ela se concentra em imitar o comportamento humano usando técnicas de aprendizado de máquina, permitindo que os modelos interajam com o ambiente e executem tarefas sem instruções explícitas sobre o que gerar. Em vez de apenas analisar ou classificar dados existentes, a IA generativa é capaz de produzir conteúdo original, como texto, imagens, áudio e vídeo.

## Modelo de Linguagens Grandes

Os aplicativos de IA generativas são alimentados por LLMs, que são um tipo especializado de modelo de Machine Learning que você pode usar para executar tarefas de PLN (Processamento de Linguagem Natural), incluindo

- Determinar sentimento ou classificar de outra forma o texto em idioma natural.
- Resumir um texto.
- Comparar várias fontes de texto quanto à similaridade semântica.
- Geração de nova linguagem natural.


### Modelo Transformador

A arquitetura do modelo do transformador consiste em dois componentes principais, ou blocos

- Um bloco codificador que criar representações semânticas do vocabulário de treinamento.
- Um bloco decodificador que gerar novas sequências de linguagem.
- O texto é tokenizado para que cada palavrar ou frase seja representada por um token numérico exclusivo.
- Inserções (valores de vetor com várias dimensões são atribuídas aos tokens).
- As camadas de atenção examinam cada token por vez e determinam valores incorporados que refletem os relacionamentos semânticos entre os tokens.
- No decodificador, essas relações são usadas para prever a sequência mais provável de tokens.

### Modelo Tokenização

A primeira etapa no treinamento de um modelo de transformador é decompor o texto de treinamento em tokens.

### Modelo de Inserção

As relações entre tokens são capturadas como vetores, conhecidos como inserções.

![[Pasted image 20250324141115.png]]


### Modelo de Atenção

O modelo de atenção permite que redes neurais se concentrem em partes específicas de uma entrada (como uma frase ou um documento) ao fazer previsões. Em vez de processar todos os dados igualmente, ele aprende a dar mais "atenção" às partes mais relevantes.

- Capturar a força das relações entre tokens usando a técnica de atenção.

#### Exemplo:

Meta: prever o token após "cachorro".

- Represente "Ouvi um cachorro" como vetores.
- Atribua mais peso a "ouvi" e "cachorro".

	Vários tokens possíveis podem vir depois de cachorro.
	O token mais provável é adicionado à sequência, nesse caso , "latir".

## Copilotos

Os copilotos são frequentemente integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de IA.

- Os desenvolvedores podem criar copilotos que enviam prompts para grandes modelos de linguagem e geram conteúdo para uso em aplicativos.
- Os usuários empresariais podem usar copilotos para aumentar sua produtividade e criatividade com conteúdo gerado por IA.

## Engenharia de Prompts
O termo engenharia de prompts descreve o processo de aprimoramento e otimização de prompts (as instruções ou perguntas dadas a um modelo de IA generativa) para obter respostas de melhor qualidade e mais relevantes. É a arte e a ciência de se comunicar eficazmente com a IA.

Tanto os desenvolvedores que projetam aplicativos de IA quanto os consumidores que usam esses aplicativos podem aprimorar a qualidade das respostas da IA generativa utilizando diversas técnicas:

Linguagem Direta e Explícita: Você pode obter conclusões mais úteis sendo explícito e direto sobre o tipo, formato e estilo de resposta que deseja. Evite ambiguidade.
Mensagens do Sistema (System Messages): Para chatbots e agentes de IA, as mensagens do sistema são instruções ou diretrizes ocultas fornecidas ao modelo para descrever como o chat deve funcionar, definir seu "persona" ou estabelecer regras de comportamento.
Fornecer Exemplos (Few-Shot Learning): Incluir exemplos de entrada e saída esperada no seu prompt (conhecido como "few-shot learning") ajuda o modelo a entender o padrão e o formato desejado para a resposta.
Dados de Fundamentação (Grounding Data): Fornecer informações adicionais ou contexto relevante (chamado de "grounding data") diretamente no prompt ou através de uma recuperação de informações, ajuda o modelo a basear suas respostas em fatos específicos e a evitar "alucinações".





