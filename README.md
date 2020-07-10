# .githooks
My Git hooks

# Install

## Install dependency
```
pip install -r [requirements.txt](https://github.com/pouralijan/.githooks/blob/master/requirements.txt)
```


## Add .githook as a submodule

Change direcory to your git repository
```
git submodule add https://github.com/pouralijan/.githooks.git

```

## Config your git

Config git hookPath as global
```
git config --global core.hookspath ".githooks"
```

Config git hookPath as local(only for current repository)
```
git config core.hookspath ".githooks"
```
