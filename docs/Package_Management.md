# Task 3: Package Management

This page details how I used the Cloudsmith CLI for package operations in my organization’s repositories. All terminal outputs are evidenced by corresponding screenshots.

## 1. Upload a Package

I created a simple package (`example_package_psharma-0.0.1-py3-none-any.whl`) for upload. To upload it to the repository created in Task 2:

> cloudsmith push python psharma-dev/cloudsmith-cli-psharma-dev example_package_psharma-0.0.1-py3-none-any.whl

![Upload Package Screenshot](/docs/push-package.png)


