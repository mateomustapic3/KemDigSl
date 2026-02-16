# KemDigSl – Kemijanje Digitalnih Slika

AI-powered desktop aplikacija za obradu i restauraciju slika  
WinForms (C#) + Python AI moduli

---

## AI Moduli

KemDigSl integrira vise naprednih modela u jedinstveno sucelje:

- Real-ESRGAN → upscale / downscale
- GFPGAN → obnova lica
- CodeFormer → restauracija lica
- DDColor → kolorizacija
- AdaIN → style transfer
- YOLOv8n → detekcija objekata
- AnimeGANv2 → cartoonify
- LaMa → uklanjanje objekata / ogrebotina
- AutoFix → kombinirana automatska obrada

Uz to podrzane su i klasicne transformacije:

brightness • contrast • saturation • sharpness • grayscale • sepia

---

## System Requirements

- Windows 10 / 11 (64-bit)
- Preporuceno 16 GB RAM
- GPU nije obavezan (ali ubrzava AI obradu)
- Dovoljno slobodnog prostora za runtime i modele

---

## Installation

Instalacija zahtijeva:

- Setup EXE iz repozitorija
- BIN datoteke iz Releases sekcije

---

### Step 1 – Download Setup

Iz glavnog repozitorija preuzmi:

KemDigSl_Setup.exe

---

### Step 2 – Download BIN Files

Idi na:

Releases → Latest Release → Assets

Preuzmi:

KemDigSl_Setup-1.bin  
KemDigSl_Setup-2.bin  
KemDigSl_Setup-3.bin  
KemDigSl_Setup-4.bin  
KemDigSl_Setup-5.bin  
KemDigSl_Setup-6.bin  

---

### Step 3 – Place Together

Sve datoteke moraju biti u ISTOM folderu:

KemDigSl_Setup.exe  
KemDigSl_Setup-1.bin  
KemDigSl_Setup-2.bin  
KemDigSl_Setup-3.bin  
KemDigSl_Setup-4.bin  
KemDigSl_Setup-5.bin  
KemDigSl_Setup-6.bin  

Ne mijenjati nazive  
Ne pokretati instalaciju bez svih BIN datoteka

---

### Step 4 – Run Installer

Pokreni:

KemDigSl_Setup.exe

(preporuceno kao Administrator)

Zadana instalacija:

C:\Program Files (x86)\KemDigSl

Desktop shortcut se automatski kreira.

---

## First Launch

Pokreni aplikaciju preko:

Desktop → KemDigSl

ili

Project.exe iz instalacijskog foldera

Ucitaj sliku → odaberi modul → pokreni obradu → spremi rezultat

---

## Performance Notes

- CPU obrada moze trajati dulje kod:
  CodeFormer / DDColor / LaMa
- Vrijeme obrade ovisi o rezoluciji slike
- Za vece projekte preporucen je jaci hardware

---

## Known Limitations

- Rezultat ovisi o kvaliteti ulazne slike
- Agresivni parametri mogu stvoriti artefakte
- LaMa moze koristiti OpenCV fallback ako neka ovisnost nije dostupna

---

## Uninstall

Deinstalacija dostupna kroz:

Windows Apps / Programs

ili

Uninstall u instalacijskom folderu

---

## Tech Stack

C# WinForms  
Embedded Python Runtime  
Real-ESRGAN  
GFPGAN  
CodeFormer  
DDColor  
YOLOv8n  
AnimeGANv2  
LaMa

---

## License

Academic / Research use
