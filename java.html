<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplicativo Dinâmico com JavaScript</title>
    <style>
        /* CSS para estilizar a interface */
        * { box-sizing: border-box; font-family: Arial, sans-serif; margin: 0; padding: 0; }
        body { background-color: #f4f7f6; display: flex; justify-content: center; align-items: center; min-height: 100vh; }
        .app-container { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); width: 100%; max-width: 450px; }
        h1 { color: #333; margin-bottom: 20px; font-size: 24px; text-align: center; }
        .input-group { display: flex; gap: 10px; margin-bottom: 20px; }
        input { flex: 1; padding: 12px; border: 2px solid #ddd; border-radius: 6px; font-size: 16px; outline: none; }
        input:focus { border-color: #007bff; }
        button { background: #007bff; color: white; border: none; padding: 12px 20px; border-radius: 6px; cursor: pointer; font-size: 16px; font-weight: bold; }
        button:hover { background: #0056b3; }
        ul { list-style: none; }
        li { display: flex; justify-content: space-between; align-items: center; padding: 12px; background: #f9f9f9; border-bottom: 1px solid #eee; border-radius: 6px; margin-bottom: 8px; transition: 0.2s; }
        li.completed { background: #d4edda; text-decoration: line-through; color: #155724; }
        .actions { display: flex; gap: 5px; }
        .btn-done { background: #28a745; padding: 6px 10px; font-size: 12px; }
        .btn-done:hover { background: #218838; }
        .btn-delete { background: #dc3545; padding: 6px 10px; font-size: 12px; }
        .btn-delete:hover { background: #c82333; }
    </style>
</head>
<body>

    <div class="app-container">
        <h1>Minhas Tarefas</h1>
        
        <!-- Formulário de Entrada -->
        <div class="input-group">
            <input type="text" id="taskInput" placeholder="Digite uma nova tarefa...">
            <button id="addBtn">Adicionar</button>
        </div>

        <!-- Lista que será populada pelo JavaScript -->
        <ul id="taskList"></ul>
    </div>

    <!-- O SCRIPT JAVASCRIPT COMEÇA AQUI -->
    <script>
        // 1. Mapeamento dos elementos da tela (DOM)
        const taskInput = document.getElementById('taskInput');
        const addBtn = document.getElementById('addBtn');
        const taskList = document.getElementById('taskList');

        // 2. Função para criar e adicionar uma nova tarefa na tela
        function addTask() {
            const taskText = taskInput.value.trim();

            // Validação simples para não aceitar texto vazio
            if (taskText === "") {
                alert("Por favor, digite alguma tarefa!");
                return;
            }

            // Criando o elemento da lista (<li>)
            const li = document.createElement('li');
            
            // Criando o texto da tarefa
            const textSpan = document.createElement('span');
            textSpan.textContent = taskText;
            li.appendChild(textSpan);

            // Criando o container dos botões de ação
            const actionsDiv = document.createElement('div');
            actionsDiv.className = 'actions';

            // Botão "Concluir"
            const doneBtn = document.createElement('button');
            doneBtn.textContent = '✓';
            doneBtn.className = 'btn-done';
            doneBtn.onclick = function() {
                li.classList.toggle('completed');
            };

            // Botão "Excluir"
            const deleteBtn = document.createElement('button');
            deleteBtn.textContent = 'X';
            deleteBtn.className = 'btn-delete';
            deleteBtn.onclick = function() {
                taskList.removeChild(li);
            };

            // Juntando as peças dentro do elemento da lista
            actionsDiv.appendChild(doneBtn);
            actionsDiv.appendChild(deleteBtn);
            li.appendChild(actionsDiv);

            // Adicionando a nova tarefa à nossa lista principal
            taskList.appendChild(li);

            // Limpa o campo de texto e volta o foco do teclado para ele
            taskInput.value = "";
            taskInput.focus();
        }

        // 3. Evento de clique no botão Adicionar
        addBtn.addEventListener('click', addTask);

        // 4. Evento para permitir adicionar a tarefa apertando "Enter" no teclado
        taskInput.addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                addTask();
            }
        });
    </script>
</body>
</html>
