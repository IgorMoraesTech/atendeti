# Atende TI

Sistema web para registrar e acompanhar chamados de suporte de informática.

Projeto acadêmico da disciplina Linguagens e Tecnologias para Desenvolvimento Web.

## Integrantes

- José Igor Moraes da Silva
- Micael da Silva Gomes

## Objetivo

Permitir que cada usuário registre problemas de informática e acompanhe
seus próprios chamados em um único lugar.

## Funcionalidades previstas

- Cadastro de usuários.
- Login e logout.
- Criação, listagem, visualização, edição e exclusão de chamados.
- Organização dos chamados por categoria, prioridade e status.
- Acesso restrito aos chamados do próprio usuário.

Nesta versão, o próprio usuário gerencia seus chamados.
Não haverá um perfil separado de técnico.

## Dados de um chamado

- Título: resumo do problema.
- Descrição: detalhes do problema.
- Categoria: hardware, software, rede ou outros.
- Prioridade: baixa, média ou alta.
- Status: aberto, em andamento ou resolvido.
- Proprietário: usuário que criou o chamado.
- Datas de criação e atualização.

## Tecnologias previstas

- React para a interface.
- Node.js e Express para a API.
- MongoDB para armazenar os dados.
- Mongoose para definir os modelos e suas validações.
- Axios para as requisições da interface à API.
- bcrypt para gerar e verificar hashes de senhas.
- JWT para autenticação.
- Docker e Docker Compose para execução em contêineres.

## Organização do trabalho

As tarefas são acompanhadas pelas issues deste repositório.

Cada tarefa será desenvolvida em uma branch e submetida por pull request.
Os dois integrantes contribuirão no front-end e no back-end.

## Situação atual

Projeto em desenvolvimento. As funcionalidades acima representam o
escopo planejado e serão implementadas por etapas.
