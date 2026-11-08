# my-parfum

Guia e oráculo da minha coleção de perfumes. Registra o que eu tenho, avalia o que falta e ajuda a decidir as próximas compras, com dados do [Fragrantica](https://www.fragrantica.com/).

## Por onde começar

| Quero... | Abra |
|---|---|
| Ver o que eu tenho | [colecao/README.md](colecao/README.md) |
| Saber o que a coleção tem e o que falta | [analise/avaliacao-da-colecao.md](analise/avaliacao-da-colecao.md) |
| Decidir os próximos 2 perfumes | [analise/proximas-compras.md](analise/proximas-compras.md) |
| Conferir ou corrigir o que o oráculo sabe de mim | [perfil/perfil-do-usuario.md](perfil/perfil-do-usuario.md) |
| Entender como cada perfume é classificado | [referencias/metodo-de-classificacao.md](referencias/metodo-de-classificacao.md) |

## Estrutura

```
my-parfum/
├── CLAUDE.md                  Instruções do oráculo (papel, princípios, formato das respostas)
├── colecao/                   Uma ficha por perfume que eu tenho
├── candidatos/                Fichas dos perfumes que estou considerando comprar
├── analise/                   Avaliação da coleção e recomendações de compra
├── perfil/                    Meu gosto, clima, ocasiões, orçamento e pendências
├── referencias/               Método de classificação e fontes
├── dados/fragrantica/         Dados estruturados coletados (votos, acordes, notas)
└── arquivo-historico/         Versões originais dos arquivos antigos (não apagar)
```

## Como usar o oráculo

Abra uma conversa do Claude Code nesta pasta. O arquivo [CLAUDE.md](CLAUDE.md) é lido automaticamente e o oráculo já conhece o perfil e a coleção. Exemplos:

- "O que acha do Dior Sauvage para a minha coleção?"
- "Compare o Azzaro Pour Homme com o meu Fervo Intenso."
- "Comprei o perfume X. Atualize o repositório."

## Convenções

Arquivos em kebab-case, em português, sem abreviações. Cada afirmação é marcada como **Confirmado**, **Estimado** ou **Não sei**. Preços só entram se forem verificados em loja brasileira.
