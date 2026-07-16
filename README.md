# Caderno Temático: Código Limpo e Boas Práticas de Programação

Caderno temático sobre Código Limpo e boas práticas, construído com NotebookLM como ferramenta de estudo ativo.

## Contexto e Objetivos

Como estudante de Engenharia de Software, escolhi Código Limpo e boas práticas de programação como tema deste caderno por ser a base para escrever software de qualidade, fácil de manter e ler. O objetivo foi usar o NotebookLM como ferramenta de estudo ativo, organizando fontes confiáveis sobre o tema e extraindo conhecimento estruturado através de prompts direcionados.

## Curadoria de Fontes

**Fontes de texto (PDF):**
- Código Limpo (livro completo) — codigo-limpo-completo-pt_text.pdf
- Clean Architecture, Robert Cecil Martin (Book - Clean Architecture)
- Refactoring: Improving the Design of Existing Code, Addison-Wesley Professional
- Orientação a Objetos e SOLID para Ninjas: Projetando classes flexíveis, Mauricio Aniche
- Refatoração: Melhorando a Qualidade de Código Pré-Existente — IME-USP

**Fontes de vídeo:**
- Filipe Deschamps — YouTube
- Clean Code // Dicionário do Programador
- Como desenvolver boas práticas de programação? com Fabio Akita
- SOLID: o que é e quais são os 5 princípios da Programação Orientada a Objetos (POO)
- AS BOAS PRÁTICAS NA PROGRAMAÇÃO NA ERA DA IA!

## Engenharia de Prompts

**Prompt 1:** Resuma os principais princípios de Código Limpo abordados nas fontes, organizados por categoria (nomenclatura, funções, comentários, formatação).

Resultado: resumo estruturado em 4 categorias (nomenclatura, funções, comentários, formatação) mais uma seção extra com princípios complementares (Regra do Escoteiro, DRY, KISS). Resposta completa na primeira tentativa, sem necessidade de refinar.

**Prompt 2:** Crie um glossário com os 15 termos mais importantes sobre Código Limpo e boas práticas de programação citados nas fontes, com definição curta de cada um.

Resultado: glossário completo com 15 termos técnicos (SOLID, SRP, OCP, LSP, ISP, DIP, Refatoração, Débito Técnico, KISS, DRY, Encapsulamento, Coesão, Acoplamento, Regra do Escoteiro, Código Limpo).

**Prompt 3:** Quais são as práticas que Robert C. Martin considera mais críticas para evitar código ruim? Cite exemplos práticos mencionados nas fontes.

Resultado: 7 práticas centrais com exemplos práticos de código para cada uma (SRP e funções pequenas, OCP e polimorfismo, DIP, nomenclatura significativa, eliminação de comentários desnecessários, TDD, gestão de dependências e arquitetura).

**Prompt 4:** Compare a visão de Clean Code com os princípios SOLID: como eles se complementam?

Resultado: comparação usando a analogia dos "tijolos e paredes" de Uncle Bob, mostrando a diferença de granularidade entre os dois conjuntos de práticas e os pontos de convergência (SRP, DIP, OCP).

## Miniguia de Estudo

### Resumo estruturado

**Nomenclatura**
Nomes devem ser diretos e revelar intenção sem precisar de comentário. Substantivos para classes, verbos para métodos/funções. Evitar abreviações confusas e notação húngara.

**Funções**
Devem ser pequenas e fazer apenas uma coisa. Poucos parâmetros, evitar flags booleanas, sem efeitos colaterais ocultos.

**Comentários**
Código bem escrito dispensa comentário. Quando necessário, explicar o "porquê", nunca o "como". Testes bem escritos também funcionam como documentação.

**Formatação**
Linhas em branco separando blocos lógicos, indentação consistente, linhas curtas, espaçamento em operadores.

**Princípios complementares**
Regra do Escoteiro (deixar o código mais limpo do que encontrou), DRY (não repetir lógica), KISS (priorizar simplicidade).

### Glossário

| Termo | Definição |
|---|---|
| Código Limpo | Conjunto de práticas para escrever software legível e fácil de manter |
| SOLID | 5 princípios de orientação a objetos (SRP, OCP, LSP, ISP, DIP) |
| SRP | Uma classe deve ter apenas um motivo para mudar |
| OCP | Aberto para extensão, fechado para modificação |
| LSP | Classes derivadas devem substituir a base sem quebrar o sistema |
| ISP | Não forçar dependência de métodos não usados |
| DIP | Depender de abstrações, não de implementações concretas |
| Refatoração | Melhorar a estrutura do código sem mudar seu comportamento |
| Débito Técnico | Custo futuro de uma solução rápida e mal feita agora |
| KISS | Manter a solução simples |
| DRY | Não duplicar lógica no sistema |
| Encapsulamento | Esconder como um método funciona, expor só o que ele faz |
| Coesão | O quanto uma classe foca em uma única responsabilidade |
| Acoplamento | Grau de dependência entre classes/módulos |
| Regra do Escoteiro | Deixar o código um pouco mais limpo do que encontrou |

### Prompts reutilizáveis

- "Resuma os principais princípios de [tema] abordados nas fontes, organizados por categoria."
- "Crie um glossário com os termos mais importantes sobre [tema] citados nas fontes."
- "Quais são as práticas mais críticas sobre [tema] segundo [autor]? Cite exemplos práticos."
- "Compare [conceito A] com [conceito B]: como eles se complementam?"
