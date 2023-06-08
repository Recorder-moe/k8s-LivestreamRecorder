# k8s-recorder.moe

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add recordermoe https://github.com/Recorder-moe/k8s-recorder.moe
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
recordermoe` to see the charts.

To install the recorder.moe chart:

```bash
helm install my-recorder.moe recordermoe/recorder.moe
```

To uninstall the chart:

```bash
helm delete my-recorder.moe
```
