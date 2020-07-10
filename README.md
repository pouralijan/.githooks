# .githooks
My Git hooks

# Install

## Install dependency
Install dependency with [requirements.txt].
```
pip install -r requirements.txt
```

## Add .githook as a submodule

Change direcory to your git repository and ...

Add my [.githooks] repository to your repository as a submodule.
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

[requirements.txt]: https://github.com/pouralijan/.githooks/blob/master/requirements.txt
[.githooks]: https://github.com/pouralijan/.githooks.git
