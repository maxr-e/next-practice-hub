10.20.23 Max here. creat-react-app was how I was taught to start a react app. This method also includes a couple hundred Mb of dependencies that will be loaded each time user first views the app, so I've read. Using Next.js via 'create-next-app' only includes a few modules. This project is my first time using it and exploring how it works. I will be journaling my journey here and in the code comments.
I created this app locally on my desktop. I will create a repo in github later.

I added this locally hosted project to github by doing the following:
First, initialize a git repo.
   1. Open Git Bash
   2. Navigate to the root directory of the project (/Desktop/GitLab_Classwork/sandbox/react practice/react-explorer/next-practice (main))
   3. Initialize the local directory as a Git repo. By default, the initial branch is called `main`.
   ```
   git init -b main
   ```
   4. Add thefiles in the new local repo, staging them for the first commit.
   ```
   git add .
   ```
   5. Commit the files staged in the local repo.
   ```
   git commit -m "First commit"
   ```
Second, add the local repo to GitHub using Git
   1. Create a new repo on GitHub.com, and do not include a README, license or gitignore. Add them later.
   2. While on GitHub.com's Quick SetUp page, click the copy icon to copy the remote repository URL.
   ![Copy icon on right](https://next-practice.github.com/media/git_set_up.png)
 
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
