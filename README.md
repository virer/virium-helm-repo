## 🚀 Overview

This repository contains the **Virim CSI driver Helm Charts** — Virium is a Kubernetes CSI-compatible plugin that extends the functionality of the [official iSCSI CSI driver](https://github.com/kubernetes-csi/csi-driver-iscsi) to support **dynamic provisioning**.

**CSI plugin name**: `virium.csi.virer.net`

This driver works in conjunction with a running and properly configured [**Viriumd** API server](https://github.com/virer/viriumd), which handles the underlying LVM and iSCSI operations.

## 🔧 Usage:

```
helm repo add virium https://virer.github.io/virium-helm-repo/
helm repo update
helm search repo virium
helm install a1 virium/virium --namespace=virium --create-namespace -f values.yaml 
```
## ⚙️ Instruction

Please check the content of [Virium CSI Driver Controller](https://github.com/virer/virium-csi-drv-controller) repository for documentation.

## 📚 Other reference

- [Viriumd API server](https://github.com/virer/viriumd)