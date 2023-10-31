
# Kubevap Binaries

This repository contains the binaries for Kubevap, a powerful tool for managing Kubernetes clusters seamlessly. The project is maintained by Itera-IO.

## Installation

To get started, you can clone the repository to your local machine using the following command:
```
git clone https://github.com/itera-io/kubevap-binaries
```

## Updating Versions

Make sure to update the versions properly in the `versions.yaml` file before making any commits. You can do this by modifying the file directly and then using the following commands to add and commit the changes:

```
git add versions.yaml
git commit -m "generate kubernetes binaries for k8s version 1.27.7"
```

## Tagging and Pushing Changes

To distinguish between development and production versions, make use of the appropriate tags. For example:
```
git tag dev-v1.27.7
git push origin dev-v1.27.7
```

## GitHub Actions

Once you've completed the necessary steps, the GitHub Actions should automatically be triggered. You can monitor the process in the Actions tab. Good luck!
