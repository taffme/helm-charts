[taffme](alias)
# helm-charts
Helm Charts Monorepo

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```bash
helm repo add taffme https://helm.taffco.me/
```
If you had already added this repo earlier, run:
```bash
helm repo update
```
to retrieve the latest versions of the packages. You can then run:
```bash
helm search repo taffme
```
to see the charts.
