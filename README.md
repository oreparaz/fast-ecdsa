# fast-ecdsa

installing python2 is easier than porting this to python3 (sorry)

```
brew install pyenv
pyenv install 2.7.18
export PATH="$(pyenv root)/shims:${PATH}"
echo 'PATH=$(pyenv root)/shims:$PATH' >> ~/.zshrc
pyenv init
```

then for development:

```
pyenv shell 2.7.18
```
