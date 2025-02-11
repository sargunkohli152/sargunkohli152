![Banner](banner.png)
```ts

  @Controller('users')
  export class UserController {
    constructor(private readonly createUserService: CreateUserService){ }
    @Post()
    function create () {
      return this.createUserService.execute({
        name: 'Sargun Kohli',
        email: 'sargun.kohli152@gmail.com',
        role: 'Software Engineer',
        leetcode: 'sargun_code',
        linkedIn: 'https://www.linkedin.com/in/sargun-kohli-b829a61ba/',
        medium: 'https://medium.com/@sargun.kohli152',
      });
    }
  }

```

