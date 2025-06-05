# Google Dork Report

## Target 1: tesla.com

### 1. Public Documents
**Dork Used**: `site:tesla.com filetype:pdf`  
- [Model 3 Owner's Manual](https://www.tesla.com/ownersmanual/model3/en_hk/Owners_Manual.pdf)
- [Model Y Owner's Manual](https://www.tesla.com/ownersmanual/modely/en_hk/Owners_Manual.pdf)

### 2. Login/Admin Pages  
**Dork Used**: `site:tesla.com inurl:login`  
- [Feedback Portal Login](https://feedback.tesla.com/login/identity-provider-select?stateID=...)
- [Solar Bonds Login](https://solarbonds.tesla.com/a/login/)

### 3. Backup / Config Files  
**Dork Used**: `site:tesla.com inurl:backup
site:tesla.com filetype:env
site:tesla.com inurl:config` 
**Examples**:
- No results found 

### 4. Logs / Errors  
**Dork Used**: `intitle:"index of" logs site:tesla.com`  
- No results

### 5. Emails & Contact Info

**Dork Used**: `site:tesla.com "@tesla.com"`  
**Emails**:
- `accommodationrequest@tesla.com` 
- `philippines@tesla.com` 
- `press@tesla.com`

**Dork Used**: `site:tesla.com intitle:"contact"`  
**Examples**:
- [Tesla PH Contact Page](https://www.tesla.com/en_ph/contact)
- [Tesla Insurance Contact](https://www.tesla.com/support/insurance/contact-tesla-insurance)
- [Tesla UK Contact Page](https://www.tesla.com/en_gb/contact)

### 6. Git / Env Files  
**Dork Used**: `site:tesla.com inurl:.git`  

- No results found

---

## Target 2: nitt.edu

### 1. Public Documents

**Dork Used**: `site:nitt.edu filetype:pdf`  

- (https://nitt.edu/home/EEE_ATAL_FDP_2021.pdf)
- (https://nitt.edu/home/CHL_GIAN_ABBR_2025_v2.pdf)
- (https://nitt.edu/home/CA_IoT_Essentials_Jun_2025.pdf)

### 2. Login / Admin Pages

**Dork Used**: `site:nitt.edu inurl:login`   `site:nitt.edu inurl:admin`  
**Examples**:
- https://webmail.nitt.edu/horde/login.php
- https://scholarship.nitt.edu/auth/admin/login
- https://webmail.nitt.edu/mailman/admin/bwc- 

### 3. Public Backup/ Config files

**Dork Used**: `site:nitt.edu inurl:backup`  
- http://vr360.nitt.edu/dashboard/docs/backup-restore-mysql.html


### 4. Exposed Logs / Errors

**Dork Used**: `site:nitt.edu inurl:error`  
- https://sports.nitt.edu/dwd/1956-dime-error
- https://sports.nitt.edu/dwd/bedpage-dallas-error-500

**Observation**:
- These pages contain the word “error” in their URL path.
- When visited, they remain stuck loading with no response a blank page.

### 5. Emails & Contact Info

**Dork Used**: `site:nitt.edu "@nitt.edu"`  
- `ug@nitt.edu` – Undergraduate admissions
- `pg@nitt.edu` – Postgraduate admissions

**Dork Used**: `site:nitt.edu intitle:"contact"`  
- https://www.nitt.edu/contact
- https://www.nitt.edu/home/students/facilitiesnservices/ComputerSupportGroup/contact%20address/
Admission contact
- +91-431-2503931 (B.Tech / B.Arch.)
- +91-431-2504940 (PG Programs – M.Tech / MBA / etc.)

### 6. Git / Config-Related Files

**Dork Used**: `site:nitt.edu inurl:git`  
- http://vr360.nitt.edu/dashboard/docs/deploy-git-app.html


---

## Target 3: nasa.gov

### 1.Public Documents

**Dork Used**: `site:nasa.gov filetype:pdf`  

- https://mars.nasa.gov/internal_resources/1489/
- https://mars.nasa.gov/internal_resources/824/
- https://mars.nasa.gov/internal_resources/815/

### 2.Login/Admin Pages

**Dork Used**: `site:nasa.gov inurl:login`  

- https://stemgateway.nasa.gov/public/s/login
- https://www.earthdata.nasa.gov/data/earthdata-login
- https://www.jpl.nasa.gov/site/NSET/accounts/login/

### 3. Public Backup/ Config files
**Dork Used**: `site:nasa.gov inurl:config OR inurl:backup`  

- http://heasarc.gsfc.nasa.gov/FTP/caldb/software/tools/caldb.config
- https://cmr.earthdata.nasa.gov/service-bridge/docs/current/reference/cmr.opendap.testing.config.html
- https://git.earthdata.nasa.gov/.../config.json
- https://vso1.nascom.nasa.gov/data/psp.backup/

### 4. Exposed Logs / Errors

**Dork Used**: `site:nasa.gov inurl:error`  

- https://wwwastro.msfc.nasa.gov/qdp/help/error.html
- https://spdf.gsfc.nasa.gov/.../java.lang.Error.html

### 5. Emails & Contact Info
**Dork Used**: `site:nasa.gov intitle:"contact"`  

- https://www.nasa.gov/contact/
- https://www3.nasa.gov/help/contact/index.html
- https://www.nasa.gov/srb-retrieval-ships-recordation/contact/

### 6. Git / Config-Related Files
**Dork Used**: `site:nasa.gov inurl:git`  

- https://git.smce.nasa.gov/cicci/python
- https://git.earthdata.nasa.gov/.../dacqre/commits/...
- https://git.earthdata.nasa.gov/.../daac2disk-cli-py/browse
- https://git.earthdata.nasa.gov/.../hello-world/browse

---


