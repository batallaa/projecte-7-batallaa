# T07: Migrant al núvol

**Autors:**  
Pol Castaño  
Biel Batalla  

**Data:** 20/04/2024  
**Curs:** SMX 2B  

---

## 1. Anàlisi de solucions

### 1.1 Comparativa de solucions

Actualment, el mercat ofereix diverses plataformes de correu corporatiu al núvol orientades a PIMES. S’han analitzat les següents opcions:

- **[Microsoft 365](https://www.microsoft.com/microsoft-365/business)**  
  Solució molt completa que inclou correu (Outlook), OneDrive, Teams i aplicacions ofimàtiques. Molt estesa però amb un cost elevat.

- **[Google Workspace](https://workspace.google.com/intl/ca/)**  
  Plataforma al núvol amb Gmail, Drive, Meet i Docs. Molt intuïtiva i orientada al treball col·laboratiu.

- **[Zoho Workplace](https://www.zoho.com/workplace/)**  
  Alternativa més econòmica amb correu, ofimàtica i eines de col·laboració. Bona relació qualitat-preu.

- **[Lark](https://www.zoho.com/workplace/)**  
  Plataforma integrada amb xat, videotrucades i documents, enfocada a la comunicació interna.

![Captura 1](/Tasques/T07/img/i1.png)

---

### 1.2 Taula comparativa

| Proveïdor | Preu €/usuari/mes | Cost anual (35 usuaris) | Emmagatzematge | Seguretat | Eines col·laboratives |
|---------|------------------|------------------------|---------------|-----------|----------------------|
| Microsoft 365 Business Standard | ~11,5 € | ~4.830 € | 50 GB correu + 1 TB núvol | MFA, antispam, protecció avançada | Teams, Office, OneDrive |
| Google Workspace Business Standard | ~12 € | ~5.040 € | 2 TB compartits | MFA, detecció d’amenaces | Meet, Drive, Docs |
| Zoho Workplace Professional | ~5,5 € | ~2.310 € | 100 GB correu + núvol ampliable | MFA, SSO, xifrat | Writer, Cliq, WorkDrive |
| Lark Pro | ~11 € | ~4.620 € | 1 TB compartit | MFA, control d’accés | Docs, xat, videotrucades |

![Captura 2](/Tasques/T07/img/i2.png)

---

## 2. Justificació tècnica

Després de l’anàlisi, es recomana implementar **[Zoho Workplace](ttps://www.zoho.com/workplace/)** com a solució principal pels següents motius:

- **Cost molt competitiu:** pràcticament la meitat que Microsoft o Google.
- **Alta capacitat de correu:** fins a 100 GB per usuari, superior a altres opcions.
- **Seguretat robusta:**
  - Autenticació multifactor (MFA)
  - Xifrat de dades
  - SSO (Single Sign-On)
  - Eines d’auditoria i *eDiscovery*
- **Ecosistema complet:** inclou correu, calendari, emmagatzematge i eines ofimàtiques sense necessitat de software addicional.
- **Escalabilitat:** fàcil creixement si l’empresa augmenta la plantilla.

A més, cobreix perfectament la necessitat de substituir el servei actual, aportant una millora en seguretat, comunicació i col·laboració interna.

---

## 3. Càlcul de costos i implantació

### 3.1 Cost de llicències

| Concepte | Valor |
|--------|-------|
| Usuaris | 35 |
| Cost per usuari/mes | 5,5 € |
| Cost mensual total | 192,5 € |
| Cost anual total | 2.310 € |

---

### 3.2 Costos recurrents

- Subscripció anual: **2.310 €**
- Costos addicionals opcionals:
  - Emmagatzematge extra
  - Suport tècnic avançat

---

### 3.3 Migració del correu

Per a la migració es poden utilitzar eines oficials com:

- **[Zoho Migration Tool](https://www.zoho.com/mail/migration/)** (IMAP / Exchange)
- Assistents de migració automatitzats

Aquestes eines permeten:

- Migrar correus, contactes i calendaris
- Minimitzar el temps d’aturada
- Fer la transició de manera transparent pels usuaris

---

## 4. Conclusió

La migració al núvol amb **[Zoho Workplace](ttps://www.zoho.com/workplace/)e** permet a **FoodLogistic**:

- Reduir costos operatius
- Millorar la seguretat del correu
- Incorporar eines modernes de treball col·laboratiu
- Eliminar la dependència d’un hosting antiquat

És una solució equilibrada, escalable i econòmica, ideal per a una empresa de **35 treballadors**.

![Captura 3](/Tasques/T07/img/i3.png)
