# 1. Create the index.html game
# 2. Create Dockerfile with content
```
FROM nginx
COPY . /usr/share/nginx/html/
``` 
it will add our html to nginx html directory

# 3. Build image

`docker build -t htmlgame .`

# 4. Run image

`docker run -d -p 80:80 htmlgame`

