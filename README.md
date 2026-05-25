# README - AppLogin

````md id="u4tqzx"
# AppLogin 🔐

Aplicativo Android desenvolvido no Android Studio utilizando Java e SQLite para realizar cadastro e autenticação de usuários.

---

# 📱 Sobre o Projeto

O AppLogin é um sistema simples de LOGIN e SENHA desenvolvido para fins acadêmicos.  
O aplicativo permite:

✅ Cadastro de usuários  
✅ Armazenamento em banco SQLite  
✅ Autenticação de login  
✅ Navegação entre telas  
✅ Interface personalizada e moderna  

---

# 🛠 Tecnologias Utilizadas

- Java
- Android Studio
- SQLite
- XML
- ConstraintLayout / LinearLayout

---

# 📂 Estrutura do Projeto

## Classes Java

- MainActivity
- LoginActivity
- RegistrarActivity
- DBHelper

## Layouts XML

- activity_main.xml
- activity_login.xml
- activity_registrar.xml

---

# 🎨 Funcionalidades

## Tela Inicial

- Logo do aplicativo
- Botão Entrar
- Botão Cadastrar
- Interface personalizada

## Tela de Cadastro

- Cadastro de usuário
- Validação de senha
- Salvamento no banco SQLite

## Tela de Login

- Autenticação do usuário
- Verificação de login e senha
- Mensagens utilizando Toast

---

# 🗄 Banco de Dados

O aplicativo utiliza SQLite para armazenamento local dos usuários.

Tabela criada:

```sql
CREATE TABLE utilizador(
    username TEXT PRIMARY KEY,
    password TEXT
);
````

---

# ▶ Como Executar

1. Abrir o Android Studio
2. Selecionar Open Project
3. Abrir a pasta do projeto AppLogin
4. Executar no emulador ou celular físico

---

# 📸 Telas do Aplicativo

* Tela Inicial
* Tela de Cadastro
* Tela de Login

---

# 👨‍💻 Desenvolvedor

Projeto desenvolvido por Camille Ferreira
Curso Técnico de Informática

---

# 📚 Objetivo Acadêmico

Este projeto foi desenvolvido com o objetivo de praticar:

* Navegação entre Activities
* Manipulação de componentes gráficos
* Banco de dados SQLite
* Programação Java no Android
* Validação de formulários
* Interface gráfica mobile

---

```
```
