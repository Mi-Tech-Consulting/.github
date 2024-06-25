## Hi there 👋

# 🌈 Contribution guidelines
Here is the procedure on how to work with the GitHub repo, when you want to start coding:
1. Fork the origin repo to your `PERSONAL PRIVATE repo`
2. Working on your new repo, (usually you wanna check out a few feature branches thus to keep the default branch easy to sync and merge from - it is a bit tricky)
3. When your code is ready to merge, pls create a PULL REQUEST from your repo to the origin repo
4. Before merging, pls make sure you have run the following commands:
   ```console
   npm run build
   ```
   and then commit the changes to the PR
5. Once the PR is approved, it will be merged into the origin repo
6. Once the PR is merged, you can delete your PR branch

- branch: use `develop` branch as default
- Keep the code clean, style consistent
- Try to use the dependent libraries we provide. If you have special needs, please contact @jhcao23 or @keyskull 
- Always think about code reusability
- Pls let us know if you have any questions about this procedure


## 🙋‍♀️Getting Started

## How to Run a Develop Environment in Local 

* copy the `dev.next.config.js.sample` file to `dev.next.config.js`

Initial your project with the following commands:
```console
git submodule update --init
npm install
```

Finally, run the following commands to start the development server:

```console
npm run dev
```

You should now be able to access the application at http://localhost:3000.

Make sure you haven't run multiple instances for the same application at the same time.

## 🙋‍♀️ Rule of Submitting Your Code

Please make sure your code is locally built correctly before your `git push`.
Use command: 
```console
npm run build
```
to make sure the code you build is not in conflict.
Then use regular git operation to submit your code.

Thanks!

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
