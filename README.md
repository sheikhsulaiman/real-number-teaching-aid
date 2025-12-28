# 📚 বাস্তব সংখ্যা - ইন্টারেক্টিভ শিক্ষা সহায়ক

# Real Numbers - Interactive Teaching Aid

An interactive educational web application designed for 9th-10th grade students to learn about real numbers, rational and irrational numbers, and mathematical proofs in Bengali.

## ✨ Features

### 📊 Interactive Number Line

- **Visual Plotting**: Plot numbers on an interactive number line
- **Number Types**: Support for both rational and irrational numbers
- **Preset Numbers**: Quick access to common numbers:
  - √2 (Square root of 2)
  - √3 (Square root of 3)
  - π (Pi)
  - 1/2, 3/4 (Fractions)
- **Custom Numbers**: Enter any custom number
- **Zoom Controls**: Zoom in/out to see numbers in detail (up to 5x zoom)
- **Color Coding**:
  - 🟢 Green badges for rational numbers
  - 🟠 Orange badges for irrational numbers
- **Real-time Information**: Displays number value, label, and type

### 🔬 Mathematical Proof

- **Step-by-step Proof**: Interactive proof that √2 is irrational
- **Navigation**: Move forward and backward through proof steps
- **Visual Indicators**: Progress dots show current step
- **Detailed Explanation**: Each step includes:
  - Mathematical expressions
  - Explanations in Bengali
  - Highlighted contradictions and conclusions

## 🎥 Video Guide

Watch this comprehensive video tutorial to see the application in action and learn how to use all its features:


https://github.com/user-attachments/assets/92584780-1841-4f62-99bf-8f0365493dab


## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/real-number_teaching_aid.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd real-number_teaching_aid
   ```

3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local server:

     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (http-server)
     npx http-server
     ```

   - Then navigate to `http://localhost:8000`

## 📖 Usage Guide

### Number Line Tab (সংখ্যা রেখা)

1. **Select a Number Type**

   - Choose from the dropdown menu (√2, √3, π, fractions, or custom)
   - For custom numbers, enter a value in the input field

2. **Plot the Number**

   - Click "স্থাপন করুন" (Plot) button
   - The number appears on the number line with color coding

3. **Zoom Controls**

   - 🔍 Zoom In: Increase magnification
   - 🔍 Zoom Out: Decrease magnification
   - 🔄 Reset: Return to default zoom level

4. **View Information**

   - See detailed information about the plotted number
   - View list of all plotted numbers

5. **Clear**
   - Click "মুছুন" (Clear) to remove all plotted numbers

### Proof Tab (√2 প্রমাণ)

1. **Navigate Through Steps**

   - ⬅️ আগের (Previous): Go to previous step
   - পরের ➡️ (Next): Go to next step
   - 🔄 শুরু (Reset): Return to first step

2. **Follow the Proof**
   - Each step builds on the previous one
   - Mathematical expressions are clearly displayed
   - The contradiction is highlighted
   - Final conclusion is shown with success indicator

## 🎨 Features Breakdown

### Proof Steps Included:

1. **Step 1**: Assume √2 is rational (√2 = p/q)
2. **Step 2**: Square both sides (2q² = p²)
3. **Step 3**: Prove p is even
4. **Step 4**: Substitute and prove q is even
5. **Step 5**: Show contradiction (both p and q are even)
6. **Conclusion**: √2 is irrational

### Visual Elements:

- ✅ Smooth animations
- 📊 Responsive canvas drawing
- 🎯 Color-coded number types
- 📱 Mobile-friendly design
- 🌈 Clean, modern UI

## 🛠️ Technical Details

- **Language**: HTML, CSS, JavaScript (Vanilla JS)
- **No Dependencies**: Pure JavaScript, no frameworks required
- **Canvas API**: Used for number line visualization
- **Responsive Design**: Works on desktop and mobile devices
- **Language**: Bengali (বাংলা) interface

## 🎓 Educational Value

This tool helps students:

- Visualize real numbers on a number line
- Understand the difference between rational and irrational numbers
- Learn a classic mathematical proof using contradiction
- Interact with mathematical concepts hands-on
- Follow step-by-step logical reasoning

## 📱 Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Any modern browser with HTML5 Canvas support

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation
- Add more proofs or examples

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍🏫 Target Audience

- **Students**: 9th-10th grade (মাধ্যমিক)
- **Teachers**: Mathematics educators
- **Subject**: Real Numbers (বাস্তব সংখ্যা)
- **Curriculum**: Bangladesh Secondary Education

## 🌟 Future Enhancements

Potential features for future versions:

- More mathematical proofs (√3, √5, etc.)
- Practice problems and quizzes
- Save/load plotted numbers
- Export number line as image
- Additional language support
- Sound effects and narration
- Printable worksheets

## 📧 Contact

For questions, suggestions, or feedback, please open an issue on GitHub.

---

**Made with ❤️ for students learning mathematics**

_শিক্ষার আলোয় আলোকিত হোক প্রতিটি মন_ 🎓
