# large-files

## Commit

```bash
git lfs track AdventureWorks2019.bak
git add AdventureWorks2019.bak
git commit -m "Added large file"
```

## Installation on Ubuntu 20.04.6 LTS

```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash

sudo apt-get install git-lfs
```

## References

https://stackoverflow.com/questions/62905325/this-repository-is-over-its-data-quota-account-responsible-for-lfs-bandwidth-sh

1. Go to your repo settings.
2. Scroll down to the archives section.
3. Check on the checkbox of Include Git LFS objects in archives.
4. Then try to push from locally again.
