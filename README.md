# Capacity Calculator IKC

**Interactive Capacity Planning Tool** for August - December 2026

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)

## 📊 Overview

A professional capacity planning calculator designed to help teams manage production capacity across multiple product families with different conversion factors. This tool enables real-time capacity visualization and demand planning.

## 🎯 Features

✅ **Interactive Dashboard** - Real-time capacity visualization with dynamic charts
✅ **Multi-Program Support** - Game, Legend, MLB, NBA, XC2
✅ **Conversion Factors** - Each program has unique production ratios
✅ **Automatic Calculations** - Standard capacity consumption computed in real-time
✅ **Visual Alerts** - Green (OK), Yellow (Warning), Red (Over Capacity)
✅ **Excel Export** - Download reports for sharing and archiving
✅ **Responsive Design** - Works on desktop, tablet, and mobile

## 📦 Available Capacity by Month

| Month | Standard Units |
|-------|----------------|
| August | 9,906 |
| September | 152,384 |
| October | 248,234 |
| November | 222,844 |
| December | 185,964 |
| **TOTAL** | **819,332** |

## 🔄 Conversion Factors by Program

| Program | Factor | Impact |
|---------|--------|--------|
| Game | 0.63x | Fewer units than standard |
| Legend | 1.73x | More units than standard |
| MLB | 0.69x | Fewer units than standard |
| NBA | 0.82x | Fewer units than standard |
| XC2 | 0.32x | Significantly fewer units |

## 🚀 Quick Start

### Option 1: Use the Online Dashboard (Recommended)
Simply open the dashboard in your browser - no installation needed:
```
https://menesesbarrera.github.io/Capacity-Calculator/dashboard_en.html
```

### Option 2: Use the Excel Template
Download `Capacity_Calculator_IKC_Full.xlsx` for offline calculations with built-in formulas and charts.

## 📖 How to Use

### Dashboard Steps:
1. **Review Available Capacity** - Check how many standard units you have each month
2. **Check Factors** - Understand how each program scales the available capacity
3. **Enter Demand** - Input units you want to produce per program per month (YELLOW CELLS)
4. **Monitor Charts** - Watch capacity utilization update in real-time
5. **Check Status** - See if you're within limits (Green = OK, Yellow = Warning, Red = Over Capacity)
6. **Download Report** - Export your planning to Excel for team sharing

### Key Concepts:

**Standard Capacity**: The reference unit of capacity (Factor = 1.0)
- This is your absolute capacity limit per month

**Conversion Factor**: How each program scales the standard capacity
- **Factor > 1** (Legend 1.73): You can produce MORE units
- **Factor < 1** (Game 0.63): You can produce FEWER units

**Standard Capacity Consumed**: Amount of standard capacity used by your demand
- Formula: Demand ÷ Conversion Factor
- Example: 10,000 Legend units ÷ 1.73 = 5,780 standard units consumed

**Utilization %**: What percentage of your monthly capacity you're using
- < 80% = Green ✓ OK
- 80-100% = Yellow ⚠️ Warning
- > 100% = Red 🚫 Over Capacity

## 📊 Understanding the Charts

### Chart 1: Available vs Consumed Capacity
- **Blue bars**: Available standard capacity
- **Green bars**: Consumed standard capacity by your demand
- Shows how much capacity remains each month

### Chart 2: Demand by Program
- Stacked bars showing contribution of each program
- See which programs consume the most capacity
- Helps identify optimization opportunities

## 💾 Files

- **dashboard_en.html** - Interactive web dashboard with real-time calculations
- **Capacity_Calculator_IKC_Full.xlsx** - Excel template with formulas, tutorial, and charts
- **README.md** - This documentation file

## 🎓 Example Scenario

**August Capacity**: 9,906 standard units

If you demand:
- 5,000 Game units (factor 0.63): Consumes 5,000 ÷ 0.63 = 7,937 standard units
- 3,000 Legend units (factor 1.73): Consumes 3,000 ÷ 1.73 = 1,734 standard units
- **Total consumed**: 7,937 + 1,734 = 9,671 standard units
- **Remaining**: 9,906 - 9,671 = 235 standard units
- **Utilization**: 9,671 ÷ 9,906 = 97.6% (⚠️ WARNING - very close to capacity!)

## 📝 Best Practices

✅ **Review capacity before planning** - Know your limits
✅ **Use factors strategically** - Mix programs with different factors
✅ **Monitor warnings** - When utilization > 80%, start reviewing alternatives
✅ **Plan ahead** - Use multiple months for better resource distribution
✅ **Export regularly** - Keep records of your planning decisions
✅ **Adjust as needed** - If over capacity, reduce demand for some programs

## 🔧 Technical Details

- **Built with**: HTML5, Chart.js, JavaScript, Excel
- **Browser Support**: Chrome, Firefox, Safari, Edge (latest versions)
- **No installation required** - Works directly in browser
- **Offline capable** - Excel version works without internet

## 📧 Support

For questions or issues with the calculator:
1. Check the tutorial at the top of the dashboard
2. Review the Excel template for detailed explanations
3. Verify your factor values match the specification

## 📄 License

MIT License - Feel free to use and modify as needed

---

**Last Updated**: April 2026
**Version**: 1.0
**Status**: Production Ready

---

**Pro Tips:**
- 💡 Use the Excel version for detailed analysis and record-keeping
- 💡 Use the Dashboard for quick planning and team presentations
- 💡 Export your plans weekly to track changes over time
- 💡 Share the public dashboard link with your team - no login required!

