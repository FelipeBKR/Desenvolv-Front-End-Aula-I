# 🐾 ONG ResGatos - Exercício Prático III

Este diretório contém o **Exercício Prático III** da disciplina de Desenvolvimento Front-End. O projeto consiste em um website estático de três páginas para uma ONG fictícia chamada **"ONG ResGatos"**, focada no resgate e cuidado de felinos abandonados.

O objetivo principal deste exercício é aplicar e demonstrar conhecimentos básicos de **HTML5** para estruturação de conteúdo e **CSS3** para estilização e layout, incluindo o uso de formulários com validação de entrada (regex).

## 🚀 Funcionalidades

O website é composto pelas seguintes páginas:

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | **Página Inicial:** Apresenta a ONG, sua missão, informações de contato e um chamado para voluntariado. |
| `projeto.html` | **Página do Projeto:** Detalha os objetivos do projeto (resgate, tratamento veterinário, adoção) e as formas de apoio (doação, adoção, divulgação). |
| `cadastro.html` | **Página de Cadastro:** Contém um formulário para o cadastro de novos voluntários, com campos que utilizam **validação de entrada (regex)** para telefone e CPF. |
| `style.css` | **Estilização:** Arquivo CSS responsável pelo design, layout e responsividade básica do website. |

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Estruturação semântica do conteúdo.
*   **CSS3:** Estilização e layout.

## 📝 Detalhes do Formulário de Cadastro

O formulário de cadastro em `cadastro.html` implementa validações específicas para garantir a integridade dos dados de contato e identificação:

| Campo | Padrão de Validação (Regex) | Exemplo de Formato |
| :--- | :--- | :--- |
| **Telefone** | `\(\d{2}\) \d{4,5}-\d{4}` | `(99) 99999-9999` ou `(99) 9999-9999` |
| **CPF** | `\d{3}\.\d{3}\.\d{3}-\d{2}` | `123.456.789-00` |

## 📂 Estrutura de Arquivos

```
Exercício Prático III/
├── README.md
├── cadastro.html
├── imagem/
│   └── (Arquivos de imagem do projeto)
├── index.html
├── projeto.html
└── style.css
```

## 🔗 Como Visualizar

Para visualizar o projeto, basta abrir o arquivo `index.html` em qualquer navegador web moderno.

1.  Navegue até o diretório `Exercício Prático III/`.
2.  Clique duas vezes no arquivo `index.html` ou abra-o através do menu do seu navegador.

---
*Desenvolvido como parte do curso de Desenvolvimento Front-End.*
