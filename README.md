<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Resolução: Desafio 07 - GoFinances Web
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#funcionalidades-da-aplicação">Funcionalidades da Aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#especificações-dos-testes">Especificações dos Testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## Tecnologias Utilizadas

- [ReactJS](https://pt-br.reactjs.org/);
- [ESLint](https://eslint.org)
- [Prettier](https://prettier.io)
- [Typescript](https://typescriptlang.org)

### Funcionalidades da Aplicação

- **`Lista as transações da API`**: A página `Dashboard` exibe uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na API desenvolvida no [Desafio 06](https://github.com/thiagonascimento8512/desafio-database-upload).

- **`Exibe o balance da API`**: A página `Dashboard`, exibe o balance que é retornado do backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importa arquivos CSV`**: A página `Import`, permite o envio de um arquivo no formato `csv` para o backend, que irá fazer a importação das transações para o banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

### Específicações dos testes

- **`should be able to list the total balance inside the cards`**: Para que esse teste passe, a aplicação deve permitir que seja exibido na Dashboard, cards contendo o total de `income`, `outcome` e o total da subtração de `income - outcome` que são retornados pelo balance do backend.

* **`should be able to list the transactions`**: Para que esse teste passe, a aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do backend.

- **`should be able to navigate to the import page`**: Para que esse teste passe, a aplicação deve permitir a troca de página através do Header, pelo botão que contém o nome `Importar`.

- **`should be able to upload a file`**: Para que esse teste passe, a aplicação deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de `import`, e que seja possível exibir o nome do arquivo enviado para o input.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
