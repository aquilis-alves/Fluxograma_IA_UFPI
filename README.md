# Explorador Curricular - IA UFPI

Uma ferramenta interativa para visualização do fluxo curricular do curso de **Inteligência Artificial** da **Universidade Federal do Piauí (UFPI)**.

## Sobre o Projeto

Este projeto consiste em uma única página web (HTML/CSS/JS) que apresenta uma grade interativa de todas as disciplinas do curso de Inteligência Artificial da UFPI divididas por semestre.

O objetivo principal é ajudar os alunos a mapearem sua trilha no curso, entendendo facilmente a cadeia de dependências de cada disciplina.

### Funcionalidades

- **Visualização Completa**: Grade curricular completa de 1º a 8º semestre.
- **Mapeamento de Requisitos**: Ao clicar em uma disciplina, a interface destaca visualmente:
  - 🟦 **A disciplina selecionada**.
  - 🟨 **Seus pré-requisitos** (disciplinas que você precisa cursar antes).
  - 🟩 **Suas dependências** (disciplinas que serão liberadas após a conclusão).
- **Trilha Recursiva**: O algoritmo calcula automaticamente toda a cadeia de pré-requisitos e disciplinas liberadas (não apenas as diretas).
- **Disciplinas Optativas**: Modal informativo sobre o status das disciplinas optativas.

## Como usar

Por ser uma aplicação totalmente estática ("front-end only"), não é necessária nenhuma instalação ou configuração de servidor.

1. Faça o clone ou baixe este repositório.
2. Abra o arquivo `fluxograma_ia_ufpi.html` em qualquer navegador web atual (Chrome, Firefox, Edge, Safari).
3. Clique em qualquer disciplina na grade para visualizar suas conexões.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica.
- **CSS3 (Vanilla)**: Estilização, grid layout, design responsivo e animações de estado.
- **JavaScript (Vanilla)**: Lógica de seleção, algoritmos recursivos de busca e manipulação do DOM.

## Contribuição

Sinta-se à vontade para abrir _issues_ apontando correções na grade (caso alguma disciplina mude de semestre ou pré-requisito) ou enviar _pull requests_ com melhorias no código.
