# TestBox Sample

```
box
mkdir test && cd test
coldbox create app name=test skeleton=rest-hmvc
cat box.json
start
testbox run
!code . 

box
git init
git add .
git commit -m "Inicializacion"
coldbox create handler name=Roles actions=index views=false directory=modules_app/api/modules_app/v1/handlers
testbox run
```
