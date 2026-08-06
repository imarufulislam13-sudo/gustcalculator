# Civil Engineering Calculators

A collection of free, web-based civil engineering calculators for students, engineers, and construction professionals. All calculators are mobile-friendly and designed to be used directly in your browser.

## 🌐 Live Demo

Visit the main website: [Civil Engineering Fundamentals](https://cefundamentals.blogspot.com/)

## 📁 Project Structure

```
├── index.html                          # Main landing page with calculator categories
├── calculator.html                     # Gust Effect Factor Calculator (ASCE 7-05 & BNBC 2020)
├── gust-effect/                        # Gust effect calculator directory
│   └── index.html                      # Redirect to main calculator
├── BNBC_2020_Base_Shear_Calculator/    # Seismic base shear calculator
│   └── index.html                      # BNBC 2020 seismic calculator
└── README.md                           # This file
```

## 🧮 Available Calculators

### ✅ Currently Available

| Calculator | Standard | Description |
|------------|----------|-------------|
| **Gust Effect Factor** | ASCE 7-05, BNBC 2020 | Calculate gust effect factor for flexible or dynamically sensitive structures |
| **Seismic Base Shear** | BNBC 2020 | Equivalent static base shear calculation following response-spectrum procedure |

### 🚧 Coming Soon

| Category | Planned Calculators |
|----------|---------------------|
| **Concrete** | Concrete volume, Cement-sand-aggregate quantity, Water-cement ratio |
| **RCC Design** | Beam reinforcement, Slab reinforcement, Development length |
| **Steel Design** | Tension member capacity, Compression member checks, Bolt and weld calculations |
| **Geotechnical** | Allowable bearing capacity, Earth pressure, Soil unit-weight conversion |
| **Surveying** | Rise and fall, Bearing conversion, Coordinate distance |
| **Unit Converter** | Force and stress, Length and area, Moment and pressure |

## 🚀 Usage

### Gust Effect Factor Calculator

Access the calculator at: `calculator.html`

**Input Parameters:**
- Time Period, T (sec)
- Wind Speed, V (mph)
- Exposure Category (B, C, or D)
- Building Width, B (ft)
- Building Length, L (ft)
- Roof Height, h (ft)
- Damping Ratio, β (%)

**Output:**
- Natural frequency (n₁)
- Peak factors (gQ, gv, gR)
- Turbulence intensity (Iz)
- Background response (Q)
- Resonant response (R)
- **Gust Effect Factor (Gf)**

### Seismic Base Shear Calculator

Access the calculator at: `BNBC_2020_Base_Shear_Calculator/index.html`

**Input Parameters:**
- Seismic Zone (I, II, III, IV)
- Site Class (SA, SB, SC, SD, SE)
- Importance Class
- Structural System Type
- Building dimensions and weight

**Output:**
- Design spectral acceleration
- Response modification factor
- Fundamental period
- **Base shear coefficient**
- **Design base shear**

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, Flexbox, and Grid
- **JavaScript (Vanilla)** - Client-side calculations (no framework dependencies)
- **Responsive Design** - Mobile-first approach

## 🎨 Features

- **Free to Use** - No registration or payment required
- **Mobile-Friendly** - Responsive design works on all devices
- **Print-Ready** - Save calculations as PDF for documentation
- **Real-time Calculation** - Instant results as you input values
- **Error Validation** - Input validation with helpful error messages
- **Professional Output** - Clean, formatted results suitable for reports

## 📋 Standards Compliance

The calculators follow these engineering standards:

- **ASCE 7-05** - Minimum Design Loads for Buildings and Other Structures
- **BNBC 2020** - Bangladesh National Building Code

## 🔧 Local Development

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Open `index.html` in any modern web browser

3. No build process or server required - files work directly from the filesystem

## 📄 License

This project is provided free for educational and professional use.

## ⚠️ Disclaimer

These calculators are provided for educational and preliminary design purposes only. Always verify calculations and consult relevant codes, standards, and qualified professionals before using results for actual construction or engineering projects. The authors assume no liability for errors or misuse.

## 🤝 Contributing

Contributions are welcome! Feel free to suggest new calculators or improvements to existing tools.

## 📧 Contact

For questions or suggestions, visit [Civil Engineering Fundamentals](https://cefundamentals.blogspot.com/).

---

© 2026 Civil Engineering Fundamentals
