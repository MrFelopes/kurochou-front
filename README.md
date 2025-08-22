[🇺🇸 English Version](README.en.md)

# Kurochou WebApp
## ❓ O que é?
kurochou.me é um pequeno projeto sendo desenvolvido por dois bons amigos com paixão por desenvolvimento, buscando nos desafiar e aprimorar. A intenção é ser um site simples, em que as pessoas possam acessar e assistir clipes das nossas jogatinas e risadas diárias.


---

## 🚀 Funcionalidades

- Login com autenticação por usuário e senha;
- Geração de token JWT;
- Layout responsivo com **TailwindCSS**;
- Comunicação com **API .NET** ([Repositório kurochou-api](https://github.com/meirochun/kurochou-api));
- Upload e visualização de vídeos (to-do);

---

## 🛠 Tecnologias

- **Frontend:** Next.js, TailwindCSS
- **Backend:** .NET 8, Dapper
- **Autenticação:** JWT
- **Banco de dados:** PostgreSQL

---

## ⚡ Pré-requisitos

- Node.js >= 18
- npm ou yarn

---

## 💻 Como rodar o projeto

### Frontend (Next.js)
```bash
git clone git@github.com:MrFelopes/kurochou-front.git
cd kurochou-front
npm install
npm run dev
```

### Sobre o banco de dados
Apesar do código do projeto estar disponível para todos, o acesso do banco de dados é restrito a mim e ao [Meiro](https://github.com/meirochun). Caso deseje testar o projeto, recomendo que faça um banco localmente. Alternativamente, também recomendo a plataforma [supabase](https://supabase.com) para a criação online de bancos de dados PostgreSQL.