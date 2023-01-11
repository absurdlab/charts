# Charts

This is the helm chart repository for absurdlab.

## Prerequisite

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add absurdlab https://absurdlab.github.io/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
absurdlab` to see the charts.

## Tigerd

To install the tigerd chart:

```bash
helm install my-tigerd absurdlab/tigerd
```

To uninstall the chart:

```
helm delete my-tigerd
```
