# Setting up the SSH

1. Open Git Bash
2. In git bash/termainal type : ssh-keygen
     * Enter a file in which to save the key (/c/Users/you/.ssh/id_algorithm):[Press enter]
     * Enter passphrase (empty for no passphrase): [Press Enter]
     * Enter same passphrase again: [Press Enter]
 
### Now you have generated the SSH key next step is to add your key to github

3. In your terminal/bash type :clip < ~/.ssh/id_rsa.pub # Windows
    * You have your key in your clipboard
4. Goto github.com -> setting -> ssh -> add ssh
5. Paste the key 
