
## create secret

```
copilot secret init \
  -n BODY \
  --values demo=Default-body,prod=Dburl-szekolya-szikret
```

## redeploy

```
copilot deploy --force -e prod
```