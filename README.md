# 🚗 Carros — Sistema de Gestão de Veículos em Django

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Django](https://img.shields.io/badge/Django-Framework-green)
![Status](https://img.shields.io/badge/Status-em%20desenvolvimento-purple)

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
✔ Estrutura separada por responsabilidades, seguindo as boas práticas  

---

## 🛠️ Tecnologias utilizadas

- Python 3  
- Django  
- HTML  
- CSS  
- SQLite / PostgreSQL 
- Git & GitHub  

---

## 📁 Estrutura do Projeto

```bash
carros/
├── accounts/     # Autenticação de usuários
├── cars/         # Gestão de veículos
├── app/          # Configurações do projeto Django
├── templates/    # Templates globais
├── static/       # Arquivos estáticos (CSS, JS, imagens)
├── manage.py
└── requirements.txt
 ```
---

## Como rodar o projeto localmente:

### Pré-requisitos:
- Python 3.x
- Git
- Virtualenv (opcional, mas recomendado)

---

## Passo a passo:

## 1. Dentro do seu terminal, clone o repositório:

```bash
git clone https://github.com/bia-codes/carros.git
```

## 2. Entre na pasta criada:
```
cd carros
```

## 3. Crie e ative o ambiente virtual:

### Criação
```
python -m venv venv
```
### Ativação
   #### 3.1 No Windows:
   ```
   venv\Scripts\activate
   ```
   
   #### 3.2 No Linux/Mac:
   ```
   source venv/bin/activate
   ```

## 4. Instale as dependências:

```pip install -r requirements.txt```

## 5. Aplique as migrações:

```python manage.py migrate```

## 5. Crie um superusuário:

```python manage.py createsuperuser```

## 6. Inicie o servidor:

```python manage.py runserver```

## 7. Acesse no navegador:

   🔗 http://127.0.0.1:8000/

---

## 💡 Próximos passos
- Melhorar a interface frontend do projeto

## 📕 Aprendizados
Esse projeto me ajudou a fortalecer meus conhecimentos em Python, Django, lógica de programação, modelagem de dados e integração com banco de dados.

## 🤝 Contribuições / Sugestões
Contribuições e sugestões são bem vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📌 Contato
GitHub: https://github.com/bia-codes  
LinkedIn: www.linkedin.com/in/bianca-de-souza-lima-078007263  
Em busca de oportunidade na área de desenvolvimento backend com Python e Django. 
