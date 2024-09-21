+++
title = "2. Process Notion to Github Repo"
weight = 2
+++


Open [Notion to MD](https://notion-to-md.bamidev.com/), fill in the information, and proceed to the step where you click "Parse into Hugo Relearn".


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-559206-image.png)


It will show the “Chapter Structure” table, where we can preview and check if the Git repository structure matches the headings inside our Notion page.


The repository structure will follow two simple rules:

1. **Header H1** will always create a new directory.
2. **Headers with larger numbers** will always be inside the nearest smaller header. For example, **H2** will be inside **H1**.

Try not to overthink this structure for now. Just follow the trial-and-error principle, and we’ll be fine.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-370998-image.png)


Fill in the Sync to GitHub information and start the “Sync to GitHub” process.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-548956-image.png)


(Troubleshooter) This error may occur if you use a brand-new repository without any initialized commits.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-323283-image.png)


The solution is to initialize the Git repository. Just use the simple git instruction, and that should be enough.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-549134-image.png)


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-118283-image.png)


If everything is working correctly, the process will start and scroll through each step. When it’s complete, you will see this message.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-344208-image.png)


Double-check the GitHub repository. You should see the `content` directory (holding contents) and the `static` directory (holding images) created, indicating success.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-322387-image.png)


