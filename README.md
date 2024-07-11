# *FINAL PROJECT SKALABILITAS*

---

Fairuz Azhar A - 5027201059

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/feb3e241-4a24-49ca-97bd-e9294678876f/93ed65dc-dadc-421f-b9f9-e893a1a04cc7/Untitled.png)

# Arsitektur

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/feb3e241-4a24-49ca-97bd-e9294678876f/fc3047b2-d44f-4c04-9b57-5ffc26839e70/Untitled.png)

### Master

IP : 10.15.40.65

### Worker

- IP : 10.15.40.55
- IP : 10.15.40.64

# Implementasi

## Worker

---

1. Install MickroK8s

bash
sudo apt-get install snapd
sudo snap install microk8s --classic


## Master

---

1. Instalasi MicroK8s pada Master Node

bash
sudo apt-get install snapd
sudo snap install microk8s --classic


1. Atur Hak Akses Grup

bash
sudo usermod -a -G microk8s $USER
sudo chown -f -R $USER ~/.kube


1. Tambah Node 

bash
microk8s add-node


1.
