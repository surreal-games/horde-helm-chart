# horde-helm-chart
Horde Helm Chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add horde-helm-chart https://surreal-games.github.io/horde-helm-chart

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
{alias}` to see the charts.

To install the horde-helm-chart chart:

    helm install horde horde-helm-chart/horde

To uninstall the chart:

    helm delete horde
