# YAML

Various YAML manifests from tests and demos, many of which are found on cormachogan.com

- folder vSphereWithTanzu contains manifests from demonstrations around vSphere with Tanzu, such as how to SSH to a TKG node when it is deployed on an NSX-T segment <https://cormachogan.com/2022/05/12/how-to-access-tkg-nodes-on-vsphere-with-tanzu-and-nsx-t/> and how to pull embedded Harbor images from a TKG cluster.

- Folder certs+contour-ingress contains YAML manifests related to blog <https://cormachogan.com/2021/11/02/securing-application-access-on-tkg-v1-4-with-cert-manager-and-contour/>

- Folder nfs+server+client contains YAML manifests for creating a NFS server pod, and a number of NFS client pods. It requires some modification, such as adding a valid IP address to the nfs-client-pv manifest once the server has been deployed, as well as selecting an appropriate storage policy for the NFS server storage class.
