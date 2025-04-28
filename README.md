# Sistema de Gerenciamento Simples (SGP)

O **SGP** é um sistema de gerenciamento simples desenvolvido com **Django** e uma interface administrativa aprimorada com **Jazzmin**. Ele oferece uma solução prática e eficiente para gerenciar dados, com recursos adicionais como filtros personalizados e exportação de produtos para Excel.

---

## 🚀 Status do Projeto
- **Situação**: Desenvolvido
- **Última Atualização**: Abril de 2025

---

## 🛠️ Tecnologias Utilizadas
- **Django** 5.0
- **Django Jazzmin** 3.0.0

---

## 📋 Funcionalidades
- **Interface Administrativa Personalizada**:
  - Utiliza o **Jazzmin** para uma experiência de administração moderna e intuitiva.
- **Filtros Avançados**:
  - Filtre dados facilmente dentro do sistema.
- **Exportação para Excel**:
  - Exporte produtos ou dados selecionados diretamente para arquivos Excel.

---

## 🎨 Aparência do Projeto
Abaixo está uma prévia visual da interface final:
![Design sem nome(1)](https://github.com/user-attachments/assets/be207a3c-3ecd-42b2-b5e8-1b38b1d27134)

---

## 📂 Estrutura do Projeto
A estrutura principal do projeto segue o padrão Django e inclui:
```
SGP/
├── core/                  # Configuração e funcionalidades centrais do projeto
├── products/              # Módulo para gerenciamento de produtos
├── static/                # Arquivos estáticos (CSS, JS, imagens)
├── templates/             # Templates HTML
├── venv/                  # Ambiente virtual para dependências do projeto
├── manage.py              # Script de gerenciamento do Django
├── requirements.txt       # Dependências de produção
├── requirements_dev.txt   # Dependências de desenvolvimento
└── db.sqlite3             # Banco de dados SQLite
```

---

## 🧩 Como Usar

### 1. **Clone este repositório**
```bash
git clone https://github.com/LoboProgrammingg/SGP.git
cd SGP
```

### 2. **Crie e ative um ambiente virtual**
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. **Instale as dependências**
```bash
pip install -r requirements.txt
```

### 4. **Realize as migrações do banco de dados**
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. **Inicie o servidor**
```bash
python manage.py runserver
```
Acesse o sistema no navegador em: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

---

## 📜 Próximos Passos
- [ ] Adicionar relatórios detalhados em PDF para exportação.
- [ ] Melhorar a responsividade da interface administrativa.
- [ ] Implementar notificações para eventos importantes, como atualizações de produto.

---

## 👨‍💻 Contribuindo
Contribuições são bem-vindas! Siga as etapas abaixo:
1. Faça um fork do projeto.
2. Crie uma branch para suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça suas alterações e um commit:
   ```bash
   git commit -m "Minha nova feature"
   ```
4. Envie suas alterações para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

Criado por **Matheus Lobo Camara**.
