# 🚀 Take-Home Challenge: Mini-platformă de Onboarding pentru Profesori

Proiectează și dezvoltă o platformă simplă de onboarding pentru profesori în **2-4 ore**, concentrându-te pe **clean code** și **UX**.

---

## 📊 Structura DB

```sql
-- Profesor (Teacher)
CREATE TABLE teachers (
  id BIGINT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(100) NOT NULL,
  subjects VARCHAR(255),          -- ex: "matematica,informatica"
  hourly_rate DECIMAL(10,2),      -- tarif pe oră
  availability VARCHAR(255),      -- ex: "luni-vineri,09:00-17:00"
  created_at DATETIME NOT NULL DEFAULT CURRENT_TIMESTAMP
);
```

---

## 🎯 Cerințe Funcționale

### 1. **Landing Page Simplă**
- [Hero section](https://tailwindui.com/components/marketing/sections/heroes) minimal cu titlu și descriere
- Button **"Înregistrare Profesor"**

### 2. **Formular de Înregistrare**
- **Input-uri:** Nume, email, materii predate (dropdown multi-select sau input cu tags), tarif pe oră, program disponibilitate (text sau time picker simplu)
- **Validare:** Validări de bază pentru input-uri
- **Preview:** În timp real sub formular care arată cum va apărea anunțul

### 3. **Confirmare & Preview**
- **Submit:** Salvare în DB
- **Redirect:** Pagina de succes cu datele introduse
- **Opțional:** Link de editare (fără auth, doar cu preview)

---

## 🛠️ Cerințe Tehnice

### **Stack Recomandat**
- **Frontend:** React, Vue, Angular, Laravel Blade, Django Templates, Rails ERB, Vanilla JS
- **Backend:** Orice MVC Framework (.NET, Node, Laravel, Spring)
- **UI:** [Tailwind CSS](https://tailwindcss.com/) (sau alt framework CSS)
- **DB:** SQL (MySQL, PostgreSQL, SQLite)

### **Must Have**
- Cod curat, organizat
- Validări de bază
- Responsive design
- Git workflow cu commits clare

### **Nice to Have (Opțional)**
- Tests
- Error handling
- Loading states

---

## 📦 Livrabile

| **Livrabil**         | **Detalii**                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **GitHub Repo**      | - README cu instrucțiuni de setup<br>- Screenshots cu aplicația<br>- Commits organizate          |
| **Demo (Opțional)**  | - GIF/video cu flow-ul complet<br>- SAU link către aplicația deployed (Netlify, Vercel, Heroku) |

---

## 💡 Tips pentru Succes

### 🛠️ **Recomandări:**
- Folosește AI tools (ChatGPT, GitHub Copilot) pentru boilerplate
- Comunică dacă ai blocaje sau întrebări - apreciem proactivitatea
- Concentrează-te pe quality coding și UX plăcut

### ✅ **Focus pe:**
- Cod curat și bine organizat
- Design modern și intuitiv (ex: [Tailwind UI components](https://tailwindui.com/components))
- Git workflow profesionist cu commits clare
- Documentație minimală dar utilă în README

### ❌ **De evitat:**
- Setup complicat sau over-engineering
- Cod copiat fără înțelegere
- UI/UX neintuitive sau design inconsistent

---

## 🎯 Evaluare

| 🏆 **Categorie**       | **Criterii**                                                                                                                                              | **Pondere** |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| **Implementare tehnică** | - Cod curat și organizat<br>- Arhitectură pragmatică<br>- Validări și error handling<br>- Funcționalitate completă                                       | **40%**     |
| **Frontend & UX**      | - Design modern și intuitiv<br>- Responsive pe mobile și desktop<br>- Componente reutilizabile<br>- Preview funcțional și atractiv<br>- Atenție la detalii UI/UX | **40%**     |
| **Best Practices**     | - Git workflow profesionist<br>- README clar<br>- Coding standards                                                                                       | **20%**     |

---

## 📩 Contact
Pentru orice întrebări: [rares@meditatii.ro](mailto:rares@meditatii.ro). Feel free to reach out! 

De asemenea, dacă ai feedback sau sugestii pentru acest proiect, suntem deschiși să le auzim!


**Mult succes!** 🚀
