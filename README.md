# Git Checkout

Checks-out your repository under `$GITHUB_WORKSPACE`, so your workflow can access it. Leverages the official [checkout action](https://github.com/actions/checkout) pre-configured specifically for the Codebelt methodology. 

This ensures a smooth and consistent way to setup your CI/CD pipeline as well as structuring your repository.

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: codebeltnet/git-checkout@main
```

### Inputs

This action has no inputs.

### Outputs

This action has no outputs.

## Examples

### Fetch entire repository


```yaml
steps:
  - name: Checkout
    uses: codebeltnet/git-checkout@main
```

## Contributing to Git Checkout

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
