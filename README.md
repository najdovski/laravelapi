## API Routes

# All articles
GET api/articles

# Single article
GET api/article/{id}

# New article
POST api/article
[Request body]: "id", "title", "body"

# Update article
PUT api/article
[Request body]: "article_id", "title", "body"

# Delete article
DELETE api/article/{id}
