## Folder structure of a possible hexagonal and DDD (Domain Driven Design) architecture in golang

### This is an example, it can be done in many different way, please feel free to modify


read about this concept here:

https://en.wikipedia.org/wiki/Hexagonal_architecture_(software)


![Hexagonal architecture](harc.png)

Please note, this repo does not contain any code, just a way of implementing the structure. 

```
├── cmd
|     ├── api
|     ├── cmd
|     ├── web
├── internal
|     ├── adapters
|     |     ├── primary
|     |     |     ├── api
|     |     |     ├── cmd
|     |     |     ├── web
|     |     ├── secondary
|     |     |     ├── postgres
|     |     |     ├── mysql
|     |     |     ├── redis
|     ├── core
|     |     ├── domain
|     |     ├── services
|     ├── ports
```


Please see readme.md in folders, modify, restructure the tree for your domain requirements.

