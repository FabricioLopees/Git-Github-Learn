# Git-Learn
**Local para testar e aprender sobre Git e Github**


## Principais Regras - Conventional Commits

Mensagem de commit:
``` 
<tipo>[escopo opicional]: <descrição>

[corpo opicional]

[rodapé opicional]
``` 
---
### OBRIGATÓRIO

`<tipo>: <descrição>`

- escrever tudo em letra minúscula (tipo e descrição);
- descrever o tipo;
- sempre apresentar a descrição;
- não escrever uma linha com mias de 100 caracteres. Faça uma quebra de linha, mas não ultrapasse os 100 caracteres. Vale para:
	- tipo
	- descrição
	- corpo
	- rodapé
---

Flags para `<tipo>`
```
[
  'build' -> alterações em configurações de compilação, dependências ou scripts de build;
  'chore' -> ajustes no código, não é nova feature e nem correção de bug;
  'docs'  -> alteração na documentação;
  'feat'  -> nova funcionalidade
  'fix'   -> correção de erros
  'perf'  -> melhora de performance no código;
  'refactor' -> alteração de estrutura, legibilidade ou organização do código;
  'revert' -> desfaz uma alteração anterior;
  'style' -> ajustes na formatação do código, ex: identação;
]
``` 
Existem outras, inclusive algumas eu retirei da lista, pois não é útil para mim neste momento. Como 'ci' que tem haver com 'continuous integration'.

Para informações com mais detalhes ou exemplos de commit: [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/#resumo)
