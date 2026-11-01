# DevOps Medium Scripts

Scripts used in [DevOps Medium](https://devopsmedium.com) tutorials: shell, Terraform, Kubernetes
manifests, Dockerfiles and more. Each doc pins a tag or commit, so the code on devopsmedium.com is
exactly what's here.

## How Docs Use These Scripts

A doc embeds a file by path and ref:

```md
::script{src="DevOps-Medium/scripts/k8s/install-ingress.sh" ref="v1.2.0" title="Install script"}
```

- Prefer **tags** (`v1.2.0`) or commit SHAs. A branch ref works, but docs only pick up new commits
  when they're re-published.
- Tag a release when a script changes, so docs that pin an older tag keep showing the code they
  were written for.

## Licence

[MIT](LICENSE): use, copy, modify and distribute these scripts freely, including commercially, as
long as the copyright notice and licence are kept.

The scripts are provided "as is", without warranty of any kind. Read a script before you run it,
test it outside production first and keep backups. You run them at your own risk.
