🎨 KemDigSl – Kemijanje Digitalnih Slika

AI-powered desktop aplikacija za obradu i restauraciju slika
WinForms (C#) + Python AI moduli

📦 Installer (ISO)

👉 https://drive.google.com/file/d/1oJKFBEfaBDwAcUWUaX_gluE-aMb-Rz5k/view?usp=sharing

🖼️ Preview

🤖 AI Moduli

KemDigSl integrira više naprednih AI modela u jedinstveno sučelje:

Real-ESRGAN → upscale / downscale
GFPGAN → obnova lica
CodeFormer → restauracija lica
DDColor → kolorizacija
AdaIN → style transfer
YOLOv8n → detekcija objekata
AnimeGANv2 → cartoonify efekt
LaMa → uklanjanje objekata / ogrebotina
AutoFix → automatska optimizacija slike
🎛️ Klasične transformacije
brightness
contrast
saturation
sharpness
grayscale
sepia

💻 System Requirements
Windows 10 / 11 (64-bit)
Preporučeno: 16 GB RAM
GPU nije obavezan (ali ubrzava obradu)
Dovoljno slobodnog prostora za modele i runtime
⚙️ Installation

Instalacija se sastoji od 2 dijela:

Setup (.exe)
BIN datoteke (modeli i runtime)
🥇 Step 1 – Download Setup

Preuzmi iz repozitorija:

KemDigSl_Setup.exe

🥈 Step 2 – Download BIN Files

Idi na:

Releases → Latest Release → Assets

Preuzmi:

KemDigSl_Setup_Quick-1.bin
KemDigSl_Setup_Quick-2.bin
KemDigSl_Setup_Quick-3.bin
KemDigSl_Setup_Quick-4.bin
KemDigSl_Setup_Quick-5.bin

🥉 Step 3 – Place Files Together

Sve datoteke moraju biti u ISTOM folderu:

KemDigSl_Setup.exe
KemDigSl_Setup_Quick-1.bin
KemDigSl_Setup_Quick-2.bin
KemDigSl_Setup_Quick-3.bin
KemDigSl_Setup_Quick-4.bin
KemDigSl_Setup_Quick-5.bin

⚠️ Bitno:

Ne mijenjati nazive datoteka
Ne pokretati instalaciju bez svih .bin datoteka

🚀 Step 4 – Run Installer

Pokreni:

KemDigSl_Setup.exe

👉 Preporučeno: Run as Administrator

Default instalacija:

C:\Program Files (x86)\KemDigSl

✔ Desktop shortcut se automatski kreira

▶️ First Launch

Pokreni aplikaciju:

preko Desktop shortcuta
ili direktno: Project.exe
Workflow:

Učitaj sliku → odaberi modul → pokreni obradu → spremi rezultat

⚡ Performance Notes
CPU obrada može biti sporija kod:
CodeFormer
DDColor
LaMa
Vrijeme obrade ovisi o:
rezoluciji slike
snazi hardwarea

👉 Za ozbiljniji rad preporuča se jači PC / GPU

⚠️ Known Limitations
Kvaliteta rezultata ovisi o ulaznoj slici
Agresivni parametri mogu uzrokovati artefakte
LaMa može koristiti OpenCV fallback ako ovisnosti nisu dostupne
🗑️ Uninstall

Deinstalacija dostupna putem:

Windows Apps / Programs
ili Uninstall.exe
🧠 Tech Stack
C# WinForms
Embedded Python Runtime
Real-ESRGAN
GFPGAN
CodeFormer
DDColor
YOLOv8n
AnimeGANv2
LaMa
📜 License

Academic / Research use
