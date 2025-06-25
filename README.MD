# Task Manager - Aplicação Web Flask
Aplicação web simples para gerenciamento de tarefas, com autenticação de usuários, criação, listagem, edição e exclusão de tarefas.

---
## Tecnologias usadas
- Python 3.11.0
- Flask
- Flask-SQLAlchemy
- Bootstrap 
- SQLite (banco local para desenvolvimento)
---
## Funcionalidades
- Cadastro e login de usuários
- CRUD completo de tarefas (Criar, Ler, Atualizar, Deletar)
- Interface moderna e responsiva
---
## Como rodar localmente
1. Clone o repositório:
- git clone https://github.com/seuusuario/task-manager.git
- cd task-manager
---
2. Crie um ambiente virtual e ative:
- Windows -> python -m venv venv
- Linux / macOS -> source venv/bin/activate
---

3. Instale as dependências:
- pip install -r requirements.txt
---
4. Rode a aplicação:
- python app.py
---
5. Acesse no navegador:
- http://localhost:5000
---
## Deploy Online
O projeto pode ser facilmente implantado em serviços como Render.com ou Railway.app. Configure o build com:
- pip install -r requirements.txt

**E o start com:**
- gunicorn app:app
---
## Melhorias futuras
- Implementar marcação de tarefas como concluídas
- Filtros de visualização
- Página de perfil do usuário
- Testes automatizados
- Migração para banco de dados mais robusto
---
## Autor
Leonardo Szervinski
---
## Contato
LinkedIn: linkedin.com/in/leonardoszervinski