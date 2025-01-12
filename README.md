# Trabalho-extensionista

Este projeto é uma aplicação desenvolvida em C# utilizando Windows Forms, com o objetivo de promover a inclusão digital e acessibilidade na educação. A aplicação é voltada para escolas públicas e comunidades carentes, oferecendo uma plataforma acessível e intuitiva para aprendizado.

## Funcionalidades

1. **Tela Inicial**:
   - Menu principal com opções para navegação entre as funcionalidades do sistema.

2. **Cadastro de Usuários**:
   - Permite registrar alunos e professores.
   - Campos disponíveis: Nome e Tipo de usuário (Aluno ou Professor).

3. **Cursos Disponíveis**:
   - Lista de cursos básicos como Informática Básica, Navegação Online e Introdução ao Windows.

4. **Configurações de Acessibilidade**:
   - Opções para aumentar a fonte ("Ativar fonte grande").
   - Modo escuro para facilitar a visualização.

## Estrutura do Código

O código está organizado em diferentes formulários para atender às funcionalidades principais:

### **1. MainForm** (Formulário Principal):
   - Contém o menu principal com botões para acessar as funcionalidades:
     - Cadastro de Usuários
     - Cursos Disponíveis
     - Configurações de Acessibilidade

### **2. CadastroUsuariosForm**:
   - Formulário para cadastro de usuários com validação simples e mensagens de sucesso.

### **3. CursosForm**:
   - Exibe uma lista de cursos disponíveis para os usuários.

### **4. AcessibilidadeForm**:
   - Permite configurar opções de acessibilidade, como fonte grande e modo escuro.

## Requisitos de Sistema

- **Linguagem**: C#
- **Framework**: .NET Framework (Windows Forms)
- **IDE**: Visual Studio
- **Sistema Operacional**: Windows

## Como Executar

1. Clone o repositório para o seu computador.
2. Abra o projeto no Visual Studio.
3. Compile o projeto para garantir que todas as dependências estão corretas.
4. Execute o aplicativo pressionando `F5` ou iniciando o programa pelo botão de "Start".

## Melhorias Futuras

- Integração com banco de dados para persistência de dados de usuários e progresso nos cursos.
- Suporte multilíngue para ampliar o alcance do projeto.
- Implementação de recursos adicionais de acessibilidade, como leitores de tela e comandos por voz.
- Criação de um sistema de autenticação para proteger os dados dos usuários.
