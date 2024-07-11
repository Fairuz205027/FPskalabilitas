# *FINAL PROJECT SKALABILITAS*

---

Fairuz Azhar A - 5027201059

![alt text](https://github.com/Fairuz205027/FPskalabilitas/blob/main/gambar%201.jpg?raw=true)

# Arsitektur

![alt text](https://github.com/Fairuz205027/FPskalabilitas/blob/main/gambar%202.jpg)?raw=true)

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


2. Atur Hak Akses Grup

bash
sudo usermod -a -G microk8s $USER
sudo chown -f -R $USER ~/.kube


3. Tambah Node 

bash
microk8s add-node


1.
