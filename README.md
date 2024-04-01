# Avalia Muriaé

**Automatização de criação de formulários para lançamento de avaliações diagnósticas pela Secretaria Municipal de Educação de Muriaé.**

## Visão Geral

O projeto Avalia Muriaé é uma solução paliativa para facilitar o lançamento de alunos nas avaliações diagnósticas pela Secretaria Municipal de Educação de Muriaé. Embora não tenhamos um aplicativo com banco de dados dedicado, esta solução simplifica o processo ao criar formulários para cada sala de aula, minimizando a necessidade de digitação manual. Atualmente, o processo envolve baixar a base de dados do site SISLAME e realizar uma curadoria desses dados.

## Instalação

Para utilizar este projeto, são necessárias as seguintes ferramentas:

- Jupyter Notebook
- Python
- Anaconda

## Uso

O projeto consiste em duas fases:
1. **Criação de formulários:** Esta etapa é realizada antes dos professores lançarem os alunos. Utilizamos o Google App Script para automatizar a criação de formulários para cada sala de aula.
2. **Consolidação de dados:** Após os professores lançarem os alunos nos formulários, os dados são consolidados e posteriormente lançados no Power BI para análise.

## Fase 1

Nesta fase a gente precisa criar um documento que seja possível nós automatizarmos a criação de formulário para que possamos criar formulários baseados em Google App Script.

1. Primeiro passo é baixar a planilha: ALUNOS DADOS CADASTRAIS do SISLAME: https://sislamemg.caedufjf.net/sislamemg/inicio.faces#
2. Esta planilha se encontra em: BI > Relatórios > Alunos > Dados Cadastrais Alunos
3. A planilha tem normalmente uma estrutura fixa (caso o Sislame não mude é claro)
4. Remova as linhas em branco desta planilha e deixe os nomes das colunas na primeira linha
5. Se você tiver limpado direitinho você poderá rodar este script: 1. SISLAME PARA FORMULÁRIO/Script - Tabela do Sislame para Forms.ipynb
6. O resultado do script irá criará planilhas separadas por turmas, cada turma terá o seu formulário
7. 

## Contribuição

Se você estiver interessado em contribuir com o projeto, especialmente na criação de um front end ou em qualquer outra área que facilite o lançamento de turmas pelos professores, sua ajuda será muito bem-vinda. 😊

## Contato

- Email: guilherme@edu.muriae.mg.gov.br
- Instagram: [@oguisaito](https://www.instagram.com/oguisaito)

Sinta-se à vontade para entrar em contato se tiver dúvidas, sugestões ou se quiser colaborar de alguma forma. 🚀
