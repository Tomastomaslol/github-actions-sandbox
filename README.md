# Actions sandbox


> There is a catch when you’re developing actions that react to issue comments! When a new comment is added to a pull request, the event actually happens on the default branch of the repository, typically main or master. This makes development of new action workflows a bit difficult since you’re not able to test them properly until the code is merged to the default branch. Therefore, you might want to do your development and testing in a separate repository, and then copy the final working result back to your original repository.

[Run GitHub Actions on Issue Comments](https://pakstech.com/blog/gh-actions-issue-comments/)

This is sandbox for me to develop github actions so I can test them before i merge them in to a "real" repository. 
