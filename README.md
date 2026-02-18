# This was Fork from : [ianshulx - React-projects-for-beginners](https://github.com/ianshulx/React-projects-for-beginners)

## Fix MovieCard App.css Error. 
---
## for depecrated NPM solution. 
---
### Delete package-lock.json

```bash
rm -rf node_modules package-lock.json
```

### reinstall react-scripts

```bash
npm install react-scripts --save
```

### verify script

```bash
ls node_modules/.bin | grep react-scripts
```

### start App

```bash
npm start
```


