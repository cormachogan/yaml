# YAML

Various YAML manifests from tests and demos

- Folder certs+contour-ingress contains YAML manifests related to blog <https://cormachogan.com/2021/11/02/securing-application-access-on-tkg-v1-4-with-cert-manager-and-contour/>

- Folder nfs+server+client contains YAML manifests for creating a NFS server pod, and a number of NFS client pods. It requires some modification, such as adding a valid IP address to the nfs-client-pv manifest once the server has been deployed, as well as selecting an appropriate storage policy for the NFS server storage class.
