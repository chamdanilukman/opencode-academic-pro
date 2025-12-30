# OpenCode Academic Pro 

Koleksi agent dan skill OpenCode yang dioptimalkan untuk penulis akademik: jurnal ilmiah, artikel, tesis, dan disertasi.

##  Fitur Utama

-  **6 Agent Spesialis Akademik** - Asisten AI untuk berbagai kebutuhan penulisan ilmiah
-  **3 Skill Workflow** - Panduan sistematis penulisan akademik
-  **Multi-Citation Style** - APA, IEEE, Harvard, Vancouver, Chicago
-  **Research Methodology** - Kuantitatif, Kualitatif, Mixed Methods
-  **Literature Review** - Systematic Review, Meta-Analysis, PRISMA

---

##  Daftar Agent

### 1. Journal Writer (`@journal-writer`)
Pakar penulisan jurnal ilmiah dengan struktur IMRaD (Introduction, Methods, Results, and Discussion).

**Keahlian:**
- Struktur artikel ilmiah standar internasional
- Penulisan abstrak efektif
- Formulasi research gap dan novelty
- Penyusunan literature review
- Format sitasi berbagai style

**Contoh penggunaan:**
```
@journal-writer bantu tulis introduction untuk penelitian tentang pengaruh social media terhadap produktivitas kerja
```

---

### 2. Thesis Advisor (`@thesis-advisor`)
Pembimbing virtual untuk mahasiswa S2/S3 yang sedang menyusun tesis atau disertasi.

**Keahlian:**
- Penyusunan proposal penelitian
- Struktur BAB I-V
- Perumusan masalah dan hipotesis
- Kerangka teoritis dan konseptual
- Review dan feedback konstruktif

**Contoh penggunaan:**
```
@thesis-advisor review BAB II tinjauan pustaka saya, apakah sudah cukup komprehensif?
```

---

### 3. Literature Reviewer (`@literature-reviewer`)
Pakar systematic literature review dan meta-analysis.

**Keahlian:**
- Systematic Literature Review (SLR)
- Scoping Review
- Meta-Analysis
- PRISMA Guidelines
- Bibliometric Analysis

**Contoh penggunaan:**
```
@literature-reviewer bantu buat search strategy untuk SLR tentang digital transformation in education
```

---

### 4. Academic Editor (`@academic-editor`)
Editor profesional untuk naskah akademik.

**Keahlian:**
- Proofreading (typo, grammar, punctuation)
- Copy editing (clarity, conciseness)
- Substantive editing (logic, flow)
- Format editing (journal guidelines)

**Contoh penggunaan:**
```
@academic-editor tolong review dan perbaiki paragraf discussion ini
```

---

### 5. Citation Manager (`@citation-manager`)
Pakar manajemen referensi dan sitasi.

**Format yang didukung:**
- APA 7th Edition
- IEEE
- Harvard
- Vancouver
- Chicago (Author-Date)

**Contoh penggunaan:**
```
@citation-manager konversi referensi berikut ke format APA 7th:
Smith, John. 2023. "AI in Education". Journal of Technology. Vol 10, pp 1-15.
```

---

### 6. Research Methodologist (`@research-methodologist`)
Pakar desain dan metodologi penelitian.

**Keahlian:**
- Desain penelitian (experimental, survey, case study)
- Sampling techniques
- Analisis data (SPSS, R, NVivo)
- Validity & reliability
- Sample size calculation

**Contoh penggunaan:**
```
@research-methodologist bantu tentukan metode sampling yang tepat untuk penelitian dengan populasi 500 mahasiswa
```

---

##  Skill Workflows

### 1. Academic Writing (`academic-writing`)
Panduan sistematis menulis artikel jurnal dari awal hingga submission.

### 2. Thesis Writing (`thesis-writing`)
Workflow lengkap penulisan tesis/disertasi BAB I-V.

### 3. Literature Review (`literature-review`)
Step-by-step melakukan systematic literature review.

---

##  Instalasi

### Metode 1: Clone ke Global Config
```bash
git clone https://github.com/YOUR_USERNAME/opencode-academic-pro ~/.config/opencode-academic-pro

# Copy agent dan skill ke opencode config
cp -r ~/.config/opencode-academic-pro/agent/* ~/.config/opencode/agent/
cp -r ~/.config/opencode-academic-pro/skill/* ~/.config/opencode/skill/
```

### Metode 2: Clone ke Project Lokal
```bash
git clone https://github.com/YOUR_USERNAME/opencode-academic-pro .opencode-academic

# Copy ke folder .opencode project
cp -r .opencode-academic/agent/* .opencode/agent/
cp -r .opencode-academic/skill/* .opencode/skill/
```

### Windows (PowerShell)
```powershell
git clone https://github.com/YOUR_USERNAME/opencode-academic-pro $env:USERPROFILE\.config\opencode-academic-pro

# Copy agent dan skill
Copy-Item -Recurse "$env:USERPROFILE\.config\opencode-academic-pro\agent\*" "$env:USERPROFILE\.config\opencode\agent\"
Copy-Item -Recurse "$env:USERPROFILE\.config\opencode-academic-pro\skill\*" "$env:USERPROFILE\.config\opencode\skill\"
```

---

##  Konfigurasi

Tambahkan agent ke `oh-my-opencode.json`:

```json
{
  "agents": {
    "journal-writer": {
      "model": "opencode/glm-4.7"
    },
    "thesis-advisor": {
      "model": "opencode/glm-4.7"
    },
    "literature-reviewer": {
      "model": "opencode/glm-4.7"
    },
    "academic-editor": {
      "model": "opencode/glm-4.7"
    },
    "citation-manager": {
      "model": "opencode/glm-4.7"
    },
    "research-methodologist": {
      "model": "opencode/glm-4.7"
    }
  }
}
```

---

##  Panduan Penggunaan

### Menulis Jurnal Ilmiah

1. **Persiapan**
   ```
   @journal-writer apa saja yang perlu disiapkan sebelum menulis artikel untuk jurnal Scopus Q2?
   ```

2. **Menulis Abstract**
   ```
   @journal-writer bantu tulis abstract untuk penelitian dengan judul "..."
   ```

3. **Review & Edit**
   ```
   @academic-editor review artikel saya, fokus pada grammar dan academic tone
   ```

4. **Format Sitasi**
   ```
   @citation-manager format semua referensi ke APA 7th edition
   ```

### Menulis Tesis/Disertasi

1. **Proposal**
   ```
   @thesis-advisor bantu susun outline proposal penelitian tentang "..."
   ```

2. **Literature Review**
   ```
   @literature-reviewer bantu identifikasi research gap dari 10 artikel berikut
   ```

3. **Metodologi**
   ```
   @research-methodologist apakah desain penelitian saya sudah tepat untuk menjawab research questions?
   ```

---

##  Tips & Best Practices

### Untuk Jurnal Internasional
- Selalu baca author guidelines target journal
- Gunakan `@journal-writer` untuk struktur IMRaD
- Minta `@academic-editor` review sebelum submit
- Pastikan sitasi konsisten dengan `@citation-manager`

### Untuk Tesis/Disertasi
- Mulai dengan `@thesis-advisor` untuk outline
- Gunakan `@literature-reviewer` untuk BAB II
- Konsultasi `@research-methodologist` untuk BAB III
- Final review dengan `@academic-editor`

---

##  Kontribusi

Kontribusi sangat diterima! Silakan:
1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/agent-baru`)
3. Commit perubahan (`git commit -m 'Tambah agent baru'`)
4. Push ke branch (`git push origin feature/agent-baru`)
5. Buat Pull Request

---

##  Lisensi

MIT License - Bebas digunakan dan dimodifikasi.

---

##  Author

**[Your Name]**
- GitHub: [@your_username](https://github.com/your_username)

---

##  Acknowledgments

- [OpenCode](https://opencode.ai/) - The open source coding agent
- [Oh My OpenCode](https://github.com/code-yeongyu/oh-my-opencode) - Plugin framework
- Komunitas akademik Indonesia
