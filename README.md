tflint mirror
====================

Mirror of tflint for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For tflint: see https://github.com/terraform-linters/tflint

### Using tflint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-tflint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: tflint-conda
```

