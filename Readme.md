# Kubectl Plugin

This plugin provides completion for the `kubectl` command.

## Installation

```bash
sudo chmod +x ./scripts/kubeplugin
sudo ln -s $(pwd)/scripts/kubeplugin /usr/local/bin/kubectl-kubeplugin
```

## Usage

Where `<resource>` can be `pod` or `node`. The `<namespace>` is namespace of the resource.
```bash
kubectl kubeplugin <namespace> <resource>
```

## Example

```bash
kubectl kubeplugin default pod
```

## Demo

![Demo](https://github.com/brokerUA/devops101-w5-m5-t1/blob/main/demo.gif)