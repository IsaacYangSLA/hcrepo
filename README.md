## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add hcrepo https://IsaacYangSLA.github.io/hcrepo

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
hcrepo` to see the charts.

To install the my-chart chart:

    helm install my-chart hcrepo/my-chart

To uninstall the chart:

    helm delete my-chart
