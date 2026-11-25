# Animação

Site de estudo sobre animações em CSS. Cada página mostra um exemplo prático de `transition` ou `@keyframes`.

## Captura de tela

<!-- Adicione aqui um print de uma das páginas de exemplo. -->

## Tecnologias

- HTML5
- CSS3 (`transition`, `@keyframes`, `animation`, `animation-delay`)

Não usa JavaScript.

## Conceitos

O arquivo `TransitionEKeyframes.txt` resume a diferença:

- **Transition**: animação por estado. Acontece quando algo muda de um estado para outro (por exemplo, ao passar o mouse).
- **Keyframes**: animação autônoma. Acontece sozinha.

## Páginas

| Página | Exemplo |
| --- | --- |
| `index.html` | Menu de navegação para os exemplos |
| `exemplo1.html` | Botão que sobe e ganha sombra ao passar o mouse (`transition`) |
| `exemplo2.html` | Spinner de carregamento girando (`@keyframes`) |
| `exemplo3.html` | Bolinha que pula em loop (`@keyframes` com `alternate`) |
| `exemplo4.html` | Frases que surgem uma depois da outra, com atraso (`animation-delay`) |

## Estrutura

```
Animacao/
├── index.html
├── exemplo1.html ... exemplo4.html
├── TransitionEKeyframes.txt
└── css/
    ├── style.css      (estilos comuns: menu e layout)
    └── exemplo1.css ... exemplo4.css
```

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Fernando3M/Animacao.git
   ```
2. Abra o `index.html` no navegador e use o menu para ver cada exemplo.

## Autor

[Fernando3M](https://github.com/Fernando3M)
