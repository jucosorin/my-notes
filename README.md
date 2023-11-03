
Create package.json file with empty object
```shell
node -e "fs.writeFileSync('package.json', '{}')"
```
Install Antora locally
```shell
npm i -D -E @antora/cli@3.1 @antora/site-generator@3.1 @antora/lunr-extension
```
Check Antora version
```shell
npx antora --version
```
Run Antora
```shell
npx antora --fetch antora-playbook.yml
```