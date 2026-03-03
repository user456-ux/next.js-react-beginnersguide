# next.js-react-beginnersguide
 <br/>
:rocket: Let's get started. <br/>
Once completed you can code and watch your web page update instantly.  <br/>
As noted in the repo title, this is a beginner's guide for those looking for a quickstart intro  <br/>
into Next.js over React
for Modern Web Development.
<br/> <br/>
This tutorial is utilizing the Next.js platform by Vercel <br/>
which is an optimized ecosystem for building and deploying full-stack React applications. <br/>
You may ignore the "deploy" links in the borwser as this introduction is just for learning in your local dev environment. <br/>
Instructions are tested on Window 11.
<br/><br/>

## Prerequisites - Please familiarize yourself with the following technologies 
 - Windows Terminal
 - Visual Studio Code (Microsoft's flagship editor, NOTE: I am a .NET Engineer by trade)
 - Basic CSS / HTML5 concepts (this tutorial does **not** cover databases or microservices)

  <hr/>
  
- [x] Install Node.js e.g. winget install -e --id OpenJS.NodeJS
- [x] Open terminal &nbsp;&nbsp;&nbsp; (I prefer Powhershell 7 (x64))
- [x] npm install -g pnpm &nbsp; (faster version of npm)
- [x] VS Code setup | set Auto Save: afterDelay | set Auto Save Delay: 1000


1) Open windows explorer and terminal (explorer is optional, but it's nice to have a gui helper)
2) Create your folder e.g. mynextapp
3) cd into this folder
4) terminal | run pnpm create next-app [project-name] [options] <br/>
  &nbsp;&nbsp;&nbsp; ex.  pnpm create next-app mynextapp //this is a very basic e.g. empty
6) terminal | run pnpm dev to activate server which is now ready for browser
7) browse http://localhost:3000/  (now you can start editing nad learning)
8) VS Code open  ..\create-next-app\mynextapp\app\page.tsx

After the <Image> tag block

```html
   <Image
          className="dark:invert"
          src="/next.svg"
          alt="Next.js logo"
          width={100}
          height={20}
          priority
      />
```
add this

```html
           <div>
            <h1 className="max-w-md text-lg leading-8 text-zinc-600 dark:text-zinc-400">Welcome to My Next.js App</h1>
            <p className="text-blue-500">This is the home page.</p>
           </div>
```

> [!TIP]
> This is just a basic example. <br/>
> When you add the text above your browser is intantly updated. <br/>
> Visit here for begineers tutorialspoint.com have some fun (link is below). <br/>
> Make sure Ghostery Privacy Ad Blocker extension is installed for unintrusive free browsing.



 ### Ref Links 
 [nextjs pages](https://www.tutorialspoint.com/nextjs/nextjs_pages.htm) <br/>
 [nextjs docs](https://nextjs.org/docs/app/api-reference/cli/create-next-app)

 
