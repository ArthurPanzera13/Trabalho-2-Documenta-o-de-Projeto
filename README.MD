# 📘 Documentação do Sistema LitNet

📄 **Documentação Oficial em PDF**  
A versão completa e final da documentação pode ser acessada no link abaixo:

➡️ [**Trabalho 2 - Documentação de Projeto (PDF)**](Trabalho%202%20-%20%20Documentação%20de%20Projeto.pdf)

Este repositório reúne todos os diagramas, modelos e artefatos utilizados para documentar o sistema **LitNet**, uma plataforma social para leitores que integra biblioteca pessoal, fórum de discussão, avaliações e marketplace.

---

# 📂 Estrutura de Diretórios

**Estrutura do projeto:**
``` 
Documentação-LitNet/
├── Casos de Uso/
│   ├── Código PLANT UML/
│   └── Imagens/
│       ├── UC-01 - Gerenciar Usuários.png
│       ├── UC-02 - Avaliar Livros.png
│       ├── UC-03 - Gerenciar Fórum de Discussão.png
│       ├── UC-04 - Gerenciar Livros.png
│       ├── UC-05 - Comprar e Vender Livros.png
│       └── UC-06 - Fluxo Geral do sistema.png
├── Diagrama de Sequência do Sistema/
│   ├── Código PLANT UML/
│   └── Imagens/
│       └── DS-01 - Diagrama de Sequência do Sistema.png
├── Modelo de Dados/
│   ├── Código PLANT UML/
│   └── Imagens/
│       └── Modelo de Dados.png
├── Modelos de Projeto/
│   ├── Arquitetura/
│   │   ├── Código PLANT UML/
│   │   └── Imagens/
│   │       └── Arquitetura do Sistema.png
│   ├── Diagrama de Classes/
│   │   ├── Código PLANT UML/
│   │   └── Imagens/
│   │       └── Diagrama de Classes.png
│   ├── Diagrama de Componentes/
│   │   ├── Código PLANT UML/
│   │   └── Imagens/
│   │       └── Diagrama de Componentes.png
│   ├── Diagrama de Comunicação/
│   │   ├── Código PLANT UML/
│   │   └── Imagens/
│   │       ├── DiagramaUC01.png
│   │       ├── DiagramaUC02.png
│   │       ├── DiagramaUC03.png
│   │       ├── DiagramaUC04.png
│   │       └── DiagramaUC05.png
│   └── Diagrama de Estados/
│       ├── Código PLANT UML/
│       └── Imagens/
│           └── Diagrama de Estados.png
└── README.md
```
Todas as imagens estão organizadas nas respectivas pastas.

---

# 👤 2.1 Atores do Sistema

A seguir estão os atores identificados no sistema LitNet, conforme definidos no documento oficial:

### **📘 Usuário (Ator Principal)**
Representa qualquer pessoa que utiliza a plataforma LitNet. Pode realizar ações como login, cadastrar livros na biblioteca, publicar tópicos, comentar, avaliar obras, criar anúncios e enviar propostas de compra.

### **🧑‍🏫 Moderador**  
Usuário com permissões administrativas restritas, responsável por acompanhar o fórum e executar ações de manutenção de conteúdo, como remover comentários ou tópicos inadequados. Garante a qualidade das interações dentro da comunidade.

### **📚 Leitor**  
Usuário cujo foco principal é a gestão da própria biblioteca: buscar livros, adicionar itens à estante, consultar detalhes, acompanhar progresso de leitura e registrar avaliações de obras.

### **🛒 Comprador**  
Usuário interessado em adquirir livros disponíveis no marketplace. Realiza ações como buscar anúncios, visualizar detalhes, enviar propostas e confirmar transações.

### **🏷️ Vendedor**  
Usuário que cria anúncios para venda de livros. Pode registrar novos itens, receber propostas, negociar valores e confirmar a conclusão da venda.

---

# 🔹 2.2 Modelo de Casos de Uso

### UC-01 – Gerenciar Usuários
![UC-01 - Gerenciar Usuários](Casos%20de%20Uso/Imagens/UC-01%20-%20Gerenciar%20Usu%C3%A1rios.png)

### UC-02 – Avaliar Livros
![UC-02 - Avaliar Livros](Casos%20de%20Uso/Imagens/UC-02%20-%20Avaliar%20Livros.png)

### UC-03 – Gerenciar Fórum de Discussão
![UC-03 - Gerenciar Fórum](Casos%20de%20Uso/Imagens/UC-03%20-%20Gerenciar%20Forúm%20de%20Discussão.png)

### UC-04 – Gerenciar Livros
![UC-04 - Gerenciar Livros](Casos%20de%20Uso/Imagens/UC-04%20-%20Gerenciar%20Livros.png)

### UC-05 – Comprar e Vender Livros
![UC-05 - Comprar e Vender Livros](Casos%20de%20Uso/Imagens/UC-05%20-%20Comprar%20e%20Vender%20Livros.png)

---

# 🔄 2.3 Diagrama de Sequência do Sistema

![DS-01](Diagrama%20de%20Sequ%C3%AAncia%20do%20Sistema/Imagens/DS-01%20-%20Diagrama%20de%20Sequ%C3%AAncia%20do%20Sistema.png)

---

# 🧩 3. Modelos de Projeto

## 3.1 Arquitetura
![Arquitetura](Modelos%20de%20Projeto/Arquitetura/Imagens/Arquitetura%20do%20Sistema.png)

---

## 3.2 Diagramas de Componentes e Implantação

### 🔌 Diagrama de Componentes
![Componentes](Modelos%20de%20Projeto/Diagrama%20de%20Componentes/Imagens/Diagrama%20de%20Componentes.png)

### 🚀 Diagrama de Implantação
![Implantação](Modelos%20de%20Projeto/Diagrama%20de%20Implantação/Imagens/Diagrama%20De%20Implantação.png)

---

## 3.3 Diagrama de Classes
![Classes](Modelos%20de%20Projeto/Diagrama%20de%20Classes/Imagens/Diagrama%20de%20Classes.png)

---

## 3.4 Diagramas de Sequência (por Caso de Uso)

### Diagrama de Sequência UC-01
![Seq UC01](Modelos%20de%20Projeto/Diagramas%20de%20Sequência/Imagens/DiagramaSequenciaUC01.png)

### Diagrama de Sequência UC-02
![Seq UC02](Modelos%20de%20Projeto/Diagramas%20de%20Sequência/Imagens/DiagramaSequenciaUC02.png)

### Diagrama de Sequência UC-03
![Seq UC03](Modelos%20de%20Projeto/Diagramas%20de%20Sequência/Imagens/DiagramaSequenciaUC03.png)

### Diagrama de Sequência UC-04
![Seq UC04](Modelos%20de%20Projeto/Diagramas%20de%20Sequência/Imagens/DiagramaSequenciaUC04.png)

### Diagrama de Sequência UC-05
![Seq UC05](Modelos%20de%20Projeto/Diagramas%20de%20Sequência/Imagens/DiagramaSequenciaUC05.png)

---

## 3.5 Diagramas de Comunicação

### Diagrama de Comunicação UC-01
![UC01](Modelos%20de%20Projeto/Diagrama%20de%20Comunicação/Imagens/DiagramaUC01.png)

### Diagrama de Comunicação UC-02
![UC02](Modelos%20de%20Projeto/Diagrama%20de%20Comunicação/Imagens/DiagramaUC02.png)

### Diagrama de Comunicação UC-03
![UC03](Modelos%20de%20Projeto/Diagrama%20de%20Comunicação/Imagens/DiagramaUC03.png)

### Diagrama de Comunicação UC-04
![UC04](Modelos%20de%20Projeto/Diagrama%20de%20Comunicação/Imagens/DiagramaUC04.png)

### Diagrama de Comunicação UC-05
![UC05](Modelos%20de%20Projeto/Diagrama%20de%20Comunicação/Imagens/DiagramaUC05.png)

---

## 3.6 Diagrama de Estados
![Diagrama de Estados](Modelos%20de%20Projeto/Diagrama%20de%20Estados/Imagens/Diagrama%20de%20Estados.png)

---

# 🗂️ 4. Modelo de Dados
![Modelo de Dados](Modelo%20de%20Dados/Imagens/Modelo%20de%20Dados.png)

---

# 🧑‍💻 Autor
**Arthur Lara Panzera**  
Disciplina: *Projeto de Software*  
Data: 15/11/2025

---

# ⭐ Licença
Documentação acadêmica — uso educativo e não comercial.