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

## Tech Blog Posts
[![What's New in React 19?](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pRJy7vK18HG4r3XpK2NUSw.png)](https://medium.com/@sargun.kohli152/whats-new-in-react-19-efff0027da41)
