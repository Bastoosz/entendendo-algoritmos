<div align="center">

# Entendendo Algoritmos

<p>
  <kbd>&nbsp;Python 3.x&nbsp;</kbd> &nbsp; <kbd>&nbsp;Em andamento&nbsp;</kbd> &nbsp; <kbd>&nbsp;Grokking Algorithms&nbsp;</kbd>
</p>

Registro público dos meus estudos a partir do livro <strong>Entendendo Algoritmos</strong>, de Aditya Bhargava.
Cada algoritmo é lido, reimplementado do zero e estendido além do que o livro entrega.

</div>

<br>

## Sobre o projeto

Este repositório não é um depósito de código copiado. A ideia é aprender de verdade, então cada algoritmo passa por um processo: entender a lógica, reconstruir sem consultar e estender com alguma variação que force o entendimento a sair da teoria.

O foco não está na quantidade de commits, e sim na profundidade. Cada pasta reúne uma implementação limpa, uma explicação escrita com as minhas próprias palavras e pelo menos uma extensão que o livro não traz.

## Metodologia

O ciclo aplicado a cada algoritmo tem três etapas.

**Ler e entender.** Acompanho a explicação do livro até conseguir descrever o algoritmo em uma frase, sem jargão.

**Reimplementar do zero.** Fecho o livro e reescrevo tudo em um arquivo vazio. Se não consigo reconstruir sem olhar, então ainda não aprendi, apenas reconheci.

**Incrementar.** Adiciono uma variação que muda comportamento ou testa limites: casos de borda, versão alternativa, medição de desempenho ou aplicação em um problema concreto. Mudança apenas cosmética não entra.

Ao final, cada pasta ganha uma nota curta explicando quando usar o algoritmo, por que ele funciona, qual a complexidade e onde ele quebra.

## Progresso

- [ ] 01. Busca Binária
- [ ] 02. Ordenação por Seleção
- [ ] 03. Recursão
- [ ] 04. Quicksort
- [ ] 05. Tabelas Hash
- [ ] 06. Pesquisa em Largura (BFS)
- [ ] 07. Algoritmo de Dijkstra
- [ ] 08. Algoritmos Gulosos
- [ ] 09. Programação Dinâmica
- [ ] 10. K-Vizinhos Mais Próximos (KNN)

## Estrutura do repositório

```
entendendo-algoritmos/
├── 01-busca-binaria/
│   ├── busca_binaria.py     # implementação do livro, reescrita do zero
│   ├── extensao.py          # variação além do livro
│   └── README.md            # notas, complexidade e análise
├── 02-ordenacao-selecao/
│   └── ...
├── 03-recursao/
│   └── ...
└── README.md
```

Cada pasta é autossuficiente. Para entender um algoritmo específico, basta abrir o README dela.

## Como acompanhar

O jeito recomendado de ler este repositório é pela ordem dos capítulos, começando pela busca binária. A progressão do livro é intencional: conceitos como recursão e divisão e conquista aparecem antes de serem usados em quicksort e nos grafos.

Se o interesse é um tema específico, os títulos das pastas apontam direto para o algoritmo.

## Stack

As implementações usam apenas a biblioteca padrão do Python, sem dependências externas. A intenção é manter o foco na lógica do algoritmo, não em ferramentas ao redor.

## Referência

Bhargava, Aditya. *Entendendo Algoritmos: Um guia ilustrado para programadores e outros curiosos*. Novatec.

<div align="center">
<sub>Repositório de estudo em evolução. O conteúdo cresce conforme o livro avança.</sub>
</div>
