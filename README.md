# TipPark

Sistema de gestão de estacionamento desenvolvido para organizar e controlar vagas em tempo real.  

O **TipPark** permite que cada usuário cadastre seu veículo, visualize vagas livres/ocupadas e ocupe ou libere somente a vaga que ele mesmo utilizou.  

---

## Tecnologias utilizadas
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js  
- **Banco de Dados:** MySQL  

---

##  Funcionalidades Implementadas
- Cadastro de usuário e veículo  
- Organização e visualização de vagas livres e ocupadas  
- Ocupação de vaga (restrita a uma vaga por usuário)  
- Desocupação de vaga (somente a que o usuário ocupou)
  
---

## Como rodar o projeto localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuuser/tippark.git
   
2. Entre na pasta do backend:
   cd backend
   
3. Instale as dependências:
   npm install cors express mysql2 nodemon

4. Configure a conexão com o banco de dados MySQL:
   Verifique usuário e senha no SQL Workbench
   Ajuste no código caso necessário

5. Inicie o servidor:
   npm start

---

**Principais regras**
-Cada usuário pode ocupar apenas uma vaga por vez

-Usuário só pode desocupar a vaga que ocupou

---

**Status do projeto**
✅Finalizado
