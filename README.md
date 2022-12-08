# migracao-blob-hcp
Ferramenta para migração dos campos BLOB das tabelas do SIGA para o storage HCP

## Referências

* Binary Large Object (BLOB)
* [Hitachi Content Platform (HCP)](https://www.hitachivantara.com/en-us/products/data-storage/object-storage/content-platform.html)
* [Sistema de Gestão Administrativa (SIGA)](https://github.com/projeto-siga/siga)

## Escopo das Tabelas e Colunas a serem migradas

| TABELA | COLUNA |
|--------|--------|
| [SIGA.EX_DOCUMENTO](https://github.com/projeto-siga/siga/blob/develop/siga-ex/src/main/java/br/gov/jfrj/siga/ex/ExDocumento.java) | CONTEUDO_BLOB_DOC |
| [SIGA.EX_MODELO](https://github.com/projeto-siga/siga/blob/develop/siga-ex/src/main/java/br/gov/jfrj/siga/ex/ExModelo.java) | CONTEUDO_BLOB_MOD |
| [SIGA.EX_MOVIMENTACAO](https://github.com/projeto-siga/siga/blob/develop/siga-ex/src/main/java/br/gov/jfrj/siga/ex/ExMovimentacao.java) | CONTEUDO_BLOB_MOV |
| [SIGA.EX_PREENCHIMENTO](https://github.com/projeto-siga/siga/blob/develop/siga-ex/src/main/java/br/gov/jfrj/siga/ex/ExPreenchimento.java) | PREENCHIMENTO_BLOB |

## Configurações necessárias

TODO: Colocar as configurações das URL, usuário e senha do application.properties

## Funcionamento

TODO: Colocar as orientações das chamadas REST para a migração. Compartilhar a collection do Insomnia.

TODO: Migração por órgãos dos Documentos e Movimentações


## Recomendações

TODO: Recomendar que as chamadas aos endpoints sejam feitas pontualmente acompanhando o andamento no console da aplicação
