# Llegeix-me!

Aquests arxius es poden deseplegar amb un Cluster amb aquests requeriments:

- 1 master node anomenat k8smaster
- 2 worker nodes anomenats k8swork1 i k8swork2.
- Aquests worker nodes han de tenir un disc dur muntat a /mnt/dades d'almenys 5GB d'espai.

Per millorar: 

- Afegir un DNS i accés web per HTTPS
- Volums en servidor NFS.
- Volums en servidor Ceph (persistència de dades en servidors distribuïts)
