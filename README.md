# mini-guias
*Guias rápidos* para a utilização de projetos e ferramentas da comunidade OKBR.

Estão todos **listados em https://okfn-brasil.github.io/mini-guias/**


## Adicionar um novo Guia

Supondo ambinete UBUNTU 16 LTS

1. instalar comando `mkdocs`, http://www.mkdocs.org/
2. `git clone  https://github.com/okfn-brasil/fast-guides.git` e `cd fast-guides`
3.  Para criar pasta chamada NovoGuia123 usar `mkdocs new NovoGuia123`... deixar o shell posicionando,`cd NovoGuia123`
4. Editar e criar todos os `doc.md` que desejar sob `NovoGuia123/docs`
5. rodar `mkdocs build`
6. `git add`  e ` git push`  de tudo o que fez...
7. espera 2 minutos o git preparar o site... pronto: a nova documentação está na URL `https://okfn-brasil.github.io/fast-guides/NovoGuia123/site/`  <br/>(para não esquecer inclua a URL no index.html do projeto)

## Entendendo a proposta

A maioria das ferramentas e ambientes de participação da OKBR e da OK-Network requerem uma certa familiarização.

Um Mini-guia é um documento com instruções, senvindo tanto para "quebrar o gelo" e acolher quem quer dar seus primeiros passos com um pouco mais de segurança, como suprir demandas de tradução para o português de *fast guides*  já existentes.
