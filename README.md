# CID 10 - ETL

## Estatísticas Anuais - CID-10 de auxílios por incapacidade temporária "acidentários" (quando relacionado a atividade profissional)

Arquivos (Acidentários) baixados de: https://www.gov.br/trabalho-e-previdencia/pt-br/assuntos/previdencia-social/saude-e-seguranca-do-trabalhador/dados-de-acidentes-do-trabalho/tabelas-cid-10

Link dos datasets utilizados e gerados por este notebook
https://drive.google.com/drive/folders/1ZvH_MjFpXiVSVAV-RT_TxpaY5T9pFnWu?usp=sharing

Este notebook realiza algumas transformações e limpezas dos datasets obtidos do Ministério do Trabalho e Previdência.

Ao fim dos processos, pode-se obter subconjuntos de dados mais limpos, podendo fazer a junção por colunas com totais anuais, filtrar as categorias de interesse, bem como gerar subsets por seleção de termos específicos em determinadas linhas.

Devido ao modelo dos datasets disponibilizados pelo referido órgão, os processos abaixo só se aplicam aos dados de 2017 em diante. Dados anteriores a 2017 estão disponíveis no site acima em formato pdf.