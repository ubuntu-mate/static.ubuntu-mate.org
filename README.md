# static.ubuntu-mate.org

- Video assets 📼

## Git setup

After creating this repo [LFS was enabled](https://github.com/git-lfs/git-lfs?tab=readme-ov-file#example-usage) via:

```shell
git lfs track "*.mp4"
git lfs track "*.webm"
git lfs track "*.webp"
git add .gitattributes
git commit -m "chore: track video files using LFS"
```
