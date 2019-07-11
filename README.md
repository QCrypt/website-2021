# Cloud Native Day Amsterdam 2019 website

Please join the #nl-users on Kubernetes slack (free invite on slack.k8s.io)

## Contributing

Work in this repo with Hugo `hugo serve`, when done:

hugo generates the assets in `./public`

```bash
#push the main repo
git push -f

#push the gh-repo branch
git push origin `git subtree split --prefix public master`:gh-pages --force
```
