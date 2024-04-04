# Git Checkout

Checks-out your repository under `$GITHUB_WORKSPACE`, so your workflow can access it. Leverages the official [checkout action](https://github.com/actions/checkout) pre-configured specifically for the majority. 

> This action is part of the Codebelt ecosystem and ensures a consistent way of: 
> 
> - Defining your CI/CD pipeline 
> - Structuring your repository
> - Keeping your codebase small and feasible
> - Writing clean and maintainable code
> - Deploying your code to different environments
> - Automating as much as possible
>
> A paved path to excel as a DevSecOps Engineer.

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
