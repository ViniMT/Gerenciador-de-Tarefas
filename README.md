Sistema de Gerenciamento de Tarefas com Prioridade e Persistência de Dados

Este projeto é um sistema simples de gerenciamento de tarefas, desenvolvido em Python, que permite ao usuário adicionar, remover, listar e marcar tarefas como completas. O sistema também suporta a definição de prioridade para cada tarefa e persiste os dados em um arquivo JSON para que possam ser carregados posteriormente.

Funcionalidades:
Adicionar Tarefa: Permite adicionar uma nova tarefa com uma descrição e prioridade (Baixa, Média, Alta).
Remover Tarefa: Permite remover uma tarefa existente pelo nome.
Marcar Tarefa como Completa: Permite marcar uma tarefa existente como completa.
Listar Tarefas: Lista todas as tarefas ordenadas pela prioridade.
Salvar Dados: Salva todas as tarefas em um arquivo JSON.
Carregar Dados: Carrega as tarefas de um arquivo JSON.
Estrutura do Projeto
O projeto é composto por um único arquivo Python:

main.py: Contém todo o código do sistema de gerenciamento de tarefas.

Uso:
Clonar o Repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

Executar o Sistema:
Para executar o sistema, basta rodar o arquivo main.py:
python main.py

Menu de Opções:
Após executar o script, você verá um menu com as seguintes opções:

Adicionar tarefa: Adicione uma nova tarefa fornecendo a descrição e a prioridade.
Remover tarefa: Remova uma tarefa existente fornecendo a descrição da tarefa.
Marcar tarefa como completa: Marque uma tarefa como completa fornecendo a descrição da tarefa.
Listar tarefas: Lista todas as tarefas, ordenadas por prioridade.
Salvar dados: Salva as tarefas em um arquivo JSON chamado tarefas.json.
Carregar dados: Carrega as tarefas do arquivo JSON tarefas.json.
Sair: Encerra o programa.
Exemplo de Uso
Aqui está um exemplo de como utilizar o sistema:

Adicione uma nova tarefa:
Descrição da tarefa: Estudar Python
Prioridade (Baixa, Média, Alta): Alta

Liste as tarefas:
Estudar Python [Alta] - Pendente

Marque a tarefa como completa:
Descrição da tarefa a marcar como completa: Estudar Python

Liste as tarefas novamente para ver a atualização:
Estudar Python [Alta] - Completa

Salve as tarefas:
Dados salvos com sucesso em tarefas.json

Carregue as tarefas ao iniciar o programa:
Dados carregados com sucesso de tarefas.json

Contribuição
Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

