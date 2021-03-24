# Swagger
O Swashbuckle tem três componentes principais:
- Swashbuckle.AspNetCore.Swagger: um modelo de objeto e um middleware do Swagger para expor objetos SwaggerDocument como pontos de extremidade JSON.
- Swashbuckle.AspNetCore.SwaggerGen: um gerador do Swagger cria objetos SwaggerDocument diretamente de modelos, controladores e rotas. Normalmente, ela é combinada com o middleware de ponto de extremidade de Swagger para expor automaticamente o JSON do Swagger.
- Swashbuckle.AspNetCore.SwaggerUI: uma versão incorporada da ferramenta de interface do usuário do Swagger. Ele interpreta o JSON do Swagger a fim de criar uma experiência rica e personalizável para descrever a funcionalidade da API Web. Ele inclui os agentes de teste internos para os métodos públicos.
<br />

### Link Tutorial
- https://docs.microsoft.com/pt-br/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-5.0&tabs=visual-studio

### Nuget Package
```
Install-Package Swashbuckle.AspNetCore -Version 5.6.3
```

### Link para visualizar o documento Swagger 
- http://localhost:<port>/swagger

