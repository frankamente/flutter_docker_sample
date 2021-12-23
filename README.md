# Getting Started

### Introduction
This project is a sample project to have a flutter web-app running in Docker. 


### Requirements

* docker

### Usage

1. Compile image.

```
docker build -t stockapp .
```
* If you find any cache problem, execute:

```
docker build --no-cache -t stockapp .
```

2. Run the entire application.

```
docker compose up -d
```

3. Once application starts, you can access it at: http://localhost:1200
