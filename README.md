# 🧾 Projeto Cadastro de Clientes - Delphi

Este projeto é uma aplicação desenvolvida em **Delphi** com foco em uma **tela de cadastro de clientes**, utilizando os conceitos de programação orientada a objetos, componentes visuais (VCL), conexão com banco de dados via **FireDAC**, e boas práticas de organização de código.

## 🧩 Funcionalidades

- Cadastro de novos clientes
- Edição de clientes já cadastrados
- Exclusão de registros
- Pesquisa por nome ou CPF
- Validação de campos obrigatórios
- Integração com a API ViaCEP para preenchimento automático do endereço via CEP

## 🛠️ Tecnologias Utilizadas

- Delphi (versão sugerida: RAD Studio XE ou superior)
- FireDAC (acesso a banco de dados)
- SQLite ou MySQL (banco de dados, configurável)
- REST Client (para consumo da API ViaCEP)
- DataModule (para separação da lógica de acesso a dados)
- Componentes VCL padrão (TEdit, TComboBox, TButton, TDBGrid etc.)

## 📁 Estrutura do Projeto

/src
├── frmCadastroCliente.pas
├── frmCadastroCliente.dfm
├── uDmConexao.pas
├── uDmConexao.dfm
└── main.dpr

## 🧪 Como Usar

1. Abra o projeto no Delphi.
2. Configure a conexão com o banco no `uDmConexao`.
3. Compile e execute o projeto (`F9`).
4. Use a tela principal para cadastrar e consultar os clientes.

## 🔌 Integração com ViaCEP

- O campo de CEP consulta a API [https://viacep.com.br](https://viacep.com.br)
- Preenche automaticamente: Logradouro, Bairro, Cidade e Estado.

## 🧾 Campos do Cadastro

- Nome completo
- CPF
- Data de nascimento
- Telefone
- E-mail
- Endereço completo (CEP, Rua, Número, Bairro, Cidade, Estado)

## 💡 Melhorias Futuras

- Validação completa de CPF e E-mail
- Exportação dos dados para PDF/Excel
- Paginação de resultados
- Autenticação de usuários

## 👨‍💻 Autor

Emanoel Smarce  

---

