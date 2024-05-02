
Task Orchestrator

This is a project for a task orchestration service, developed as part of an academic assignment for the Operating Systems course.

Main Features:

    Execution of user tasks, either individually or in pipelines.
    Task scheduling and execution by the server.
    Output redirection to corresponding files.
    Querying of tasks in progress and already completed.

Project Structure:

    src/: Contains the project's source code.
    include/: Contains the project's header files.
    obj/: Stores the object files (binary) generated during compilation.
    bin/: Contains the executables generated after compilation.
    scripts/: Contains a basic testing script.
    progs-TP23_24/: Contains void and hello test programs.
    Makefile: Script file for compiling and building the project.

How to Run:

    In the main directory:
    $ make

    In the bin directory:
    $./orchestrator <outputPath> <num_parallel_tasks>
    $./client execute <time> <flag> "program program_args..."

Additional Configurations:

    $./client help: command to display a help message to the client

Author:
Diogo José Fernandes Esteves


