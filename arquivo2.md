# Projeto: Organizador de Estudos 

Um projeto fictício para praticar a escrita de documentação com
Markdown.

> **Objetivo:** organizar tarefas acadêmicas, acompanhar prazos e
> registrar o andamento dos estudos.

## Visão geral

O Organizador de Estudos permite cadastrar disciplinas e tarefas. Cada
tarefa possui descrição, data de entrega e situação.

### Funcionalidades previstas

-   Cadastro de disciplinas;
-   Registro de tarefas;
-   Definição de datas de entrega;
-   Acompanhamento das tarefas concluídas;
-   Consulta das atividades pendentes.

## Estrutura do projeto

``` text
organizador-estudos/
├── dados/
│   └── tarefas.json
├── docs/
│   └── exemplos.md
├── src/
│   ├── main.py
│   └── tarefas.py
└── testes/
    └── test_tarefas.py
```

## Exemplo de tarefa

  Campo        Valor
  ------------ -----------------------------------
  Disciplina   Engenharia de Software
  Atividade    Elaborar diagrama de casos de uso
  Entrega      30/11/2026
  Situação     Em andamento

Registro equivalente em Python:

``` python
tarefa = {
    "disciplina": "Engenharia de Software",
    "atividade": "Elaborar diagrama de casos de uso",
    "entrega": "30/11/2026",
    "concluida": False
}

print(tarefa["atividade"])
```

## Como executar

1.  Instale o Python 3.
2.  Clone ou baixe o projeto.
3.  Acesse a pasta do projeto.
4.  Execute:

``` bash
python src/main.py
```

## Tecnologias utilizadas

-   **Linguagem:** Python
-   **Formato de dados:** JSON
-   **Controle de versão:** Git
-   **Hospedagem:** GitHub

## Como contribuir

1.  Crie uma branch para sua funcionalidade.
2.  Faça as modificações necessárias.
3.  Registre as alterações com um commit.
4.  Envie a branch ao repositório remoto.
5.  Abra um Pull Request para revisão.

## Licença

Este projeto é fictício e foi criado exclusivamente para fins didáticos.

------------------------------------------------------------------------

**Observação:** este documento é um exemplo de conteúdo em Markdown.
Posteriormente, os mesmos recursos poderão ser usados para construir um
`README.md` de apresentação de um projeto.
