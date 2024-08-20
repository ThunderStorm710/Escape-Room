# EscapeRoom

- Design/Implementação de HUD/Front-End, animações (ex. apanhar um item e ficar no canto inferior, clicar em dica, aparecimento de caixas de texto, etc)  ----> Javascript,HTML,CSS, React, essas cenas
- Criação de Navegação e uso de API para criação de interação e serviços de geolocalização ---> ARCore
- Criação de elementos de computação gráfica/virtuais ---> Unreal Engine (Blueprints para nao se ter que programar)
- Integração através do Unreal ---> plugins do Unreal


### NOTA: 
ESTE DOCUMENTO É MERAMENTE DEMONSTRATIVO TUDO O QUE SE LEMBRAREM ADICIONEM É PROVÁVEL QUE ALGO ME TENHA PASSADO AO LADO. A DISTRIBUIÇÃO DE TRABALHOS PARECE-ME BEM MAS PODE SER AJUSTADA. PRINCIPALMENTE PARA QUEM FAZ PARTE GRÁFICA NÃO ESQUECER QUE O TEMA É MISTÉRIO, SUSPENSE, TORNAR AS CENAS COERENTES

## Tarefas

### Front-End (em princípio Filipe Mendes) --> Mockups:
 - Layout e design (simplificar mas com bom gosto e dentro do tema)
 - HUD completo de acordo com protótipo
 - Desenvolver animação de aparecer caixa de texto do briefing
 - Cronómetro
 - Desenvolver o funcionamento da dica
 - Desenvolver interação com item no canto (ex. clicar na cifra e a cifra abrir)
 - Aparecimento do briefing
 - Botão de inserção de resposta e a inserção da resposta em si
 - Partes do Menu que não vão ser apenas gráficas e que necessitam de interação: Inventário, o resto para já ficam só os botões
 - Outras caixas de texto (ex. resposta errada, acertaste!, etc...)


### Navegação e geolocalização (Luis Neto e Pedro Ascensão):

 - Navegação 
 - Interação e recohecimento com superfícies/realidade
 - Integração com o resto do sistema 
 - Integração com camâra em tempo real
 - Geolocalização
 - Lógica de funcionamento/ Parte procedimental (ex. sequência de eventos)


### Computação Gráfica (João Moura):
 - Criar estante com livros
 - Cifra e livro aberto e animação correspondente
 - Gráficos para tornar mais temático (ex. paredes mais misteriosas, quadros, candelabros, etc...)
 - Sonoplastia correspondente (ex. Música misteriosa, livro a abrir, etc)


# Interação Humano-Computador - Fichas Práticas

## Ficha PL 2: Cenários e Atividades

### Objetivo
Consolidar o cenário de uso para o projeto em desenvolvimento.

### Procedimento

1. **Análise Individual (20 min)**
   - Responda às seguintes questões:
     - Quais os motivos e as ações dos potenciais utilizadores?
     - Quem são os sujeitos envolvidos na ação?
     - Quais são as mediações (instrumentais, sociais, práticas) no cenário?
     - Quais são os conhecimentos relevantes ou desconhecimentos no contexto?
     - Quais são os tempos (relativos, absolutos, frequência, sequência das operações)?
     - Qual é o espaço onde ocorre o uso (movimento, iluminação, ruído)?
     - Quais são as relações sociais e organizacionais relevantes?
     - Quais são os outros objetos manipulados e as suas interferências?

2. **Discussão em Grupo (30 min)**
   - Cada membro partilha as suas respostas.
   - Convergem para uma lista comum de pontos para caracterizar o cenário.

3. **Redação da Narrativa (30 min)**
   - Um membro do grupo redige a narrativa com o contributo dos outros.
   - Estruturar a história respondendo às seguintes questões:
     - Onde ocorre a interação?
     - Qual é o problema?
     - Qual é a tarefa que a pessoa tenta realizar?
     - Quais pessoas estão presentes e quais são as suas ações?
     - Quais objetos/dispositivos são utilizados?
     - Quais são os inputs/outputs?
     - Como as ações resolvem o problema?

---

## Ficha PL 3: Sketchbook / HAM

### Objetivo
Desenvolver esboços de interfaces para o projeto, focando nas tarefas principais.

### Procedimento

1. **Criação de Esboços**
   - Esboce as interfaces principais usando papel e caneta/lápis.
   - Pense nos principais objetivos ou tarefas que devem ser possíveis.
   - Leve em consideração a estrutura de Verplank para garantir consistência na interação.

2. **Discussão e Refinamento**
   - Discutir os esboços individualmente e em grupo.
   - Refinar os esboços, garantindo consistência nos controlos e exibições conforme o cenário.

3. **Preenchimento do HAM**
   - Preencha as duas linhas inferiores do HAM para o projeto, utilizando o diagrama e tabela fornecidos como referência.

---

## Ficha PL 4: Design Walkthrough

### Objetivo
Realizar um walkthrough do design utilizando um protótipo de papel.

### Procedimento

1. **Preparação**
   - Assista a vídeos sobre prototipagem em papel para entender melhor o processo.
   - Foque na principal tarefa que o sistema deve suportar.
   - Redesenhe as interfaces para permitir a simulação dessa tarefa.

2. **Execução do Walkthrough**
   - Realize um walkthrough detalhado passo a passo utilizando o protótipo de papel.
   - Discuta cada etapa com a equipa, respondendo a perguntas sobre a eficácia da interface.
   - Anote falhas ou possibilidades de melhorias e ajuste o protótipo conforme necessário.

3. **Repetição**
   - Realize o walkthrough novamente com alguém de fora do projeto para obter novas perspectivas.

---

## Ficha PL 5: Trabalho no Protótipo Digital

### Objetivo
Desenvolver o protótipo digital funcional para o projeto.

### Procedimento

1. **Planeamento**
   - Identifique o que precisa de aprender.
   - Liste as tarefas necessárias, priorizando as mais importantes.
   - Defina quem fará o quê e estime o tempo necessário para cada tarefa.

2. **Definição da Arquitetura de Software**
   - Escolha as bibliotecas e frameworks a serem utilizados.
   - Estruture os componentes principais do sistema.

3. **Desenvolvimento do Protótipo**
   - Comece a trabalhar no protótipo digital, utilizando as definições e planeamento feitos anteriormente.

---

## Ficha PL 8: Avaliação da Usabilidade e Experiência do Utilizador

### Objetivo
Realizar testes de usabilidade e avaliar a experiência do utilizador com o protótipo.

### Procedimento

1. **Preparação**
   - Consulte um plano de teste de usabilidade para estruturar a sua avaliação.
   - Identifique o perfil de utilizador alvo para os testes.
   - Defina as tarefas de avaliação e prepare um questionário de experiência.

2. **Criação do Questionário**
   - Utilize técnicas de Card Sorting para identificar temas relevantes.
   - Crie perguntas com escalas de Likert e Diferencial Semântico, além de perguntas abertas.

3. **Recolha de Dados**
   - Prepare uma tabela para a recolha dos dados durante os testes de usabilidade.

---

## Entrega

As atividades devem ser documentadas e os resultados apresentados conforme as orientações fornecidas em cada ficha prática. O objetivo é garantir que o protótipo evolua de maneira consistente e que seja possível avaliar a eficácia da interface e a experiência do utilizador ao final do processo.



