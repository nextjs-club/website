# website
This is my home~~

#### step 1: 
+ vim ~/ssh/config
+ Host nextjs.club.github.com
+ HostName github.com
+ User nextjs.club
+ IdentityFile ~/.ssh/github_nextjs.club

#### step 2:
+ git remote rm origin
+ git remote add origin git@nextjs.club.github.com:nextjs-club/nextjs-club.github.io.git
