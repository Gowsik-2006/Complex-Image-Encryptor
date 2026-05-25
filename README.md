# 🔒 Complex Image Encryptor

A simple Python GUI tool that makes your images completely **unrecognizable** by using **pixel-level encryption**:
it **shuffles pixel positions** and **XORs the pixel values** with your secret **Key** and **Seed**.

---

## ✨ Features

- **Strong scrambling:** Pixel values are XOR-ed with your secret key.
- **Position shuffle:** Pixels are shuffled using a repeatable random seed.
- **Fully reversible:** Using the same Key + Seed decrypts the image exactly.
- **Simple GUI:** Built with **CustomTkinter**.
- **Supports PNG, JPG.**

---

## 🔑 How it works
- **Encrypt**: Each pixel (R, G, B) is XOR-ed with your Key → pixel array is shuffled with your Seed.

- **Decrypt**: The shuffle is reversed using the same Seed → pixel values are XOR-ed again with the same Key → original image is restored.

- Without your Key + Seed, it’s practically impossible to recover the original.

---

## 🧩How to Use
- 1️⃣ Install requirements
- 2️⃣ Run the app
- 3️⃣ Encrypt an image
  - Click Load Image.
  - Enter your Key (any integer).
  - Enter your Seed (any integer).
  - Click Encrypt Image and save the scrambled file.
- 4️⃣ Decrypt an image
  - Load the encrypted image.
  - Enter the same Key & Seed.
  - Click Decrypt Image — the original image will be restored and saved.

**🔑 Remember:**

Key & Seed must match to decrypt correctly.

Without them, the scrambled image is unreadable!

---

## 🧑‍💻 Author
- Built by **Gowsik Raja.S**
- Cybersecurity & Python enthusiast.

---
<img width="598" height="526" alt="Screenshot 2025-07-20 204723" src="https://github.com/user-attachments/assets/4369e2b9-633b-4938-b7b5-5809f9d6f719" />

