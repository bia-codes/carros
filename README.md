# 🚗 Carros — Sistema de Gestão de Veículos em Django

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-Framework-green)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

Projeto web para **gestão de veículos**, desenvolvido em **Python + Django**.  
Permite o gerenciamento completo de carros, com sistema de autenticação, cadastro de usuários e controle de dados.

📚 Projeto baseado no curso **Django Master**, com adaptações e melhorias próprias.

---

## 📌 Funcionalidades

✔ Cadastro de usuários  
✔ Login e logout  
✔ Sistema de autenticação  
✔ CRUD completo de carros  
✔ Organização em apps (`accounts`, `cars`)  
✔ Painel administrativo via Django Admin  
✔ Estrutura separada por responsabilidades seguindo boas práticas  

---

## 🛠️ Tecnologias utilizadas

- Python 3  
- Django  
- HTML  
- CSS  
- SQLite / PostgreSQL 
- Git & GitHub  

---

## 📂 Estrutura do Projeto
carros/
├── accounts/        # Autenticação de usuários
├── cars/            # App principal (gestão de veículos)
├── app/             # Configurações do projeto Django
├── templates/       # Templates globais
├── static/          # Arquivos estáticos
├── manage.py
└── requirements.txt
 
---

## Como rodar o projeto localmente

### Pré-requisitos:
- Python 3.x
- Git
- Virtualenv (opcional, mas recomendado)

---

### Passo a passo:

Clone o repositório:

```bash
git clone https://github.com/bia-codes/carros.git
cd carros
```

Crie e ative o ambiente virtual:
```
python -m venv venv
```
# Windows:
```venv\Scripts\activate```

# Linux/Mac:
```source venv/bin/activate```

Instale as dependências:

```pip install -r requirements.txt```

Aplique as migrações:

```python manage.py migrate```

Crie um superusuário:

```python manage.py createsuperuser```

Inicie o servidor:

```python manage.py runserver```

Acesse no navegador:

🔗 http://127.0.0.1:8000/
