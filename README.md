# github-actions-workflow-experiment

## Getting started

### commitzen

```
npm install -D @commitlint/cz-commitlint commitizen
```

```
{
  "scripts": {
    "commit": "cz"
  },
  "config": {
    "commitizen": {
      "path": "@commitlint/cz-commitlint"
    }
  }
}
```

### commitlint

```
npm install -D @commitlint/cli @commitlint/config-conventional 
```

```
{
  "commitlint": {
    "extends": [
      "@commitlint/config-conventional"
    ]
  }
}
```
