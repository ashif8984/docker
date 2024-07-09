### Simple Node JS application

This is just a simplet node application to demonstarte the use of
dockerfile to create custom image and deploy containers with it.

---

### Prerequisites

> - [Node.js](https://nodejs.org/en/download/) installed
> - [Docker](https://www.docker.com/) installed

### Install

```
git clone https://github.com/ashif8984/docker.git
```

```
cd project-1
```

```
npm install
```

### Run

```
node app.js
```

Visit http://localhost:8000 in your browser

### Creating image

```
docker build -t ashif8984/simple-web-server .
```

### Running Container

```
docker run -it -p 8000:8000 ashif8984/simple-web-server
```
