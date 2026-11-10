# Metodologia

## Objeto

Este repositório tem como objetivo reunir fontes jurídicas brasileiras de forma organizada, rastreável e pesquisável. A base deve priorizar fontes oficiais, públicas e verificáveis, com foco em:

- legislação
- jurisprudência
- súmulas e orientações jurisprudenciais
- precedentes e temas repetitivos
- fontes regulatórias e administrativas

## Princípios

### 1. Fonte oficial e rastreável
Toda entrada deve ter referência direta à origem oficial, como:
- tribunal
- portal oficial
- órgão administrativo
- base pública oficial
- mesmo que o dado seja exportado e armazenado localmente

### 2. Estrutura uniforme
Cada registro deve seguir um schema único com metadados mínimos:
- id
- tipo
- categoria
- tribunal
- título
- resumo
- texto ou trecho relevante
- palavras-chave
- fonte oficial
- URL
- data de coleta
- status
- número / ano / tags

### 3. Separação por categoria
Não misturar tudo em um único bloco. O repositório separa por:
- legislação
- jurisprudência
- súmulas
- orientações
- precedentes
- temas
- teses

### 4. Relevância jurídica, não só volume
O objetivo não é acumular dados aleatoriamente, mas montar uma base útil para a prática jurídica. Portanto, as fontes devem ser classificadas por valor de uso, como:
- vinculante
- repetitiva
- orientativa
- normativa
- informativa

### 5. Evidência de procedência
Cada registro deve documentar:
- o órgão responsável
- a URL oficial
- a data de coleta
- a referência do documento original
- o tipo de dado (texto, resumo, ementa etc.)

## Processo de coleta

1. identificar fonte oficial
2. validar a URL e o tipo de documento
3. normalizar o metadado
4. aplicar schema comum
5. verificar se o texto ou resumos podem ser preservados
6. registrar data da coleta e origem
7. manter arquivo em formato legível, como JSON ou Markdown

## Critérios de classificação

### Categoria
- legislacao
- jurisprudencia
- orientacao
- sumula
- precedente
- tema
- tese
- regulatorio

### Tipo
- lei
- constituicao
- sumula
- sumula_vinculante
- orientacao_jurisprudencial
- acordao
- sentenca
- tema_repetitivo
- precedente
- tese
- regulamento
- tratado

## Cobertura inicial recomendada

As fontes prioritárias para o MVP são:
- STF
- STJ
- TST
- TRT9
- CNJ
- tribunais regionais com relevância prática
- legislação federal e estadual

## Limites

- nem toda base oficial expõe seus dados em API pública
- algumas decisões exigem coleta por scraping ou integração indireta
- jurisprudência e sentenças podem ter atualização lenta ou recortes específicos
- a coleta deve respeitar regras de uso e termos da fonte original

## Objetivo

Criaremos um acervo jurídico brasileiro confiável, pesquisável e organizado, em vez de um monte de arquivos soltos sem rastreabilidade.
