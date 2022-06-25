# Reproduction

```
git clone https://github.com/kkirsche/yarn-issue-repro.git
cd yarn-issue-repro
yarn install
yarn upgrade-interactive
```

Example output:
![CleanShot 2022-06-25 at 16 30 27@2x](https://user-images.githubusercontent.com/947110/175789670-a25faa80-54e7-4877-951b-387d26e21799.png)

Expected output would have the correct versions displayed in all locations rather than the aliased package's versions.
