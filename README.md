# Git LFS Skip Smudge

A Buildkite Plugin to prevent repos using Git-LFS from downloading files not needed for the pipeline steps.

## Example

```yaml
steps:
  - label: ":buildkite:"
    plugins:
      - roshreview/git-lfs-skip-smudge#v0.0.1:
          depth: 1
```
