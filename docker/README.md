### Powershell over Docker
pull the imagem with powershell

```
docker pull microsoft/powershell
```

After execute the follow command
```
docker run -t --rm -v $PWD:/tmp microsoft/powershell /tmp/a.ps1
docker run -t --rm -v $PWD:/tmp microsoft/powershell /tmp/hello.ps1
```
