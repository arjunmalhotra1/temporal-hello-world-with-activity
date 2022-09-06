# temporal-helloworld-with-activity

## Bring the Temporal cluster up
  ```
  git clone https://github.com/temporalio/docker-compose.git
  cd docker-compose
  docker-compose up
  ```

## Run the worker
In a separate terminal window.
```
go run worker/main.go
```
![Screen Shot 2022-09-05 at 5 06 47 PM](https://user-images.githubusercontent.com/43081882/188516209-951681fe-8a20-4b9a-98bf-36c466168992.png)


## Run the starter
In a separate terminal window.
```
go run starter/main.go
```

![Screen Shot 2022-09-05 at 5 06 40 PM](https://user-images.githubusercontent.com/43081882/188516216-2a2bc60e-a5f8-4575-9f69-e2b75c60b797.png)
