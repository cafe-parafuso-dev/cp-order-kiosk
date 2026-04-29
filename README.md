# 🛒 Sistema de Carrinho de Compras — Café & Parafuso

> Parte do ecossistema **Café & Parafuso** · Desenvolvido por alunos do Curso Técnico em Informática

---

## 📌 Sobre o Projeto

O Sistema de Carrinho de Compras é a **interface de autoatendimento** do Café & Parafuso. Ele funciona de forma semelhante aos totens de pedido encontrados em redes de fast-food (como Burger King ou McDonald's): o próprio cliente navega pelo cardápio digital, escolhe seus produtos, monta seu pedido e finaliza o pagamento — tudo sem precisar de um atendente.
<br><br>
Este sistema é o **ponto de contato direto com o cliente final**. É por meio dele que a experiência de compra acontece.

**Este sistema se integra com:**
- [X] Sistema Principal (Café & Parafuso)
- [X] Sistema de Catálogo de Produtos
- [X] Sistema de Controle de Caixa

---

## 🚀 Escopo Funcional (Alto Nível)

- [ ] Exibição do Cardápio Digital
- [ ] Montagem do Pedido (Carrinho)
- [ ] Identificação do Cliente
- [ ] Finalização e Pagamento
- [ ] Envio do Pedido
- [ ] Painel de Chamadas

---

## 🛠️ Tecnologias

| Camada | Tecnologia | Versão Recomendada |
|---|---|---|
| Linguagem | Java | 17+ |
| Framework | Spring Boot | 4.0.6 |
| Template Engine | Thymeleaf | 3.1.5 |
| Banco de Dados | PostgreSQL | 15+ |
| ORM | Spring Data JPA / Hibernate | - |
| Build Tool | Maven | 3.9+ |
| FrontEnd | HTML5 + CSS3 + TailwindCSS 4 | - |
| Servidor | Tomcat Embedded (Spring Boot) | - |
| Controle de versão | Git + GitHub | - |

---

## 📁 Estrutura do Projeto

```
cp-order-kiosk/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── br/com/cafe-parafuso-dev/shop/
│   │   │       ├── controller/          ← Controladores (recebem requisições)
│   │   │       │   ├── web/             ← Controllers das páginas (Thymeleaf)
│   │   │       │   └── api/             ← Controllers da API REST
|   │   │       ├── service/             ← Regras de negócio (PedidoService, etc.)
|   │   │       ├── repository/          ← Acesso ao banco de dados
|   │   │       ├── model/               ← Entidades (Pedido, ItemPedido)
|   │   │       ├── dto/                 ← Objetos de transferência de dados
|   │   │       └── client/              ← Clientes HTTP para consumir APIs externas
|   |   └── resources/
│   │       ├── static/                  ← Arquivos estáticos (CSS, JS, imagens)
│   │       ├── templates/               ← Páginas Thymeleaf (HTML)
│   │       │   ├── cardapio.html          
│   │       │   ├── carrinho.html          
│   │       │   ├── pagamento.html
│   │       │   ├── confirmacao.html
│   │       │   └── painel.html 
│   │       └── application.properties   ← Configurações do sistema
│   └── test/
├── docs/
├── .gitignore
├── CONTRIBUTING.md
├── pom.xml                              ← Dependências do projeto (Maven)     
└── README.md
```

---

## ▶️ Como Executar

```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/cp-order-kiosk.git

# 2. Acesse a pasta
cd cp-order-kiosk

# 3. Execute o projeto
# (instruções específicas da equipe)
```

---

## 🤝 Como Contribuir

Leia o arquivo [CONTRIBUTING.md](./CONTRIBUTING.md) antes de qualquer alteração.

---

## 👥 Equipe

| Nome | Função |
|---|---|
| Álvaro Silva | Desenvolvedor |
| Davi Almeida | Desenvolvedor |
| Gabriel Campos | Desenvolvedor |
| Gustavo Andrade | Desenvolvedor |
| Pedro Marcelino | Desenvolvedor |
| Rhyan Vasconcelos | Desenvolvedor |

**Orientador:** Lenoln Muniz · [LinkedIn](https://linkedin.com/in/lenoln-io)

---

## 📄 Licença

Este projeto é de uso educacional, desenvolvido como projeto integrador do Curso Técnico em Informática.
