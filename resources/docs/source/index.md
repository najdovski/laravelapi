---
title: API Reference

language_tabs:
- bash
- javascript

includes:

search: true

toc_footers:
- <a href='http://github.com/mpociot/documentarian'>Documentation Powered by Documentarian</a>
---
<!-- START_INFO -->
# Info

Welcome to the generated API reference.
[Get Postman Collection](http://localhost/docs/collection.json)

<!-- END_INFO -->

#general


<!-- START_0d4cb2104f73e3ee9cf74a52a015de76 -->
## api/articles
> Example request:

```bash
curl -X GET \
    -G "http://localhost/api/articles" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/api/articles"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};

fetch(url, {
    method: "GET",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```


> Example response (200):

```json
{
    "data": [
        {
            "id": 1,
            "title": "Quidem tempore est voluptatum dolores cupiditate.",
            "body": "Distinctio aut omnis debitis cumque. Unde quis odio eum cum dicta iusto et. Veritatis rerum nihil fugit a architecto unde praesentium ut.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 2,
            "title": "Est suscipit velit cumque.",
            "body": "Error quo architecto est. Possimus officia explicabo est et vel consequatur natus. Voluptate vero velit voluptatem et amet vel quis. Eum sed repellat omnis itaque id tempora.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 3,
            "title": "Amet mollitia quia maiores at.",
            "body": "Quaerat id vel dolor sint officia harum. Quod aut aliquid natus odio architecto error odit laboriosam. Expedita praesentium veniam eveniet. Eum aliquid sapiente ipsum cumque assumenda est non vel.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 4,
            "title": "test",
            "body": "test",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:46:20.000000Z"
        },
        {
            "id": 5,
            "title": "Vel quidem quia a et aut voluptas eius.",
            "body": "Possimus est aut beatae quos officiis qui. Est non dolorem sit ut. Reiciendis omnis eaque blanditiis optio.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 6,
            "title": "Voluptas sit quisquam iusto omnis.",
            "body": "Est iure ipsa officiis quis. Et labore delectus eveniet reprehenderit. Rerum consectetur velit rerum aut similique. Aut amet soluta facere laudantium. Hic incidunt qui quam omnis eligendi rerum.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 7,
            "title": "Aut qui consequatur dolor itaque ipsa omnis.",
            "body": "Vel vero qui aperiam dicta eos quo alias. Quo mollitia sint quia molestiae sit magnam. Excepturi voluptatem ea numquam rem quis aut veritatis.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 8,
            "title": "Perspiciatis saepe voluptas esse dolorem.",
            "body": "Quasi rerum dicta quos iste corporis et. Cumque non nihil ratione neque. Delectus aut ex animi similique neque sequi.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 9,
            "title": "Numquam eum dolores laborum itaque.",
            "body": "Laudantium aut praesentium molestiae corrupti corrupti iure. Accusamus doloremque dolores voluptas ut dicta autem dolor. Et nihil inventore suscipit dicta. Rerum dolorem repudiandae sint.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 10,
            "title": "Quam qui dolor mollitia facere debitis accusamus.",
            "body": "Ducimus error accusantium et accusantium fugiat. Explicabo quisquam esse quam quaerat qui aut. Aut modi iste quasi ea officia impedit. Deleniti eligendi sit repudiandae qui excepturi nisi.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 11,
            "title": "Quia et neque architecto amet ea suscipit.",
            "body": "A rerum qui deserunt officia. Reiciendis dolor voluptatem qui voluptate sed. Aut deleniti est odio iste accusamus. Fugiat cum illo mollitia repudiandae.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 12,
            "title": "Sed dolorem ullam aut eos dolorum numquam.",
            "body": "Et qui itaque assumenda possimus et minima vero. Vero neque consequatur earum non.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 13,
            "title": "Qui eum quae ut voluptatum vel quo non.",
            "body": "Iste commodi mollitia numquam asperiores eum expedita. Dolore nam sunt dignissimos provident illum quod. Laudantium cupiditate aliquam facere veritatis. Quisquam omnis eaque rerum aperiam.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 14,
            "title": "Qui modi voluptas eum voluptatum.",
            "body": "Magni quia beatae ratione. Suscipit quisquam distinctio mollitia quaerat suscipit. Fuga accusamus aperiam aut vero.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        },
        {
            "id": 15,
            "title": "Iste mollitia eos qui ea nostrum natus ad alias.",
            "body": "Excepturi cupiditate voluptas officiis veniam corporis voluptas. Est harum iure quasi inventore beatae ad. Id necessitatibus ducimus nemo. Laboriosam officiis blanditiis quibusdam exercitationem.",
            "created_at": "2020-09-06T10:01:40.000000Z",
            "updated_at": "2020-09-06T10:01:40.000000Z"
        }
    ],
    "links": {
        "first": "http:\/\/localhost\/api\/articles?page=1",
        "last": "http:\/\/localhost\/api\/articles?page=2",
        "prev": null,
        "next": "http:\/\/localhost\/api\/articles?page=2"
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 2,
        "path": "http:\/\/localhost\/api\/articles",
        "per_page": 15,
        "to": 15,
        "total": 30
    }
}
```

### HTTP Request
`GET api/articles`


<!-- END_0d4cb2104f73e3ee9cf74a52a015de76 -->

<!-- START_a92651a991429ff89af216ff17612d94 -->
## api/article/{id}
> Example request:

```bash
curl -X GET \
    -G "http://localhost/api/article/1" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/api/article/1"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};

fetch(url, {
    method: "GET",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```


> Example response (200):

```json
{
    "id": 1,
    "title": "Quidem tempore est voluptatum dolores cupiditate.",
    "body": "Distinctio aut omnis debitis cumque. Unde quis odio eum cum dicta iusto et. Veritatis rerum nihil fugit a architecto unde praesentium ut.",
    "created_at": "2020-09-06T10:01:40.000000Z",
    "updated_at": "2020-09-06T10:01:40.000000Z"
}
```

### HTTP Request
`GET api/article/{id}`


<!-- END_a92651a991429ff89af216ff17612d94 -->

<!-- START_706a660bd426dfde8ef5e730869db3f8 -->
## api/article
> Example request:

```bash
curl -X POST \
    "http://localhost/api/article" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/api/article"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};

fetch(url, {
    method: "POST",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```



### HTTP Request
`POST api/article`


<!-- END_706a660bd426dfde8ef5e730869db3f8 -->

<!-- START_f98cdb8965ab64dbffcbdaaa7509093b -->
## api/article
> Example request:

```bash
curl -X PUT \
    "http://localhost/api/article" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/api/article"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};

fetch(url, {
    method: "PUT",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```



### HTTP Request
`PUT api/article`


<!-- END_f98cdb8965ab64dbffcbdaaa7509093b -->

<!-- START_13dad45773993e1d30a6eae802ceb05c -->
## api/article/{id}
> Example request:

```bash
curl -X DELETE \
    "http://localhost/api/article/1" \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"
```

```javascript
const url = new URL(
    "http://localhost/api/article/1"
);

let headers = {
    "Content-Type": "application/json",
    "Accept": "application/json",
};

fetch(url, {
    method: "DELETE",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```



### HTTP Request
`DELETE api/article/{id}`


<!-- END_13dad45773993e1d30a6eae802ceb05c -->


