
# Clothes Store Backend (Ecommerce WebSite NodeJs MongoDb)

The website sells clothing items . Using stripe intergration and MongoDb as a database

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [Material Ui templates](https://mui.com/)


## Deployment

To run this project run

```bash
  npm install
  npm run start
```


## API Reference

#### Get all items

```http
  GET /api/login
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Token` | `string` | **Required**. Your token  |

#### Get item

```http
  GET /api/Products/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Params

To install the backend on your machine you should create a .env file and change the MONGO_URL to your mongodb Database and change PASS_SEC JWT_SEC to Parameters of your choice .  

## 🚀 About Me
I'm a full stack developer. Engennering student looking for expriences and testing and learning every day check out my [website](https://haouderoussama.netlify.app/) for more .

