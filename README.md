# 📓 Notehub

![GitHub repo size](https://img.shields.io/github/repo-size/FajarFarel/notehub)
![GitHub stars](https://img.shields.io/github/stars/FajarFarel/notehub?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/FajarFarel/notehub)

<img width="1240" height="649" alt="notehub mockup" src="https://github.com/user-attachments/assets/a7c0a723-018a-4e85-b43c-855d9a6aeade" />

---

**Notehub** is an application where users can create notes about anything and share them across the internet.  
this application provides various features and pages wrapped in an interactive and beginner-friendly user interface.

---

## 🧩 main features

- ✒ create new notes  
- 👁 read notes from other users  
- 🔍 explore thousands of notes  
- 🔖 save favorite notes  
- 📆 writing frequency calendar  

---

## 🛠️ technologies used

### 📱 frontend (flutter)

- flutter sdk  
- [`http`](https://pub.dev/packages/http) – api communication  
- [`shared_preferences`](https://pub.dev/packages/shared_preferences) – local storage  
- [`getx`](https://pub.dev/packages/get) – state management  
- [`image_picker`](https://pub.dev/packages/image_picker) – profile photo selection  

---

### 🌐 backend (flask)

- rest api  
- ngrok  

---

### 📂 storage (database)

- mysql  
- cloudinary  

---

## 🗃️ database structure

### 📘 Tabel users
```sql
id, nama, email, password, foto, tanggal_pembuatan_akun
```

### 📗 Tabel notes
```sql
id, user_id, judul, isi, kategori, tanggal
```

### 📕 Tabel save_notes
```sql
id, user_id, note_id
```

## 👥 Contributors

- 👨‍💻 **Wahyu** - frontend developer (pm)
- 👨‍💻 **Fajar** – backend developer
- 🤖 Asisten AI  

---

## License

This project is licensed as open source software.
all features of this software are available free of charge.
📩 contact the developers for more information. 
[View License](LICENSE)
