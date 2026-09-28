# githubaction-trial

A proof-of-concept repo for learning **GitHub Actions** workflows.

## Workflows
| Workflow | Trigger | What it shows |
|---|---|---|
| [`firstexample.yml`](.github/workflows/firstexample.yml) | every push | A single job: check out the repo and run shell steps |
| [`multiplejobs.yml`](.github/workflows/multiplejobs.yml) | every push | Several jobs in one workflow |

## Script
[`ascii.sh`](ascii.sh) installs `cowsay`, writes a dragon to `dragon.txt`, then greps and prints it. It's used as a sample step in the workflows.

```bash
bash ascii.sh
```

Runs appear in the repo's **Actions** tab.
