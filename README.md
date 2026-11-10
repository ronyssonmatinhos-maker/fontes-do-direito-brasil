# Fontes do Direito Brasil

Acervo público e pesquisável de fontes jurídicas brasileiras, com foco em:
- legislação
- jurisprudência
- súmulas e orientações jurisprudenciais
- precedentes e temas repetitivos
- teses e repertórios jurídicos
- fontes regulatórias e administrativas

O objetivo é unir, em um só lugar, o que normalmente fica espalhado por vários portais oficiais e repositórios, com uma estrutura que permita busca, filtro, curadoria e atualização contínua.

## Visão

Uma base confiável de fontes do direito brasileiro, organizada por origem e tipo, com rastreabilidade para a fonte oficial e com suporte para:
- busca textual
- busca semântica
- filtragem por tribunal, categoria e tema
- comparação entre fontes normativas e jurisprudenciais
- consulta por advogados, estudantes e pesquisadores

## Estrutura proposta

```text
fontes-do-direito-brasil/
├── README.md
├── .gitignore
├── LICENSE
├── docs/
│   ├── README.md
│   ├── metodologia.md
│   ├── fontes-oficiais.md
│   └── roadmap.md
├── data/
│   ├── README.md
│   ├── fontes.json
│   ├── legislacao/
│   ├── jurisprudencia/
│   │   ├── stf/
│   │   ├── stj/
│   │   ├── tst/
│   │   ├── trt9/
│   │   └── outros/
│   ├── sumulas/
│   ├── orientacoes/
│   ├── precedentes/
│   ├── temas/
│   └── teses/
├── schemas/
│   ├── fonte.schema.json
│   └── exemplo.json
├── scripts/
│   ├── README.md
│   ├── fetch_sources.py
│   ├── normalize_records.py
│   ├── export_json.py
│   └── search_index.py
├── src/
│   ├── README.md
│   ├── models/
│   ├── search/
│   ├── api/
│   └── cli/
└── notebooks/
    └── exploracao.ipynb
```

## Tipos de fonte

- Lei / dispositivo legal
- Constituição / norma suprema
- Súmula
- Súmula vinculante
- Orientação jurisprudencial (OJ)
- Acórdão
- Sentença
- Tema repetitivo
- Recurso repetitivo / tese de repetitivo
- Precedente qualificado
- Regulamento / ato administrativo
- Tratado / convenção internacional

## Fontes prioritárias

As prioridades iniciais devem ser:

1. STF
2. STJ
3. TST
4. TRT9
5. CNJ
6. tribunais regionais relevantes
7. fontes oficiais legislativas federais e estaduais

## Regras de qualidade

- toda entrada deve ter origem oficial ou pública
- registrar URL oficial e data de coleta
- manter ementa ou resumo textual breve
- separar o que é fonte normativa do que é busca/curadoria
- manter evidência de procedência
- não inventar classificação sem base documental

## Objetivo do MVP

O primeiro mínimo viável deve permitir:
- buscar por palavra-chave
- filtrar por tribunal e tipo de fonte
- consultar legislação, súmula, OJ e precedentes
- visualizar a fonte oficial e a data da coleta
- exportar resultados em JSON/CSV

## Roadmap

### Fase 1 — base estável
- definição do schema comum
- abertura do catálogo de fontes
- primeira carga dos principais tribunais
- busca básica por texto e filtro

### Fase 2 — profundidade jurídica
- classificação por temas e subtemas
- indexação semântica
- consulta por intenção e tese
- relacionamento entre decisões e normas

### Fase 3 — ferramentas para advogados
- busca comparativa por tema
- painel por tribunal e relevância
- exportação para petições e revisão de precedentes
- API pública simples

## Diferencial

Este projeto não pretende ser só um repositório de leis. Ele busca unificar:
- legislação
- súmulas e OJs
- precedentes
- jurisprudência
- temas dos tribunais
- e a base de referência que os advogados usam na prática

A ideia é servir tanto para pesquisa direta quanto para construção de uma base documental sólida para IA, rankings, análise de precedentes e comparações jurídicas.

## Contribuição

Contribuições são bem-vindas, especialmente para:
- mapeamento de fontes oficiais
- coleta de registros por tribunal
- normalização de metadados
- validação de links e procedência
- melhoria do schema de dados

## Licença

A aplicação deve seguir a licença adequada à sua distribuição e ao uso dos dados. Para o código, recomendamos MIT ou Apache 2.0. Para os dados, sempre respeitar as regras da fonte original.

## Próximo passo

A partir do próximo passo, vamos montar:
1. o schema principal
2. a lista de fontes oficiais
3. os primeiros arquivos de dados
4. a estrutura inicial de busca

Se quiser, posso continuar criando o scaffold completo diretamente no repositório, incluindo os primeiros JSONs de exemplo e a base documental inicial.
