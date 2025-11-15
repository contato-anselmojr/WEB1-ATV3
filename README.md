# WEB1-ATV3

🌱 Atividade 3 – ONG Esperança (JavaScript)

Esta é a Atividade 3, continuação do projeto da ONG Esperança das atividades 1 e 2.
Nesta parte eu usei JavaScript para deixar o site mais dinâmico e interativo.

🎯 Objetivo

Transformar o site estático da Atividade 2 em uma aplicação web mais real, usando:
Manipulação do DOM;
Eventos (cliques e envio de formulário);
Sistema simples de SPA (Single Page Application);
Validação de formulário com avisos para o usuário;
Armazenamento local (localStorage).

🧩 O que foi feito com JavaScript

Criei uma pasta js com arquivos separados por funcionalidade:
templates.js → sistema simples de templates em JS (gera HTML de alertas/mensagens);
storage.js → módulo que salva cadastros no localStorage (simula um “banco de dados” local);
form-validation.js → faz a verificação de consistência dos dados do formulário e mostra mensagens de erro ou sucesso;
spa.js → implementa uma SPA básica, carregando o conteúdo das páginas dentro da tag <main> sem recarregar o site todo.

✅ Funcionalidades implementadas

Verificação se os campos do formulário foram preenchidos corretamente (nome, e-mail, CPF, telefone, CEP, cidade e estado);
Exibição de mensagens de erro quando algum dado está incorreto;
Exibição de mensagem de sucesso quando o formulário está válido;
Salvamento dos dados do voluntário no localStorage;
Navegação entre Início, Projetos e Cadastro funcionando como uma SPA simples (sem recarregar a página inteira).

🧠 O que aprendi

Com essa atividade, eu aprendi a:
Manipular o DOM com querySelector, innerHTML e eventos;
Fazer validação mais completa de formulários usando JavaScript;
Mostrar mensagens de erro e sucesso de forma amigável para o usuário;
Usar localStorage para guardar informações localmente;
Separar o JavaScript em módulos por funcionalidade, deixando o código mais organizado.

✨ Autor

Desenvolvido por Anselmo Junior e Luiz Felix da Silva Filho
Curso: Análise e Desenvolvimento de Sistemas
Disciplina: Desenvolvimento Web – Atividade 3
