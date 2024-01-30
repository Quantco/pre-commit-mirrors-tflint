# tflint mirror

Mirror of tflint for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For tflint: see [here](https://github.com/terraform-linters/tflint)

## Using tflint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-tflint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: tflint-conda
```
