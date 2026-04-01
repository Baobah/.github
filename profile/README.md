<div align="center">

# 🌳 BaObAH

**Bem-vindo à organização BaObAH no GitHub!**

*Uma plataforma moderna com frontend em Vue 3 e backend em Django REST Framework*

</div>

---

## 📖 Sobre o Projeto

O **BaObAH** é uma aplicação web full-stack desenvolvida para oferecer uma experiência moderna e eficiente. O projeto é composto por dois repositórios principais:

| Repositório | Tecnologia | Descrição |
|---|---|---|
| `baobah-frontend` | Vue 3 | Interface de usuário reativa e moderna |
| `baobah-backend` | Django + DRF | API RESTful robusta e escalável |

---

## 🚀 Stack Tecnológica

### 🖥️ Frontend — Vue 3

- **Framework:** [Vue.js 3](https://vuejs.org/) com Composition API
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Gerenciamento de Estado:** [Pinia](https://pinia.vuejs.org/)
- **Roteamento:** [Vue Router](https://router.vuejs.org/)
- **Requisições HTTP:** [Axios](https://axios-http.com/)

### ⚙️ Backend — Django + DRF

- **Framework:** [Django](https://www.djangoproject.com/)
- **API REST:** [Django REST Framework (DRF)](https://www.django-rest-framework.org/)
- **Autenticação:** JWT via [djangorestframework-simplejwt](https://django-rest-framework-simplejwt.readthedocs.io/)
- **Banco de Dados:** PostgreSQL
- **Documentação da API:** Swagger / OpenAPI

---

## 📁 Repositórios

### [`baobah-frontend`](https://github.com/Baobah/baobah-frontend)
Interface do usuário construída com Vue 3, proporcionando uma experiência ágil e responsiva.

```bash
# Instalar dependências
npm install

# Rodar em modo desenvolvimento
npm run dev

# Build para produção
npm run build
```

### [`baobah-backend`](https://github.com/Baobah/baobah-backend)
API RESTful desenvolvida com Django e Django REST Framework.

```bash
# Criar ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/macOS
# ou
venv\Scripts\activate     # Windows

# Instalar dependências
pip install -r requirements.txt

# Aplicar migrações
python manage.py migrate

# Rodar servidor de desenvolvimento
python manage.py runserver
```

---

## 🏗️ Arquitetura

```
BaObAH
├── baobah-frontend/    # Vue 3 SPA
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── stores/
│   │   └── router/
│   └── ...
│
└── baobah-backend/     # Django REST API
    ├── apps/
    ├── config/
    ├── requirements.txt
    └── manage.py
```

---

## 🤝 Como Contribuir

1. **Fork** o repositório desejado
2. Crie uma branch para sua feature: `git checkout -b feature/minha-feature`
3. Commit suas alterações: `git commit -m 'feat: adiciona minha feature'`
4. Push para a branch: `git push origin feature/minha-feature`
5. Abra um **Pull Request**

> Consulte o `CONTRIBUTING.md` de cada repositório para mais detalhes.

---

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

<div align="center">

Feito com ❤️ pela equipe **BaObAH**

</div>
