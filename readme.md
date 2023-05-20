# COMMANDS

## INIT NPM WITH DEFAULT CONFIG

```terminal
$ npm init -y
```

---

## INSTALL DEPENDENCIES

### Dev

```terminal
$ npm install eslint -D
```

or

```terminal
$ npm install eslint --save-dev
```

### Production

```terminal
$ npm install react
```

or

```terminal
$ npm install react -S
```

or

```terminal
$ npm install react --save
```

### Global (OS)

```terminal
$ npm install -g cowsay
```

### Optional

```terminal
$ npm install -o eslint
```

---

## LIST PACKAGES

### Local

```terminal
$ npm list
```

### Global

```terminal
$ npm list -g
```

---

## SIMULATE INSTALLATION

```terminal
$ npm install react-dom --dry-run
```

---

## INSTALL SPECIFIC VERSION

```terminal
$ npm install json-server@0.15.0
```

---

## INSTALL LATEST VERSION

```terminal
$ npm install json-server@latest
```

---

## COMMANDS IN NPM (SCRIPTS)

### Node Package Management

```terminal
$ npm run start
```

### Node Package Execute

```terminal
$ npx create-react
```

---

## UPDATING DEPENDENCIES

### Check packages list versions

```terminal
$ npm outdate
```

### Install latest version

```terminal
$ npm install react@latest
```

---

## Security and Issues solution

### Check issues

```terminal
$ npm audit
```

```terminal
npm audit --json
```

### Fix issues

```terminal
$ npm audit fix
```

### Update resource that needs more resources

```terminal
$ npm audit fix --force
```

---

## Delete dependencies and Package lock

### Delete dependency

```terminal
$ npm uninstall webpack-dev-server
```
