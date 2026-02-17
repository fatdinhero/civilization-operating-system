# 🕌 Civilization Operating System (COS)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18672231.svg)](https://doi.org/10.5281/zenodo.18672231)

**Bismillah ir-Rahman ir-Rahim**

The world's first open-source Sharia-compliant operating system backend for Islamic finance.

## ✨ Features

- ✅ **Riba Detection Algorithm** - Real-time interest detection
- ✅ **Zakāt Auto-Calculator** - 2.5% calculation above Nisab (595g silver)
- ✅ **Halal/Haram Validator** - Multi-category compliance
- ✅ **4 Madhahib Support** - Hanafi, Shafi'i, Maliki, Hanbali

## 🚀 Quick Start
```bash
npm install
npm test
```

## 🧪 How It Works
```typescript
// Mudaraba (HALAL)
detectRiba({
    profit_loss_sharing: true,
    guaranteed_return: false,
    time_based_interest: false,
    risk_distribution: 'symmetric'
}) // → false (HALAL!)

// Bank Loan (HARAM)
detectRiba({
    guaranteed_return: true,
    time_based_interest: true
}) // → true (RIBA!)
```

## 💰 Dual Licensing

- **Open Source** (Free): Educational, research, non-profit
- **Commercial License**: For banks & enterprises

Contact: chrsdyor@gmail.com

## 📜 License

Islamic Open Source License (IOSL) v1.0

## 🤲 Sadaqah Jariyah

Developed as ongoing charity for the Ummah.

**"The best of people are those who benefit others most"** - Prophet Muhammad (ﷺ)

---

**Author**: Fatih Dinc  
**Email**: chrsdyor@gmail.com 
**DOI**:[10.5281/zenodo.18672231](https://doi.org/10.5281/zenodo.18672231)

🕌 **Alhamdulillah**
