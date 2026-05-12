# Build Image Linux Kernel For Lichee Pi Nano

This project contains scripts and build outputs for compiling a Linux kernel for the **Lichee Pi Nano (Allwinner F1C100s)** board.

It is based on a legacy Sunxi kernel source.

---

## 📌 Overview

- Platform: Lichee Pi Nano (Allwinner F1C100s)
- Architecture: ARM (arm-linux-gnueabi)
- Kernel Source: https://github.com/robot9706/lichee-pi-nano-linux
- Toolchain: Linaro GCC 6.3.1 (2017.05)
- Host OS: Kali Linux

---

## ⚙️ Requirements

Install dependencies:

```bash
sudo apt update
sudo apt install -y \
build-essential \
bc \
bison \
flex \
libssl-dev \
libncurses-dev \
libelf-dev \
git \
wget


<img width="595" height="71" alt="image" src="https://github.com/user-attachments/assets/c1b8972f-daee-483c-aa09-8699d5b36717" />
