# homebrew-wemakeit

This tap retains slightly outdated brews required for setting up a working copy of wemakeit on macOS.

## postgresql

```bash
# Find out whether Homebrew provides postgresql 10.5
brew update
brew info postgresql | head -n 1

# Install from Homebrew if it provides the correct version
brew install postgresql

# Install from this tap otherwise
brew install wemakeit/wemakeit/postgresql@10.5
```

## postgis

```bash
# Find out whether Homebrew provides postgis 2.4.x
brew update
brew info postgis | head -n 1

# Install from Homebrew if it provides the correct version
brew install postgis

# Install from this tap otherwise
brew install wemakeit/wemakeit/postgis@2.4
```
