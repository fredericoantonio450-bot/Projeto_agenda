# 📖 Projeto Agenda de Contatos em PHP

Este projeto consiste no desenvolvimento de uma aplicação web dinâmica de **Agenda de Contatos**, desenvolvida como projeto prático no curso técnico do **SENAC** (Técnico em Informática para Internet).

A aplicação foi criada utilizando **HTML5, CSS3, Bootstrap e PHP**, estruturada com arrays associativos para simular o armazenamento e a manipulação dos dados dos contatos.

O sistema permite listar, visualizar e editar os contatos através de navegação dinâmica via parâmetros de URL, garantindo modularidade, reaproveitamento de código e facilidade de manutenção.

---

## 🎥 Demonstração do Projeto

<img width="800" height="362" alt="ProjetoAgenda-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/5d3900af-5957-4a63-947e-23449eb63d29" />

---

## 🚀 Funcionalidades

- **Listagem dinâmica de contatos** na página inicial em formato de tabela.
- **Navegação individual por contato** via parâmetro de URL (`ver.php?id=3` e `novo.php?id=3`).
- **Formulário dinâmico** para cadastro e edição de contatos.
- **Estruturação dos dados** em arrays associativos PHP.
- **Uso de templates reutilizáveis** (`header.php` e `footer.php`) para manter o padrão visual.
- **Layout responsivo** e moderno estilizado com Bootstrap e tema personalizado.
- **Exibição detalhada** dos campos:
  - ID único do contato
  - Nome completo
  - Telefone
  - Observações / Descrição

---

## 🧩 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Bootstrap 5** / **Bootstrap Icons**
- **PHP**
- **Servidor local** (XAMPP, WAMP, MAMP ou similar)

---

## 📂 Estrutura do Projeto

```text
Projeto_Agenda/
│── index.php                                     # Página inicial (listagem de contatos)
│── ver.php                                       # Página de exibição de detalhes do contato
│── novo.php                                      # Página de cadastro/edição de contato
│── README.md                                     # Documentação do projeto
│── ProjetoAgenda-ezgif.com-video-to-gif-converter.gif  # Demonstração em GIF
│
├── css/
│   └── style.css                                 # Estilos personalizados
│
├── dados/
│   └── contatos.php                              # Array associativo com os dados dos contatos
│
├── ajudantes/
│   └── funcoes.php                               # Funções auxiliares do projeto
│
└── modelos/
    ├── header.php                                # Cabeçalho e barra de navegação
    └── footer.php                                # Rodapé padronizado
