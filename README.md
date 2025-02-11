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

<div style="display: flex; flex-wrap: wrap; justify-content: space-around; gap: 20px;">
    <div style="width: 10px; border: 1px solid #ddd; border-radius: 10px; overflow: hidden; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);">
        <a href="https://medium.com/@sargun.kohli152/whats-new-in-react-19-efff0027da41" target="_blank">
            <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pRJy7vK18HG4r3XpK2NUSw.png" alt="Article Thumbnail" style="max-width: 100%; height: auto; object-fit: cover;">
        </a>
        <div style="padding: 5px;">
            <h3 style="font-size: 18px; margin: 0 0 10px;">What's New in React 19?</h3>
            <p style="font-size: 14px; color: #555;">for enhanced performance to new developer tools, React 19 is packed with exciting updates to make your development process easy</p>
        </div>
    </div>
   <div style="width: 10px; border: 1px solid #ddd; border-radius: 10px; overflow: hidden; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);">
        <a href="https://medium.com/@sargun.kohli152/whats-new-in-react-19-efff0027da41" target="_blank">
            <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pRJy7vK18HG4r3XpK2NUSw.png" alt="Article Thumbnail" style="max-width: 100%; height: auto; object-fit: cover;">
        </a>
        <div style="padding: 5px;">
            <h3 style="font-size: 18px; margin: 0 0 10px;">What's New in React 19?</h3>
            <p style="font-size: 14px; color: #555;">for enhanced performance to new developer tools, React 19 is packed with exciting updates to make your development process easy</p>
        </div>
    </div>
</div>

