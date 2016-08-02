# Now integrated with swagger-codegen

[swagger-codegen](https://github.com/swagger-api/swagger-codegen) now has a typescript-angular2 language option now. To use:

```bash
swagger-codegen generate -i http://your-url/swagger.json -o client -l typescript-angular2
```

### Typescript Angular2 Swagger CodeGen Template

Angular 2 typescript template for [swagger-codegen](https://github.com/swagger-api/swagger-codegen)

### Usage

After cloning the repository run

```bash
swagger-codegen generate \
    -i http://petstore.swagger.io/v2/swagger.json \
    -o client/petstore \
    -l typescript-angular \
    -t ./TypeScript-Angular2
```
