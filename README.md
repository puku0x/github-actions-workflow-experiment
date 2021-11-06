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

### standard-version

```
{
  "scripts": {
    "release": "npx standard-version"
  },
  "standard-version": {
    "releaseCommitMessageFormat": "chore(*): bump v{{currentTag}}",
    "skip": {
      "tag": true
    }
  }
}
```