# CSI-Snapshots-Demo
Manifests to accompany the CSI Snapshots Demo on YouTube

- demo-sc-pvc-pod-rwo.yaml contains sample StorageClass, PVC, PV and Pod manifests to test snapshot 
- csi-snapshot-class.yaml contains VolumeSnapshotClass manifest 
- dynamic-vol-snap.yaml contains VolumeSnapshot manifest to take a snapshot of demo PVC
- snapshot-restore.yaml contains PVC manifest that restore snapshot to a new PVC
- snapshot-restore-pod.yaml contains Pod manifest to mount new PVC and check snapshot data contents

# Blog Post
- https://cormachogan.com/2022/03/03/announcing-vsphere-csi-driver-v2-5-support-for-csi-snapshots/

# Video / Demo
- https://www.youtube.com/watch?v=_zsOYx8ZjJU
