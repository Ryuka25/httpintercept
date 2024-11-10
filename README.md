# HTTP Interception

## Testing on host

```sh
curl http://localhost:8080/intercept/get
```

![View 001](/assets/view001.png)

## Using Terminal

![Terminal](/assets/001.png)
![Existing Terminal](/assets/002.png)

```sh
fastapi run app/main.py --port 8080
```

## Using Docker

```sh
docker build -t httpintercept .
```

```sh
docker run -d --name httpintercept_app -p 8080:80 httpintercept
```

![alt text](/assets/docker001.png)
![alt text](/assets/docker002.png)

## Using docker compose
