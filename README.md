# OpenCode Academic Pro 

Koleksi agent dan skill OpenCode yang dioptimalkan untuk penulis akademik: jurnal ilmiah, artikel, tesis, dan disertasi.

##  Fitur Utama

-  **12 Agent Spesialis Akademik** - Asisten AI untuk penulisan dan olah data
-  **3 Skill Workflow** - Panduan sistematis penulisan akademik
-  **Multi-Citation Style** - APA, IEEE, Harvard, Vancouver, Chicago
-  **Research Methodology** - Kuantitatif, Kualitatif, Mixed Methods
-  **Data Analysis** - SPSS, R, SmartPLS, NVivo, Excel

---

##  Agent Penulisan Akademik

### 1. Journal Writer (`@journal-writer`)
Pakar penulisan jurnal ilmiah dengan struktur IMRaD.

```
@journal-writer bantu tulis introduction untuk penelitian tentang pengaruh social media terhadap produktivitas kerja
```

### 2. Thesis Advisor (`@thesis-advisor`)
Pembimbing virtual untuk mahasiswa S2/S3.

```
@thesis-advisor review BAB II tinjauan pustaka saya
```

### 3. Literature Reviewer (`@literature-reviewer`)
Pakar systematic literature review dan meta-analysis.

```
@literature-reviewer bantu buat search strategy untuk SLR tentang digital transformation
```

### 4. Academic Editor (`@academic-editor`)
Editor profesional untuk naskah akademik.

```
@academic-editor tolong review dan perbaiki paragraf discussion ini
```

### 5. Citation Manager (`@citation-manager`)
Pakar manajemen referensi (APA, IEEE, Harvard, Vancouver, Chicago).

```
@citation-manager konversi referensi berikut ke format APA 7th
```

### 6. Research Methodologist (`@research-methodologist`)
Pakar desain dan metodologi penelitian.

```
@research-methodologist bantu tentukan metode sampling yang tepat
```

---

##  Agent Olah Data Akademik

### 7. SPSS Analyst (`@spss-analyst`)
Pakar analisis data menggunakan SPSS.

**Keahlian:** T-Test, ANOVA, Regresi, Uji Instrumen, Path Analysis

```
@spss-analyst bagaimana cara uji normalitas dan homogenitas di SPSS?
```

### 8. R Statistician (`@r-statistician`)
Pakar analisis statistik menggunakan R.

**Keahlian:** tidyverse, lavaan (SEM), metafor (meta-analysis), ggplot2

```
@r-statistician bantu buat script R untuk CFA dengan lavaan
```

### 9. SmartPLS Expert (`@smartpls-expert`)
Pakar Structural Equation Modeling (SEM) dengan SmartPLS.

**Keahlian:** PLS-SEM, Measurement Model, Structural Model, Mediation, Moderation

```
@smartpls-expert bagaimana interpretasi hasil bootstrapping untuk mediasi?
```

### 10. NVivo Analyst (`@nvivo-analyst`)
Pakar analisis data kualitatif menggunakan NVivo.

**Keahlian:** Coding, Thematic Analysis, Query, Visualization

```
@nvivo-analyst bantu proses coding untuk analisis tematik
```

### 11. Excel Analyst (`@excel-analyst`)
Pakar pengolahan data akademik menggunakan Excel.

**Keahlian:** Pivot Table, Data Analysis ToolPak, Statistik Deskriptif

```
@excel-analyst bagaimana cara buat histogram dan uji korelasi di Excel?
```

### 12. Survey Designer (`@survey-designer`)
Pakar desain kuesioner dan survei penelitian.

**Keahlian:** Likert Scale, Validitas, Reliabilitas, Pilot Testing

```
@survey-designer review kuesioner saya, apakah sudah valid?
```

---

##  Skill Workflows

### 1. Academic Writing (`academic-writing`)
Panduan sistematis menulis artikel jurnal dari awal hingga submission.

### 2. Thesis Writing (`thesis-writing`)
Workflow lengkap penulisan tesis/disertasi BAB I-V.

### 3. Literature Review (`literature-review`)
Step-by-step melakukan systematic literature review dengan PRISMA.

---

##  Instalasi

### Windows (PowerShell)
```powershell
git clone https://github.com/chamdanilukman/opencode-academic-pro $env:USERPROFILE\.config\opencode-academic-pro

# Copy agent dan skill
Copy-Item -Recurse "$env:USERPROFILE\.config\opencode-academic-pro\agent\*" "$env:USERPROFILE\.config\opencode\agent\" -Force
Copy-Item -Recurse "$env:USERPROFILE\.config\opencode-academic-pro\skill\*" "$env:USERPROFILE\.config\opencode\skill\" -Force
Copy-Item "$env:USERPROFILE\.config\opencode-academic-pro\oh-my-opencode.example.json" "$env:USERPROFILE\.config\opencode\oh-my-opencode.json" -Force
```

### Linux/Mac
```bash
git clone https://github.com/chamdanilukman/opencode-academic-pro ~/.config/opencode-academic-pro

# Copy agent dan skill
cp -r ~/.config/opencode-academic-pro/agent/* ~/.config/opencode/agent/
cp -r ~/.config/opencode-academic-pro/skill/* ~/.config/opencode/skill/
cp ~/.config/opencode-academic-pro/oh-my-opencode.example.json ~/.config/opencode/oh-my-opencode.json
```

---

##  Workflow Penelitian

### 1. Persiapan
```
@research-methodologist bantu desain penelitian kuantitatif
@survey-designer buat kuesioner untuk variabel X, Y, Z
```

### 2. Pengumpulan Data
```
@survey-designer review validitas kuesioner
@excel-analyst bantu cleaning data
```

### 3. Analisis Data
```
@spss-analyst uji hipotesis dengan regresi berganda
@smartpls-expert analisis SEM untuk model penelitian
@nvivo-analyst coding data wawancara
```

### 4. Penulisan
```
@journal-writer tulis hasil dan pembahasan
@literature-reviewer susun tinjauan pustaka
@thesis-advisor review keseluruhan BAB
```

### 5. Finalisasi
```
@academic-editor proofreading naskah
@citation-manager format referensi APA 7th
```

---

##  Lisensi

MIT License - Bebas digunakan dan dimodifikasi.

##  Author

**Chamdani Lukman**
- GitHub: [@chamdanilukman](https://github.com/chamdanilukman)
