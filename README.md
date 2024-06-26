# kubernetes-ide
IDE for kubernetes

[documentation](https://htmlpreview.github.io/?https://github.com/christiancadieux/kubernetes-ide/blob/main/ide-doc/RDEI_IDE.html)



The Kubernetes IDE is a visual development environment for Kubernetes. It can be used to learn kubernetes or to develop prototypes . It allows to build applications (called projects) by creating, importing and associating kubernetes resources. These projects can be saved and executed in one of your namespaces.

Kubernetes IDE is also useful for documentation. Here is an example of a project using a variety of resources:   storage (PersistentVolume, PersistentVolumeClaim), compute (Deployment, ConfigMap, Secret), RBAC (Role, RoleBinding, ServiceAccount) and networking (Service, LoadBalancer, Ingress):


![157493775-72986497-83fb-426a-8170-15ffc5d0161b png (1761×1074)20220309115700](https://user-images.githubusercontent.com/10535265/157512365-0a0e80b3-6b46-453d-adb0-ce926c11b4cc.png)



![ide](https://github.com/christiancadieux/kubernetes-ide/assets/10535265/2d5087de-be42-4be0-85fd-c81991cfff73)



![ide](https://github.com/christiancadieux/kubernetes-ide/assets/10535265/e5b19e2c-81b6-4653-a3aa-48c8bee15207)



## Exposing relationships between resources

The Kubernetes IDE shows the relationships between the different resources to help understand the application. Here is an example with the PVC, secrets and env-vars used by the different deployments.

![Screenshot from 2023-12-31 09-42-31](https://github.com/christiancadieux/kubernetes-ide/assets/10535265/621910e7-3406-48bc-b35a-b89dab9030d1)

