# KemDigSl – Kemijanje Digitalnih Slika

AI-powered desktop aplikacija za obradu i restauraciju slika.  
Razvijena u C# (WinForms) uz integraciju Python AI modela za naprednu obradu.

---

## Installer

ISO installer dostupan na:

https://drive.google.com/file/d/1oJKFBEfaBDwAcUWUaX_gluE-aMb-Rz5k/view?usp=sharing

---

## Pregled aplikacije

![Preview](https://github.com/user-attachments/assets/86e6221d-3759-4b10-ab99-26c09489e756)

---

## Funkcionalnosti

Aplikacija objedinjuje više AI modela u jedinstveno sučelje:

- Real-ESRGAN — povećanje / smanjenje rezolucije  
- GFPGAN — obnova lica  
- CodeFormer — napredna restauracija lica  
- DDColor — kolorizacija crno-bijelih slika  
- AdaIN — style transfer  
- YOLOv8n — detekcija objekata  
- AnimeGANv2 — cartoon efekt  
- LaMa — uklanjanje objekata i oštećenja  
- AutoFix — automatska optimizacija slike  

Dodatno su dostupne klasične transformacije:

- brightness  
- contrast  
- saturation  
- sharpness  
- grayscale  
- sepia  

---

![Preview](https://github.com/user-attachments/assets/96d28301-3df9-45ce-a331-f997fe6f9657)

---

## Sistemski zahtjevi

- Windows 10 ili Windows 11 (64-bit)  
- Preporučeno: 16 GB RAM  
- GPU nije obavezan (ali ubrzava obradu)  
- Dovoljno slobodnog prostora za modele i runtime  

---

## Instalacija

Instalacija se sastoji od dvije komponente:

1. Setup (.exe)  
2. BIN datoteke (modeli i runtime)  

---

### 1. Preuzimanje setup datoteke

Preuzeti:

KemDigSl_Setup_Quick.exe

---

### 2. Preuzimanje BIN datoteka

Putanja:

Releases → Latest Release → Assets  

Potrebno preuzeti:

KemDigSl_Setup_Quick-1.bin  
KemDigSl_Setup_Quick-2.bin  
KemDigSl_Setup_Quick-3.bin  
KemDigSl_Setup_Quick-4.bin  
KemDigSl_Setup_Quick-5.bin  

---

### 3. Priprema instalacije

Sve datoteke moraju biti u istom direktoriju:

KemDigSl_Setup_Quick.exe  
KemDigSl_Setup_Quick-1.bin  
KemDigSl_Setup_Quick-2.bin  
KemDigSl_Setup_Quick-3.bin  
KemDigSl_Setup_Quick-4.bin  
KemDigSl_Setup_Quick-5.bin  

Napomena:

- Ne mijenjati nazive datoteka  
- Ne pokretati instalaciju bez svih BIN datoteka  

---

### 4. Pokretanje instalacije

Pokrenuti:

KemDigSl_Setup.exe  

Preporučeno pokretanje kao administrator.

Zadana instalacijska lokacija:

C:\Program Files (x86)\KemDigSl  

Desktop prečac se automatski kreira.

---

## Pokretanje aplikacije

Aplikacija se pokreće putem:

- desktop prečaca  
ili  
- Project.exe iz instalacijskog direktorija  

Osnovni workflow:

učitaj sliku → odaberi modul → pokreni obradu → spremi rezultat  

---

## Performanse

- Obrada može trajati dulje bez GPU-a, posebno za:
  - CodeFormer  
  - DDColor  
  - LaMa  

- Vrijeme obrade ovisi o rezoluciji slike i snazi računala  

---

## Ograničenja

- Kvaliteta rezultata ovisi o ulaznoj slici  
- Visoke vrijednosti parametara mogu uzrokovati artefakte  
- LaMa koristi OpenCV fallback ako ovisnosti nisu dostupne  

---

## Deinstalacija

Dostupno putem:

- Windows Apps / Programs  
ili  
- Uninstall.exe u instalacijskom direktoriju  

---

## Tehnologije

- C# WinForms  
- Embedded Python Runtime  
- Real-ESRGAN  
- GFPGAN  
- CodeFormer  
- DDColor  
- YOLOv8n  
- AnimeGANv2  
- LaMa  

---

## Licenca

Academic / Research use  
