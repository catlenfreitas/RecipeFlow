# Gerenciador de Receitas Culinárias

Aplicativo Android desenvolvido em Java no Android Studio com integração ao Firebase Realtime Database.

O sistema permite cadastrar, visualizar, editar, excluir e filtrar receitas culinárias de forma simples e prática.

---

# 📌 Funcionalidades

✅ Cadastro de receitas  
✅ Listagem de receitas  
✅ Edição de receitas  
✅ Exclusão de receitas  
✅ Filtro por categoria  
✅ Validação de campos obrigatórios  
✅ Persistência de dados com Firebase  
✅ Atualização em tempo real  

---

# 📱 Tecnologias Utilizadas

- Java
- Android Studio
- Firebase Realtime Database
- XML
- ListView
- Spinner
- Firebase SDK

---

# 🧩 Campos da Receita

Cada receita possui:

- Nome da receita
- Categoria
- Tempo de preparo
- Ingredientes principais
- Nível de dificuldade
- Receita favorita

---

# 🔥 Firebase

Os dados são armazenados no Firebase Realtime Database.

O aplicativo realiza operações de:

- Create (Cadastrar)
- Read (Listar)
- Update (Editar)
- Delete (Excluir)

Os dados permanecem salvos mesmo após fechar o aplicativo.

---

# 📂 Estrutura do Projeto

## MainActivity.java
Responsável por:
- interface do usuário;
- validações;
- CRUD;
- integração com Firebase.

## Receita.java
Classe modelo da receita contendo:
- atributos;
- construtores;
- getters e setters.

## activity_main.xml
Arquivo responsável pelo layout da aplicação.

---

# ▶️ Como Executar

1. Clone o repositório:
```bash
git clone LINK_DO_REPOSITORIO
