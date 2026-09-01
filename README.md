## Test Repository

Welcome to the testing repository, in this repo I learn GitHub by testing different git commands. You are also welcome to give a try to learn a open source contribution by contributing to this repo or perform any sort of testing. You can try anything like creating branches, deleting them, submitting pull request, deleting files or adding any new. So, whatever mess you can make do in this repo its a learning repository. Think it like a playground for learning from mistakes. Yes! Mistakes do teach you a lot. So, don't wait any further. Let's get started 🚀!!!

## Get Started

1. Clone this repository:  

    ```bash
    git clone https://github.com/saqibbedar/test-repo.git
    cd test-repo && code .            # change dir and open vscode
    ```
That's all setup. Starting doing the shit whole terrain is yours!!! And push your changes, let me see check them what you got!!! 😂!!!

# Understanding `git stash`

I am editing `README.md` locally and guess what? This file is modified, too, on remote (GitHub). So, can we fix this scenario? For example, if I commit and push the change to remote then we gonna face the conflict on both ends, so to resolve this always bring the remote changes first to your local machine and sophisticatedly save your local commits in a temporary area using `git stash`. 

### Steps:

- **Scenario**: You already have changes on remote and on same files you have changes, too, but locally. 
    1. Run `git stash` to save your local changes at temporary place.
    2. Run `git pull` all change gonna be fetched and synthesized perfectly locally.
    3. Run `git stash pop` now everything is clean so bring back your previous local changes cleanly without any conflict. It's simple like egg.
