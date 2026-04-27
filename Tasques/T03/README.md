# 🗂️ T03: Servidor de fitxers

## 📝 Breu descripció

### 📌 Introducció
Quan el **volum de negoci** creix 📈, també ho fa el **volum de dades** 💾 i sovint aquí comencen els problemes.  
La informació es compartimenta, de manera que manca una **visió global** de la situació.

**FoodLogistic** no ha estat una excepció 🚚. Cada departament guardava la documentació de forma local.  
Per això, un dels requisits de l’encàrrec rebut és **solucionar aquest problema**.

🎯 **Objectiu**:  
Implementar una infraestructura de fitxers **segura 🔐**, **organitzada 📁** i amb **control d’espai 📏**, utilitzant:
- Permisos **NTFS / SMB**
- **Quotes**
- **Filtratge de fitxers (FSRM)**

Caldrà demostrar el domini de les **tres vies d’administració**:
- 🗃️ Explorador de fitxers  
- 🖥️ Server Manager  
- ⚙️ PowerShell  

---

## 📂 Descripció de l'activitat

L’activitat es divideix en **fites** que simulen un procés real de **consultoria i implementació** 🛠️.

---

## 1️⃣ Preparació i Seguretat de Grups (AD)

Abans de crear el servidor de fitxers, cal preparar l’**Active Directory**.

🌐 Domini: `foodlogistic.test`  
📁 Cal crear una **estructura d’OUs coherent**, que s’haurà de **justificar** segons les necessitats.

👥 **Grups de seguretat a crear**:
- **Administracio** 🧾 → Gestió de factures i albarans  
- **Transport** 🚛 → Xofers i caps de flota  
- **Direccio** 🏢 → Gerència  

---

## 2️⃣ Implementació de Recursos Compartits (3 mètodes)

Heu de crear les següents **estructures de carpetes** al servidor, cadascuna amb un **mètode diferent**:

---

### 🅰️ Carpeta **Public**  
**Mètode**: Explorador d’arxius 📁

- Compartida per a **tothom** 👥  
- Permisos:

