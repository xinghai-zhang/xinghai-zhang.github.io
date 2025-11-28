# xinghai-zhang.github.io


Create a branch per change (post / feature)
New post branch
git checkout -b post/my-new-article
hugo new posts/my-new-article.md
# edit, preview with hugo server -D
git add .
git commit -m "Draft: my new article"
git push -u origin post/my-new-article


Then:

Open a Pull Request into main

Review your diff like code

When ready, set draft: false and merge

After merging → CI runs → post goes live.