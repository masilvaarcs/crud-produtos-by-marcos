# Crud Angular

Uma Aplicação simples - CRUD de Produtos (Create, Read, Update, Delete), desenvolvida com a finalidade de treinar recursos em angular usando o padrão **Observable**. 

## :computer: Tecnologias

<ul>
 <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
  <li><a href="https://github.com/typicode/json-server">JSON Server</a></li>
  <li><a href="https://github.com/angular/angular-cli">Angular CLI</a></li>
  <li><a href="https://github.com/ReactiveX/RxJS">RxJS</a></li>
</ul>

## :fire: Instalando e executando localmente

É necessário ter um ambiente NodeJS ou Yarn instalado em sua máquina

### Clonando o repositório

```
git clone https://github.com/masilvaarcs/crudProdutosAngular.git
```

### Executando backend e frontend

Para facilitar o entendimento e seguir o mesmo esquema utilizado no Curso, a execução localmente foi mantida separada, não sendo usado aqui a ***library Concurrently*** para executar backend e frontend simultâneamente com um único comando. Deve ser aberta as pastas e ser executada de forma separada(terminal). Um exemplo abaixo para ter uma ideia.

```bash
# Abrir uma nova instância do terminal
# Go to server folder
$ cd crudProdutosAngular

# Install Dependencies
$ npm install

# Run backend
# Abrir uma nova instância do terminal
# Go to backend folder
$ cd backend

$ npm start

# Run frontend
# Abrir uma nova instância do terminal
# Go to frontend folder
$ cd frontend

$ npm start
```

- Backend executando em <http://localhost:3002/products>
- Frontend executando em <http://localhost:4200>

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

 ---

<p align="center">Feito com 💜 por <strong><a href="https://www.linkedin.com/in/marcosprogramador/">Marcos Silva</a> 🥰 </strong> </p>
