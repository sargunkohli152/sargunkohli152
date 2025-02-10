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

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/sargun-kohli-b829a61ba/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sargun-kohli-b829a61ba/" height="30" width="40" /></a>
<a href="https://www.leetcode.com/sargun_code" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="sargun_code" height="30" width="40" /></a>
</p>

## Skills
 
[![My Skills](https://skillicons.dev/icons?i=java,c,nextjs,react,js,ts,html,css,nodejs,mysql,mongodb,redux,bootstrap,docker,vscode,powershell,bash,git,github,jest,tailwindcss,postgres,express,reactnative)](https://skillicons.dev)
