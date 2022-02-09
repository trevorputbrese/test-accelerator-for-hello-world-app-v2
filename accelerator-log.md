# Accelerator Log

## Options
```json
{
  "branch" : "master",
  "description" : "This is a my 2nd app-accelerator by Trevor P.",
  "icon" : "https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png",
  "name" : "test-accelerator-for-hello-world-app-v2",
  "projectName" : "test-accelerator-for-hello-world-app-v2",
  "url" : "https://github.com/trevorputbrese/test-accelerator-for-hello-world-app-v2.git"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","name":"test-accelerator-for-hello-world-app-v2","description":"This is a my 2nd app-accelerator by Trevor P.","artifactId":"test-accelerator-for-hello-world-app-v2","projectName":"test-accelerator-for-hello-world-app-v2","branch":"master","url":"https://github.com/trevorputbrese/test-accelerator-for-hello-world-app-v2.git"}
┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input14557403386475574168, --data-values-file, /tmp/accelerator-options327783148845229262.json, --output-files, /tmp/ytt-output17108794455493376857]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┗ ┗ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
