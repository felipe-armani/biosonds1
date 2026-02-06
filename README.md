# Projeto Biosonds1 🚀

Este é um projeto de estudo focado em **Docker** e **Git**.

## 🛠️ Tecnologias utilizadas:
- **Nginx**: Servidor web para hospedar o index.html.
- **Docker**: Para isolamento e portabilidade da aplicação.
- **Git/GitHub**: Para controle de versão e deploy.

## 📦 Como rodar este projeto:
1. Faça o build da imagem:
   `docker build -t biosonds1-img .`
2. Rode o container:
   `docker run -d -p 8081:80 --name biosonds1-app biosonds1-img`
