Errors and Troubleshooting

##Tried to fetch origin and got the following message:
git@github.com: Permission denied (publickey)

+ https://docs.github.com/en/authentication/troubleshooting-ssh/error-permission-denied-publickey 
++ ssh -vT git@github.com 
+++ debug1: Reading configuration data /etc/ssh/ssh_config
+++ debug1: /etc/ssh/ssh_config line 21: include /etc/ssh/ssh_config.d/* matched no files
+++ debug1: Authenticator provider $SSH_SK_PROVIDER did not resolve; disabling

++ I don't have a key (or the right key)
+++ following instructions from the link above, I confirmed I do not have a key to be used.

++ Checking for existing SSH Keys: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys 
+++ I do see keys, but I'm not sure I want to use those. I'll add new ones.

++ Generate new keys: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent 
+++ seems to work well. My old keys were using a custom name, so I didn't need to worry about over writing anything.

++ https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent 
+++ https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent
++++ 

### Adding a new Key to Github
