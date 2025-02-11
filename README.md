![Banner](bnner.png)
```ts

  @Controller('users')
  export class UserController {
    constructor(private readonly createUserService: CreateUserService){ }
    @Post()
    function create () {
      return this.createUserService.execute({
        name: 'Sargun Kohli',
        email: 'sargun.kohli152@gmail.com',
        role: 'Software Engineer'
      });
    }
  }

```

## Tech stack
 
[![My Skills](https://skillicons.dev/icons?i=java,c,nextjs,react,js,ts,html,css,nodejs,mysql,mongodb,redux,bootstrap,docker,vscode,powershell,bash,git,github,jest,tailwindcss,postgres,express,reactnative)](https://skillicons.dev)

