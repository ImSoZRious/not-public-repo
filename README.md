the passphrase is `not-public-repo`

you can decrypt the repo with
```sh
gpg -d source.tar.gz.gpg | tar -zxvf -
```
the idea originated from [Storing large secrets](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#storing-large-secrets) from official github action documentation

