Orquestrador de Tarefas

Este é um projeto de um serviço de orquestração de tarefas, desenvolvido como parte de um trabalho académico para a UC de Sistemas Operativos.
Funcionalidades Principais:

    Execução de tarefas do utlizador, individualmente ou em pipelines.
    Escalonamento e execução de tarefas pelo servidor.
    Redirecionamento de saída para arquivos correspondentes.
    Consulta de tarefas em execução e já realizadas.

Estrutura do Projeto:

    src/: Contém o código-fonte do projeto.
    include/: Contém os ficheiros-cabeçalho do projeto
    obj/: Armazena os ficheiros objeto(binário) gerados durante a compilação.
    bin/: Contém os executáveis gerados após a compilação.
    scripts/: Contém um script básico para testes
    progs-TP23_24/: Contém programas de teste void e hello.
    Makefile: Ficheiro de script para compilar e construir o projeto.

Como Executar:

    Na diretoria principal: 
    $ make

    Na diretoria bin:
    $./orchestrator <outputPath> <num_parallel_tasks>
    $./client execute <time> <flag> "program program_args..."

Configurações Adicionais:

    $./client help: comando para mostrar uma mensagem de ajuda ao cliente

Autor:
Diogo José Fernandes Esteves


