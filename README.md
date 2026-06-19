# homebrew-tap

This is the official Homebrew Tap for [atcprojectio](https://github.com/atcprojectio) applications.

## How to Use This Tap

You can add this tap to Homebrew by running:

```bash
brew tap atcprojectio/tap
```

Once tapped, you can install any of the available applications. Alternatively, you can install them directly without tapping first by referencing the full tap path.

## Available Applications

### ATC (Active Traffic Control)

[ATC](https://github.com/atcprojectio/atc) is a lightweight, high-performance Go service that automates the creation and management of Consul service-resolver configurations. It monitors Consul endpoints and automatically publishes failover or redirect rules when failing services are detected.

* **Type**: Cask (macOS Application/Binary)
* **Install Command**:
  ```bash
  brew install --cask atcprojectio/tap/atc
  ```
  *(or `brew install --cask atc` if already tapped)*

## Managing Installations

### Upgrade

To upgrade installed casks:

```bash
brew update
brew upgrade --cask atc
```

### Uninstall

To uninstall:

```bash
brew uninstall --cask atc
```
