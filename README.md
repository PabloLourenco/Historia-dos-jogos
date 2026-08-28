# História-dos-jogos

# 🎮 Segundo Cérebro: Criação e Evolução dos Jogos

Repositório desenvolvido como parte do Desafio de Projeto da **DIO (Digital Innovation One)**: *Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM*.

---

## 🎯 1. Contexto e Objetivos
* **Tema Escolhido:** História, Arquitetura Técnica e Game Design na Evolução dos Videogames.
* **Objetivo de Estudo:** Compreender como as limitações de hardware moldaram as técnicas de level design e arquitetura de software (desde a era dos 8/16 bits até as engines modernas) e documentar esse conhecimento usando o NotebookLM como base de dados analítica.

---

## 📚 2. Curadoria de Fontes
Foram selecionadas 4 a 5 fontes complementares cobrindo história, engenharia de software e design de níveis:

1. **História Geral:** *History of video games* — Artigo enciclopédico de referência cronológica (Wikipedia).
2. **Engenharia e Arquitetura:** *Classic Game Postmortem: 'Doom' (John Romero & Tom Hall - GDC)* — Transcrição de palestra técnica sobre BSP trees e motores pseudo-3D.
3. **Level Design & Pedagogia:** *Super Mario 3D World's 4 Step Level Design (Game Maker's Toolkit)* — Análise do conceito de *Kishōtenketsu* aplicado a jogos de plataforma.
4. **Narrativa e Produção:** *Classic Postmortem: The Making of Half-Life (Game Developer / Gamasutra)* — Estudo sobre narrativa integrada e processo Cabal na Valve.
5. **Evolução de Ferramentas:** *Game engine / A Evolução das Game Engines* — Resumo técnico sobre a transição de código proprietário monolítico para motores comerciais modulares (Unreal, Unity, Godot).

---

## ⚙️ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Prompt 1 (Comparativo Técnico):
* **Prompt:** *"Com base nas fontes, como a transição do 2D para o 3D nos anos 90 impactou a arquitetura das engines e a forma como os desenvolvedores constroem fases?"*
* **Resultado:** A IA cruzou os dados do post-mortem de *Doom* e da evolução das engines, destacando a necessidade de cálculo de oclusão espacial (BSP) e a perda de controle de câmera fixo que existia no design 2D.
* **Ajuste / Cicatriz:** No início, o prompt genérico *"Fale sobre o 3D"* gerou respostas superficiais. Adicionar restrições de arquitetura de software e design de fases forçou a IA a citar trechos específicos das fontes.

### Prompt 2 (Design e Mecânica):
* **Prompt:** *"Explique como o design de fases em 4 passos (Kishōtenketsu) difere da narrativa ambiental introduzida em Half-Life."*
* **Resultado:** Síntese clara entre a pedagogia puramente mecânica da Nintendo e a imersão diegética da Valve.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### Resumo Estruturado do Assunto:
1. **Era dos Padrões Rígidos (Anos 70/80):** Código acoplado diretamente aos registradores e chips gráficos, dependência de *tricks* de hardware para scroll de tela e memória restrita em bytes.
2. **Separação de Engine e Conteúdo (Anos 90):** Surgimento do pipeline moderno com arquivos `.wad`/`.bsp`, renderização por software/hardware acelerado e narrativa em tempo real.
3. **A Era das Engines Modulares (Anos 2000-Atual):** Democratização com Unity, Godot e Unreal, suporte a shaders programáveis, física unificada e streaming assíncrono.

### Glossário de Conceitos Aprendidos:
* **BSP (Binary Space Partitioning):** Algoritmo para estruturar árvores de polígonos e acelerar a renderização calculando apenas o que é visível.
* **Game Engine:** Camada de software intermediária que gerencia renderização, física, som e scripts, desacoplada do conteúdo do jogo.
* **Kishōtenketsu:** Estrutura de design em 4 etapas (Introdução $\rightarrow$ Desenvolvimento $\rightarrow$ Reviravolta $\rightarrow$ Desfecho/Aplicação).
* **Diegese / Narrativa Ambiental:** Transmissão de história diretamente pelo cenário e ações em tempo real, sem interrupção de cutscenes pré-renderizadas.
* **Game Loop:** Ciclo contínuo de execução que processa entradas (*input*), atualiza o estado do jogo (*update*) e desenha o quadro (*render*).

### Prompts Reutilizáveis para Futuras Revisões:
* `Quais foram as principais limitações de memória mencionadas e como foram resolvidas?`
* `Gere uma tabela comparativa com: Conceito | Exemplo no Jogo | Benefício para o Jogador.`
* `Crie um quiz de 5 perguntas com gabarito comentado sobre a transição para engines 3D.`

* ### 📸 Evidências dos Testes (Prints do NotebookLM)

#### Teste 1: Transição 2D para 3D
* **Parte 1 (Pergunta e Início da Resposta):**
![Teste 1 - Parte 1](./Print1(1).png)

* **Parte 2 (Continuação e Citações de Fontes):**
![Teste 1 - Parte 2](./Print1(2).png)

---

#### Teste 2: Metodologias de Game Design (Nintendo vs Valve)
* **Parte 1 (Pergunta e Análise):**
![Teste 2 - Parte 1](./Print2(1).png)

* **Parte 2 (Continuação da Resposta):**
![Teste 2 - Parte 2](./Print2(2).png)

---

#### Teste 3: Tabela de Evolução das Engines
* **Parte 1 (Pergunta e Tabela):**
![Teste 3 - Parte 1](./Print3(1).png)

* **Parte 2 (Detalhamento Técnico):**
![Teste 3 - Parte 2](./Print3(2).png)
