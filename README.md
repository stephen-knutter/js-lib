# js-lib


```shell
# NPM package setup

npm set init-author-name 'steve-0'
npm set init-author-email 'example@email.com'
npm set init-author-url 'http://example.com'
npm set init-license 'MIT'

cat ~/.npmrc

npm set save-exact true

npm adduser
```


```shell
# NPM package publish

npm publish

npm info javascript-open-source-library
```

```shell
# Versioning

git tag 1.0.0
git push --tags 

# Update version

# Update `package.json` version field ex) 1.0.0 -> 1.1.0
git add -A
git commit -m "update"
git tag 1.1.0
git push
git push --tags
npm publish

# Beta version
# Update `package.json` version field ex) 1.1.0 -> 1.4.0-beta.0
git add -A
git commit -m "update beta"
git tag 1.4.0-beta.0
git push
git push --tags
npm publish --tag beta
```

```shell
# Semantic release

npm i -g semantic-release-cli
semantic-release-cli setup

```
