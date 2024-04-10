# manifests for the project [Inception of Things](https://github.com/AndreIglesias/Inception-of-Things/) p3

To change the version of the app "wil-playground", you can do it with:

```bash
sed -i 's/wil42\/playground\:v1/wil42\/playground\:v2/g' deploy.yaml # or manifests/deploy.yaml, depending on where you are
```

Then just push the change

```bash
git add deploy.yaml
git commit -m 'v2'
git push
```
