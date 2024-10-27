## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add mark1002-k8s-summit-2024 https://mark1002.github.io/k8s-summit-2024

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo mark1002-k8s-summit-2024` to see the charts.

To install the myapi chart:

    helm install mark1002-myapi mark1002-k8s-summit-2024/myapi

To uninstall the chart:

    helm delete mark1002-myapi
