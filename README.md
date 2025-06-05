# Swamp Tests

## Installing Swamp

### Homebrew

1. Add the `swamp` tap (only needed once):

   ```sh
   brew tap swamp/tap
   ```

2. Install the `swamp` formula:

   ```sh
   brew install swamp
   ```

`swamp-build`, `swamp-test`, should be in your `PATH`. When you need to upgrade, just run:

```sh
brew update
brew upgrade swamp
```

## Running the tests

```sh
swamp-test --path basic
```
