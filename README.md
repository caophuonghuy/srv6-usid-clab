
# **🚀 Containerlab for SRv6 w uSID compression**

> This repo is few containerlabs about SRv6 with uSID compression. For now, all labs are set up with Nokia SR OS router.

## 📌 Contents (to be updated)

- [Introduction](#-introduction)

---

## 📖 Introduction

This repo is few containerlabs about SRv6 with uSID compression. For now, all labs are set up with Nokia SR OS router.

1. Fist lab in parent folder is the maser lab with all 7750 SR boxes
2. Other labs in subfolders are deviation topo with sligtly changes in nodes, topo, etc...

local folder: ~/srv6-uSID/ (just for me to remember)

repository url:
https://github.com/caophuonghuy/srv6-usid-clab.git

---
Topolog

## 📂 Project structure (to be updaed)

```to be updated
.
├── README.md
├── all-7750SR  (master lab)
├── IXR-access  (lab with IXR as access routers)
├── ixr-sgw     (lab with IXR as PE routers)
├── picture     (pictures of topo, capture screens...)
```

## 🖼️ topology

<p align="center">
  <img src="./pictures/uSID_lab1.png" alt="Demo" width="800">
</p>
---

## ⚙️ Deploy the labs

```bash
git clone https://github.com/caophuonghuy/srv6-usid-clab.git
cd srv6-usid-clab/
```

---
To deploy each lab

```bash
#
cd all-SR-routers
clab deploy -t SRv6-uSID.clab.yaml
```
or just

```bash
clab deploy
```

---

## 🛠️ to be updated

- P
- H
---

## 📈 To be updated

- T1
- T2
- T3

---