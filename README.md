# Website
Now, the www.unpadforstrays.or.id is our frontline on the internet. Made with TailwindCSS, AlpineJS, Eleventy SSG and hosted on Netlify with DecapCMS added for Content Management.

## Documentation
- Clone this repo to your machine
- Install Eleventy [https://www.11ty.dev/docs/]
- Install TailwindCSS with npm, not using CDN! [https://tailwindcss.com/docs/installation]
- Customize as you like!
- Install DecapCMS (formerly Netlify) with these docs [https://decapcms.org/docs/add-to-your-site/]
- Run the build script to test everything out: npx @11ty/eleventy on your terminal
- Everything should run smoothly
- Create file netlify.toml with these script:
  
[build] <br>
command = "npx @11ty/eleventy" <br>
publish = "_site" <br>

  - This command means your 'final' site folder is located in the _site folder
  - Create a .eleventyignore file with the following script, this will exclude those files from being uploaded to Github:
    
README.md <br>
.github/ <br>
node_modules <br>
_site

  - git push to your own repo
  - Sign in to your Netlify account
  - Add Site, connect to your github account, select your repo
  - Deploy!

Made by Felicia (@felii_christine)

