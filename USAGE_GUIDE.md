# 🌍 Google Maps Scraping Tool - Complete Guide

Ye ek powerful tool hai jo Google Maps se leads (Name, Phone, Address, Website, Email) extract karne ke liye use hota hai.

## 🚀 Tool Run Karne Ka Tariqa

Tool ko run karne ke 2 main tariqe hain:

### Tariqa 1: Web Interface (Asaan Tariqa)
Isme aapko browser mein ek premium looking dashboard mil jayega.

1. Terminal mein ye command likhein:
   ```powershell
   .\google-maps-scraper.exe -web
   ```
2. Browser mein ye URL open karein: **http://localhost:8080**
3. **"New Job"** par click karein.
4. Queries mein wo keywords likhein jin ki leads chahiye (e.g., `Software Houses in Karachi`).
5. **Depth** ko `1` ya `2` rakhein (jitni depth hogi, utni zyada leads ayengi).
6. **Create Job** par click kar dein. Leads ka data dashboard par nazar aane lagega.

### Tariqa 2: Terminal/Command Line (Fast Tariqa)
Agar aap direct file se nikalna chahte hain.

1. Ek file banayein `queries.txt` aur usme apne keywords likhein (har line par ek).
2. Ye command run karein:
   ```powershell
   .\google-maps-scraper.exe -input queries.txt -results leads.csv -depth 1
   ```
3. Jab process khatam hoga, aapki leads `leads.csv` mein save ho jayengi.

---

## 🎯 Best Lead Generation Keywords
Website development services bechne ke liye ye keywords best hain:
- `Real Estate Agents in [City]`
- `Gyms and Fitness Centers in [City]`
- `Private Schools in [City]`
- `Car Showrooms in [City]`
- `Construction Companies in [City]`

---

## ⚠️ Important Tips
- **Empty CSV Fix:** Hamesha apni queries wali file ko **UTF-8 encoding** mein save karein (Warna Windows ki files tool read nahi kar pata).
- **Email Extraction:** Agar aapko emails bhi chahiye, to web interface mein `"Extract Email"` ka option on karein (is se process thora slow ho jayega lekin data behtar milega).
- **Unlimited Usage:** Ye tool unlimited free hai, aap jitni chahain leads nikaal sakte hain.

---

*Powered by Muneeb Qureshi's Scraping Engine*
