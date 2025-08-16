📚 Desafio: LiterAlura – Alura  

💻✨ Karolina Anjos – Dev Java  

✅ Projeto Finalizado  
Este projeto foi desenvolvido como parte da formação Back-End Java com Orientação a Objetos (GB/ONE) pela Alura.  
O LiterAlura permite buscar títulos de livros via API da [Gutendex](https://gutendex.com/) e armazenar informações no banco de dados PostgreSQL.  

---

🌐 API Utilizada  
Gutendex: API gratuita para busca de livros e autores.  
✅ Sem autenticação | Dados atualizados | Fácil integração  

---

📚 Tecnologias e Conceitos Aplicados  
☕ Java 24  
🌐 Spring Boot 3.5.0  
🗄 PostgreSQL  
🔄 Spring Data JPA  
📦 Jackson Databind  
🧩 Organização por camadas (Controller, Service, Model, Repository)  
🧼 Código limpo e modular  

---

├── application
│ └── LiteraluraApplication.java # Interface principal
├── controller
│ └── LivroController.java # Controle das requisições
├── service
│ └── LivroService.java # Lógica de negócio e comunicação com API
├── model
│ ├── Livro.java
│ └── Autor.java # Registro dos dados do JSON da API
├── repository
│ └── LivroRepository.java # Comunicação com banco de dados
├── resources
│ └── application.properties # Configurações do Spring Boot e DB
└── README.md

📦 Estrutura do Projeto  

---

🧮 Funcionalidades  
🔄 Pesquisar títulos de livros  
💬 Exibir caminhos registrados no banco de dados  
📚 Listar autores  
📅 Buscar autores por ano  
🌍 Buscar livros por idioma (en, es, fr, pt)  

---

▶️ Como Executar  
1. Clone o repositório:  
```bash
git clone https://github.com/Karolinanjos/literalura.git
cd literalura
```

1 - Configure o banco PostgreSQL (literalura), usuário (literalura_user) e senha (senha123).

2 - Execute o projeto via IntelliJ ou terminal:
./mvnw spring-boot:run

3 - Acesse a API: http://localhost:8080

4 - Acesse o Swagger UI: http://localhost:8080/swagger-ui.html

---

🔧 Requisitos
☑️ JDK 24 ou superior
☑️ PostgreSQL
☑️ Internet para comunicação com a API Gutendex

---

📢 Agradecimento
Agradeço à Alura pela trilha de aprendizado, prática e inspiração para este projeto. 💚

---

🤝 Contribuindo
Quer colaborar?

Faça um fork 🍴

Crie uma branch: git checkout -b minha-feature

Faça suas alterações

Envie um pull request explicando a melhoria

📫 Contato
🐙 GitHub: Karolinanjos
🔗 LinkedIn: Karolina Anjos

📄 Licença
Este projeto é de uso educacional e não comercial.
