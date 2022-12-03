
# News Feed app

It is a News feed application which uses an API from https://newsapi.org/ and is based on 
Retrofit and RESTful API. 

In the project, the news articles are been send to display into RecyclerView, 
which is been requested from the news server through API request. Now the user can stay informed without switching between apps thanks to News Feed,
a simple software that provides the most recent and useful news from a variety of sources.


![logo](https://user-images.githubusercontent.com/95096810/205463821-a7522fee-573e-469b-9db8-1075969f4cb3.PNG)



## API Reference

#### Get items

```http
  GET https://newsapi.org/v2/top-headlines?country=in&apiKey=API_KEY
```

| **Parameter** | **Type**     | **Description**                |
| :-------- | :------- | :------------------------- |
| `country` | `string` | The 2-letter ISO 3166-1 code of the country. **in** code is been used|
| `apiKey` | `string` | API key is **Required**  |
| `category`| `string` | The category of news. **general, entertainment, health, science, sports, technology** categories thats been used |
| `pageSize` | `int` | The number of results to return per page. By default, it is **20**|
| `totalResults` | `int` | The total number results available for the request |
| `articles` | `array[article]` | The results of request |
| `author` | `string` | The author of the article |
| `title` | `string` | The headline or title of the article |
| `description` | `string` | A description or snippet from the article |
| `url` | `string` | The direct url to the article |
| `urlToImage` | `string` | The url to a relevant image for the article |
| `publishedAt` | `string` | The date and time that the article was published in UTC(+000) |
| `content` | `string` | The unformatted content of the article, where available. It is turncated to 200 chars |



## Screenshots


- Home page

![home](https://user-images.githubusercontent.com/95096810/205464032-7c8bddb7-720f-4d9a-9c96-360e8c09b337.PNG)

- Entertainment

![entertainment](https://user-images.githubusercontent.com/95096810/205464043-85e585c9-8267-4ef4-89f4-a952c42e25a9.PNG)

- Sports

![sports](https://user-images.githubusercontent.com/95096810/205464056-d4257a7c-341e-4bb8-ae22-4cee97408697.PNG)

- Health

![health](https://user-images.githubusercontent.com/95096810/205464082-717b0604-e399-4d86-96ea-9d06147572dc.PNG)

- Science
 
![science](https://user-images.githubusercontent.com/95096810/205464093-5a1137f1-5db5-4bbb-91bd-8ddb7b0a02a9.PNG)

- Technology

![techs](https://user-images.githubusercontent.com/95096810/205464109-48d26836-892c-46a7-93e3-740ab56daed1.PNG)

- Web view

![web_view](https://user-images.githubusercontent.com/95096810/205463907-4229f31a-9135-4925-a55a-5e47ad153a04.PNG)

- App drawer

![app_drawer](https://user-images.githubusercontent.com/95096810/205464127-aa40266f-7561-4608-a269-d9005c855786.PNG)
