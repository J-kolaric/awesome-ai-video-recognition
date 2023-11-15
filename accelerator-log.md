# Accelerator Log

## Options
```json
{
  "pkgName" : "com.example",
  "projectName" : "awesome-ai-video-recognition"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ Debug .DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/.DS_Store matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/banner.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/index.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/style.css matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/tap.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug express/video.js matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug package-lock.json matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ Debug package.json matched [**/*] -> included
┃ ┃ ┃ ┗ ┗ Debug server.js matched [**/*] -> included
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
