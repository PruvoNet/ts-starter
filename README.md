# TS-STARTER

Simple starter project for typescript

If you need to wait on other services to start you can use in the docker file:

```
CMD [ "./wait.sh" , "lcoalhost:3000", "--", "node", "index.js" ]
```
