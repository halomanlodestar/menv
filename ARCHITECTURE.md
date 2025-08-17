# Components

## Daemon
Holds a reference to the source of truth of the current state
Actual linking using `symlink`

## CLI
Used to work with `Profiles`

Create
Read
Update 
Delete

## Store
  ### Profile Store
  Registry
  Stores profile dependencies

## Adapter Plugins
Scripts and binaries that control other components

## Atomic Switcher
Controls the order of service activation and stopping
Swap
Apply Simlinks
Start Services

## Resolver
Resolves dependencies

## Transaction Log
Built on top of git (maybe)
Contains rollback data
Contains Snapshot data

## Test Harness (Optional)
Checks before applying the profile
fallback mechanism for failing profiles
