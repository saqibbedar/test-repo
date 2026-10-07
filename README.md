## Test Repository (Practice Room)

Test repository is a dedicated repository for my personal learning. Whenever, I need to do any experiment I do it using this repository. So, question must be, how this can be useful to you, right? Well, this is useful to you because you are allowed to do practice with it and I will accept your any change, even simple whitespace. Hence, you can practice opensource, branches, PR's and a lot of other git and github stuff.

# Get Started

1. Clone this repository:  

    ```bash
    git clone https://github.com/saqibbedar/test-repo.git
    cd test-repo && code .            # change dir and open it in the vscode
    ```

# Contribution

I welcome any sort of contribution, as stated above, even your whitespace is acceptable, so no worries for merge. Come and do it, the repo is yours.

To get started properly:

1. You need to fork this repository (fork means get a copy of this repository and share it on your personal account, just like how we do reshare posts on facebook, linkedin etc). 

2. Clone your forked repository: 

    ```bash
    git clone https://github.com/<your-username>/test-repo.git 
    cd test-repo && code .      # cd into test-repo and open vscode init
    ```

3. Setup upstream:

    ```bash
    git remote add upstream https://github.com/saqibbedar/test-repo.git
    ```

4. Create branch:

    ```bash
    git switch -c <branch-name>
    ```

5. Stage, commit and push your changes:

    ```bash
    git add <file-or-directory>
    git commit -m "commit message"
    push --set-upstream origin <branch-name>
    ```

6. Open a pull request from your fork's branch to original repository's main branch.

For detailed guideline on opensource contribution workflow [read this article](https://saqibbedar.github.io/gitcraft/opensrc-workflow/).