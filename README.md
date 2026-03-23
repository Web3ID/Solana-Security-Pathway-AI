# Ultimate Solana Security + AI Roadmap (2026 Edition)

> "If I were starting my long journey in web3 security all over again — this is exactly the path I would take."  
> — @0xcastle_chain (Rust/Solana Auditor, +60 audits, +300 critical/high findings)

Fokus: 4 skill paling dicari & dibayar tinggi di blockchain saat ini ($200K–$500K+ level):  
**Rust → Solana Development → AI-assisted Building → Smart Contract Security**

Total estimasi: ~6 bulan dari nol (dengan konsistensi tinggi) hingga bisa compete/earn.

## Mengapa urutan ini?
- Rust adalah fondasi → skip = struggle selamanya  
- Solana punya model unik (bukan EVM) → demand lagi meledak  
- AI = multiplier kecepatan & coverage  
- Security = endgame (bayaran tertinggi + paling langka)

Jangan skip fase yang terasa susah. Build project di setiap fase. Dokumentasikan progress (thread, blog, repo) → jadi portfolio.

## Phase 1: Rust (4–6 minggu)

**Goal**: Bisa baca & paham kode Rust orang lain, kuasai ownership/borrowing di level gut feeling.

### Resources Utama
- Bogdan's Rust Course (beginner-friendly, relevan on-chain)  
  https://www.youtube.com/playlist?list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8 (atau cari update terbaru)
- Intermediate Rust Playlist (iterators, lifetimes, trait objects)  
  https://www.youtube.com/playlist?list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8
- The Rust Book (wajib baca full, fokus ch. 4, 10, 15)  
  https://doc.rust-lang.org/book/
- RareCodeAI — interactive Rust challenges  
  https://rarecode.ai/
- Cyfrin Updraft / ProgrammerSmart Rust Course  
  (link terbaru biasanya di https://updraft.cyfrin.io/ atau cari di X)

### Milestone Exit
- Tulis CLI tool sederhana dari nol  
- Jelaskan ownership & borrowing tanpa ragu  
- Nyaman pakai `Result`, `Option`, traits, generics  
- Bisa baca & ikuti logic kode Rust orang lain

## Phase 2: Solana Development (4–8 minggu)

**Goal**: Paham model Solana (accounts, PDAs, CPIs, rent, dll) & bisa deploy program.

### Resources Utama
- Full Solana Developer Course by @HeyAndyS (Anchor + native, up-to-date)  
https://youtube.com/playlist?list=PLmAMfj0qP2wzU6UfZMoBvJq0bybXAjMdL&si=P1NdYBxoOGBAPoYF (cari update terbaru di channelnya)
- Jacob Creech long-form deep dive  
  (https://youtu.be/amAq-WHAFs8?si=wVvH4_BB8D3BO8AQ)
- RareSkills Solana for EVM devs (mapping Solidity → Solana)  
  https://rareskills.io/solana-tutorial
- S3v3ru5 beginner notes (konsep under-the-hood)    (https://s3v3ru5.github.io/posts/solana-beginner-notes/)
- Ackee Blockchain Solana School (architecture, testing, deployment)  
  https://youtube.com/playlist?list=PLzUrW5H8-hDdE-Ys5W5Gx2zrHpUTo1uXD&si=_kcHJjJzb4-ufSfm (cari Ackee Solana School)

### Milestone Exit
- Deploy program ke devnet pakai Anchor  
- Bisa jelaskan PDAs, CPIs, account model ke orang lain  
- Build app on-chain sederhana (escrow / vault / token program)  
- Tulis client-side code yang interact dengan programmu

## Phase 3: AI-assisted Building (2–3 minggu)

**Goal**: Pakai AI sebagai accelerator (bukan pengganti skill).

### Resources Utama
- Helius guide: Using AI to build Solana apps  
  https://www.helius.dev/blog/how-to-use-ai-to-build-solana-apps
- Solana Foundation awesome-solana-ai repo (tools, agents, resources)  
  https://github.com/solana-foundation/awesome-solana-ai
- Claude Skills untuk Solana (security-aware prompting) 
 1. https://github.com/Frankcastleauditor/safe-solana-builder
 2. https://github.com/exvulsec/exvul-solana-skill
 3. https://github.com/sanbir/solana-auditor-skills

### Milestone Exit
- Prompt LLM untuk scaffold program Solana + tahu bagian mana yang perlu diperbaiki  
- Generate test cases lebih banyak & bagus dari manual  
- Sudah integrasikan minimal 1 AI tool ke workflow harian  
- Lebih cepat pakai AI, tapi tetap bisa build tanpa AI (bisa verifikasi & fix sendiri)

## Phase 4: Smart Contract Security (ongoing, mulai compete setelah 3–4 bulan)

**Goal**: Bisa nemuin bug real di kode Anchor/native, tulis finding profesional.

### Resources Utama
- awesome-solana-security repo (vuln classes, tools, CTFs, blogs)  
  https://github.com/0xMacro/awesome-solana-security
- OtterSec public audit reports (high-quality Solana audits)  
  https://ottersec.notion.site/Sampled-Public-Audit-Reports-a296e98838aa4fdb8f3b192663400772
- Accretion audit reports (struktur finding bagus)  
  https://github.com/accretion-xyz/audit-reports
- Public audit reports dari @0xcastle_chain  
https://github.com/Frankcastleauditor/public-audits

- Solana Audit Arena (weekly contest audit real code, leaderboard)  
  https://github.com/Frankcastleauditor/Solana-Audit-Arena

### Common Solana Vuln Classes (pelajari & hafal)
- Missing signer checks  
- PDA seed collisions  
- CPI authority confusion  
- Arithmetic overflows  
- Token-2022 edge cases  
- Re-initialization attacks  
- dll (lihat awesome-solana-security untuk full list)

### Milestone Exit / Compete-ready
- Kenali minimal 5 vuln class Solana hanya dari lihat kode  
- Sudah baca 20+ audit report & paham finding-nya  
- Bisa review program Anchor kecil & tulis finding lengkap (root cause + impact + rekomendasi)  
- Pernah ikut minimal 1 contest (Cantina, Code4rena, atau Audit Arena)

## Final Advice dari Author
1. **Build project tiap fase** — jangan cuma nonton. Deploy ke devnet. Break things.  
2. **Contribute open-source** — PR kecil pun berharga.  
3. **Join komunitas** — Solana Discord, Superteam, security TG groups. Opportunity datang dari orang.  
4. **Dokumentasikan publicly** — threads, blogs, repos = portfolio terbaik.

Market masih sangat haus orang yang kuasai ke-4 skill ini sekaligus.  
Eksekusinya ada di tangan kamu. Good luck! 🏴


