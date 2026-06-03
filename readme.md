# ocpvirt-gitops

### Helm way
```sh
helm install my-vms ./helm-vm-deployer --dry-run
helm install my-vms ./helm-vm-deployer -n part1
helm upgrade my-vms ./helm-vm-deployer -n part1
```
### Git
```
git add .
git commit -m "Added vm3 in argo folder"
git push
```