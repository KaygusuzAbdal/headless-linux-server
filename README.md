# 🖥️ Headless Linux Server - Auto Cloud-Init Setup

This repository is directly linked to **Part 3** of my Medium series: *“How I Built a Fully Isolated Blue Team Lab at Home”*.  
It contains auto-installation (cloud-init) files I created to convert an old PC into a fully headless Linux server.

Full articles:  
👉 [TR - Evde BlueTeam Lab Kurulumu - Bölüm 3](https://cuneytkafes.medium.com/evde-blueteam-lab-kurulumu-bölüm-3-evdeki-pc-nasıl-sunucuya-dönüştürülür-9a7e7333b563)  
👉 [EN - From Dusty PC to Blue Team Lab - Part 2](#) *(link coming soon)*

---

## 📂 Repository Contents

This repo includes:

- `user-data`: The core Ubuntu cloud-init configuration. It handles SSH installation, user setup, and automated disk layout.
- `meta-data`: The minimal system descriptor required by cloud-init.

Additional folders:

- `/en/user-data-with-comment`: Contains the `user-data` file with detailed comments in English.
- `/tr/user-data-aciklama`: Contains the `user-data` file with explanations in Turkish. (TR: user-data dosyasında bulunan kodların türkçe açıklamasını içerir)
- `/tr/nocloud/`: This path includes a special config for Turkish (TR Q) keyboard layout. (TR: bu dosya yolunda bulunan dosyalarda TR Q klavye için özel yapılandırmalar da yer almaktadır)

---

## 📎 Quick Notes

- ISO used: Ubuntu Live Server 24.04 (cloud-init ready)
- You can generate your own password using:  
  `openssl passwd -6` *(uses SHA-512)*

---

## ✍️ About the Series

> 📌 This repository is part of my technical blog series:  
> **“How I Built a Fully Isolated Blue Team Lab at Home”**

You can explore all parts on my [Medium profile](https://cuneytkafes.medium.com).

---

**Mustafa Cüneyt Kafes**
