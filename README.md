# charts

Helm chart for Keitz
```
helm package keitz
mv keitz-*.tgz docs
helm repo index docs --url https://keitz.github.io/charts
git add .
git commit ...
git push origin master
```
