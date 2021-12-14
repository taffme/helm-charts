# helm-charts

Helm Charts Monorepo

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```bash
helm repo add taffme https://helm.taffco.me/
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. You can then run:
```bash
helm search repo taffme
```
to see the charts.

To install the chart *<chart_name>*:

`helm install <chart_name> taffme/<chart_name>`

To uninstall the chart *<chart_name>*:

`helm delete <chart_name>`
