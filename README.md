# 📇 Sistema de Agenda de Contactos - CTESP

Sistema web para gestão de contactos de alunos desenvolvido com Vanilla JavaScript, PHP e CSS.

## 📋 Descrição

Este projeto é um sistema de agenda de contactos desenvolvido para o curso CTESP de Sistemas Informáticos. Permite aos utilizadores pesquisar, adicionar e visualizar contactos de alunos através de uma interface web simples e intuitiva.

## ✨ Funcionalidades

- **Pesquisa de Alunos**
  - Pesquisa por número do aluno
  - Pesquisa por nome do aluno
  
- **Gestão de Contactos**
  - Adicionar novos contactos (Nome, E-mail, Número do aluno)
  - Visualizar todos os contactos
  - Armazenamento em arquivo de texto (`contactos.txt`)

- **Interface Responsiva**
  - Menu dropdown navegável
  - Design limpo e funcional
  - Estilos CSS personalizados

## 🛠️ Tecnologias Utilizadas

- **Frontend:**
  - HTML5
  - CSS3
  - Vanilla JavaScript
  - jQuery (v3.6.4)
  - AJAX para submissão de formulários

- **Backend:**
  - PHP
  - Sistema de arquivos para persistência de dados

## 📁 Estrutura do Projeto

```
VanilaJS-Wesite/
├── index.html                    # Página principal
├── novo-contacto.html           # Formulário para adicionar contactos
├── novo-contacto.php            # Processamento de novos contactos
├── pesquisa-por-nome.html       # Interface de pesquisa por nome
├── pesquisa-por-nome.php        # Lógica de pesquisa por nome
├── pesquisa-por-numero.html     # Interface de pesquisa por número
├── pesquisar-por-numero.php     # Lógica de pesquisa por número
├── estilos.css                  # Estilos CSS
├── scripts.js                   # Scripts JavaScript
├── contactos.txt                # Base de dados (arquivo de texto)
├── README.md                    # Este arquivo
└── src/
    └── trabalho-main/           # Versão do trabalho
```

## 🚀 Como Usar

### Pré-requisitos

- Servidor web com suporte a PHP (Apache, Nginx, XAMPP, WAMP, etc.)
- Navegador web moderno

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/marcelo-m7/VanilaJS-Wesite.git
```

2. Mova os arquivos para o diretório do seu servidor web:
   - XAMPP: `C:/xampp/htdocs/`
   - WAMP: `C:/wamp/www/`

3. Certifique-se de que o arquivo `contactos.txt` tem permissões de escrita

4. Acesse através do navegador:
```
http://localhost/VanilaJS-Wesite/index.html
```

## 📝 Uso

### Adicionar Novo Contacto

1. Navegue para "Adicionar Aluno" no menu
2. Preencha o formulário com:
   - Nome do aluno
   - E-mail
   - Número do aluno
3. Clique em "Adicionar"

### Pesquisar Contacto

1. No menu, selecione "Pesquisar Aluno"
2. Escolha o tipo de pesquisa:
   - Por número do aluno
   - Por nome do aluno
3. Insira os dados de pesquisa
4. Visualize os resultados

## 🎨 Funcionalidades do CSS

- Menu dropdown responsivo
- Inputs estilizados com bordas arredondadas
- Fonte personalizada (Andale Monospace)
- Layout limpo e profissional

## 🔧 Funcionalidades JavaScript

- Submissão de formulários via AJAX
- Validação de dados
- Feedback visual de sucesso/erro
- Integração com jQuery para manipulação DOM

## 📊 Formato de Armazenamento

Os dados são armazenados no arquivo `contactos.txt` no seguinte formato:
```
Nome;Email;aNumero
```

Exemplo:
```
João Silva;joao.silva@example.com;a79433
Maria Santos;maria.santos@example.com;a79434
```

## 👨‍💻 Desenvolvedor

**Marcelo Santos** 