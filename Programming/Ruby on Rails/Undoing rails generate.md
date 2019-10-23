# Undoing rails generate

## replace 'generate' with 'destroy'
```
rails generate controller StaticPages home help
rails destroy controller StaticPages home help
```
or
```
rails generate model User name:string email:string
rails destroy model User
```

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMzU1MTkxMDRdfQ==
-->