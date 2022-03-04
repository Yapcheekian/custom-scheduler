## WHAT
Practice using [kubebuilder](https://book.kubebuilder.io/) to implement k8s operator

## Steps
```bash
kubebuilder init

kubebuilder create api --kind Pod --group core --version v1
# Create Resource [y/n]
# n
# Create Controller [y/n]
# y

# start the controller
make run
```
