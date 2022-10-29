# SSH

## RSA Keygen

Open Terminal, and run the following command to generate an RSA key:

```
ssh-keygen -t rsa` and then run `ssh-add ~/.ssh/id_rsa
```

Run the following command to output the RSA key:

```
cat ~/.ssh/id_rsa
```

Copy the output of the last command and enter it into the GitHub's SSH Key settings.
