# 🛒 ComparaAI

<div align="center">

### Encontre a melhor compra, não apenas o menor preço.

Compare preços, reputação, avaliações e confiança das lojas em um único lugar.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)
![Python](https://img.shields.io/badge/python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![License](https://img.shields.io/badge/license-MIT-purple)

</div>

---

# 📖 Sobre o Projeto

O **ComparaAI** é uma plataforma inteligente que ajuda consumidores a tomarem decisões de compra mais seguras.

Ao invés de mostrar apenas o menor preço, o sistema analisa:

- 💰 Preço do produto
- ⭐ Avaliações dos compradores
- 🛒 Quantidade de vendas
- 🏪 Reputação da loja
- 📈 Histórico de preços
- 🤖 Análise inteligente das avaliações

Nosso objetivo é responder uma pergunta simples:

> **"Qual é a melhor compra?"**

---

# ✨ Funcionalidades

## Versão 1.0

- [x] Pesquisa de produtos
- [x] Comparação de preços
- [x] Ranking de lojas
- [x] Score de confiança
- [x] Interface moderna

## Versão 2.0

- [ ] Histórico de preços
- [ ] Cadastro de usuários
- [ ] Favoritos
- [ ] Alertas de queda de preço

## Versão 3.0

- [ ] IA para resumir avaliações
- [ ] IA para detectar avaliações suspeitas
- [ ] IA para recomendar a melhor compra

## Versão 4.0

- [ ] Extensão para Google Chrome
- [ ] Aplicativo Android
- [ ] Aplicativo iOS

---

# 🚀 Tecnologias

## Backend

- Python
- FastAPI
- SQLAlchemy
- PostgreSQL

## Frontend

- HTML5
- CSS3
- JavaScript

## Inteligência Artificial

- OpenAI API
- Processamento de linguagem natural
- Sistema de Score Inteligente

---

# 📂 Estrutura do Projeto

```text
comparaai/

├── backend/
│
├── frontend/
│
├── database/
│
├── static/
│
├── templates/
│
├── requirements.txt
│
└── README.md
```

---

# 🎯 Como Funciona

O usuário pesquisa um produto:

```text
iPhone 15 128GB
```

O sistema coleta informações de diferentes lojas e gera um ranking:

| Loja | Preço | Avaliação | Vendas | Score |
|--------|--------|--------|--------|--------|
| Amazon | R$ 4.499 | 4.8 | 12.000 | 96 |
| Mercado Livre | R$ 4.350 | 4.6 | 8.000 | 91 |
| Magazine Luiza | R$ 4.590 | 4.9 | 6.500 | 94 |

Resultado:

```text
🏆 Melhor Compra

Amazon

Preço competitivo
Ótimas avaliações
Alta confiança
```

---

# 🧠 Sistema de Score

O ComparaAI utiliza um algoritmo próprio para calcular a qualidade da compra.

Exemplo:

```text
Preço .............. 30%
Avaliações ......... 40%
Quantidade de vendas 20%
Reputação .......... 10%
```

Resultado:

```text
Score Final = 96/100
```

---

# 🔮 Roadmap

### Curto Prazo

- Comparação de produtos
- Ranking de lojas
- Melhorias de desempenho

### Médio Prazo

- Histórico de preços
- Alertas automáticos
- Cadastro de usuários

### Longo Prazo

- IA própria
- Aplicativo mobile
- Extensão para navegador
- Marketplace de recomendações

---

# 💡 Diferencial

Enquanto outros comparadores mostram:

```text
Menor preço
```

O ComparaAI mostra:

```text
Melhor compra
```

Levando em consideração confiança, reputação e experiência real dos consumidores.

---

# 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/comparaai.git
```

Entre na pasta:

```bash
cd comparaai
```

Crie um ambiente virtual:

```bash
python -m venv venv
```

Ative o ambiente:

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o projeto:

```bash
uvicorn main:app --reload
```

Abra:

```text
http://localhost:8000
```

---

# 🤝 Contribuindo

Contribuições são sempre bem-vindas.

1. Faça um Fork
2. Crie uma Branch

```bash
git checkout -b minha-feature
```

3. Commit

```bash
git commit -m "Nova funcionalidade"
```

4. Push

```bash
git push origin minha-feature
```

5. Abra um Pull Request

---

# 📄 Licença

Este projeto está licenciado sob a Licença MIT.

---

# 👨‍💻 Autor

**Max**

Criando ferramentas inteligentes para ajudar pessoas a tomarem decisões melhores.

---

<div align="center">

### ⭐ Se gostou do projeto, deixe uma estrela no repositório!

**ComparaAI — A melhor compra começa com a melhor informação.**

</div>
