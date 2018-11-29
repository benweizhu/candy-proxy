# simple-nginx-reverse-proxy-example

Start the real backend server

```
cd server
npm install
node index.js
```

```
cd html
npm install
node index.js
```

Start the nginx reverse proxy
```
docker-compose up
```

![image](https://user-images.githubusercontent.com/5471228/49225879-26176b80-f420-11e8-92e5-f36549bca2b5.png)
