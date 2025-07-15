# Calculator App

A modern, responsive calculator built with React, Next.js, and Tailwind CSS. This calculator provides a clean, iOS-inspired interface with smooth animations and comprehensive functionality.

## Features

### Basic Operations
- ✅ Addition (+)
- ✅ Subtraction (-)
- ✅ Multiplication (×)
- ✅ Division (÷)

### Advanced Functions
- ✅ Percentage calculations (%)
- ✅ Plus/minus toggle (+/-)
- ✅ Decimal point support
- ✅ Clear all (AC)

### User Experience
- 🎨 Modern, clean UI design
- 📱 Fully responsive (works on mobile and desktop)
- ⚡ Smooth hover animations
- 🖥️ Large, easy-to-read display
- 🎯 Intuitive button layout

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **State Management**: React useState hooks

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd calculator-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

### Basic Calculations
1. Click number buttons to input values
2. Click an operation button (+, -, ×, ÷)
3. Input the second number
4. Press = to see the result

### Advanced Features
- **AC Button**: Clears all calculations and resets to 0
- **+/- Button**: Toggles between positive and negative numbers
- **% Button**: Converts the current number to a percentage
- **Decimal Point**: Click . to add decimal places

### Example Calculations
```
Basic: 5 + 3 = 8
Decimal: 2.5 × 4 = 10
Percentage: 50% = 0.5
Negative: 10 +/- = -10
```

## Project Structure

```
calculator-app/
├── app/
│   ├── page.tsx          # Main calculator component
│   ├── layout.tsx        # Root layout
│   └── globals.css       # Global styles
├── components/
│   └── ui/               # shadcn/ui components
├── lib/
│   └── utils.ts          # Utility functions
├── public/               # Static assets
└── README.md            # This file
```

## Key Components

### Calculator Logic
The calculator uses React state to manage:
- Current display value
- Previous value for operations
- Current operation type
- Waiting state for new operand input

### Button Types
- **Number Buttons**: Input digits 0-9
- **Operation Buttons**: Perform calculations (+, -, ×, ÷, =)
- **Function Buttons**: Special functions (AC, +/-, %)

## Customization

### Styling
The calculator uses Tailwind CSS classes for styling. Key design elements:

- **Display**: Black background with white text, monospace font
- **Number Buttons**: Light gray with hover effects
- **Operation Buttons**: Orange with white text
- **Function Buttons**: Medium gray

### Colors
You can customize the color scheme by modifying the button classes in `app/page.tsx`:

```typescript
const numberButtonClass = "bg-gray-100 hover:bg-gray-200 text-gray-900"
const operatorButtonClass = "bg-orange-500 hover:bg-orange-600 text-white"
const functionButtonClass = "bg-gray-300 hover:bg-gray-400 text-gray-900"
```

## Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Commit your changes: `git commit -m 'Add feature'`
5. Push to the branch: `git push origin feature-name`
6. Submit a pull request

## Future Enhancements

- [ ] Scientific calculator functions (sin, cos, tan, log)
- [ ] Memory functions (M+, M-, MR, MC)
- [ ] Calculation history
- [ ] Keyboard input support
- [ ] Themes (dark mode, different color schemes)
- [ ] Sound effects
- [ ] Unit conversions

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Design inspired by iOS Calculator
- Built with [shadcn/ui](https://ui.shadcn.com/) components
- Icons from [Lucide React](https://lucide.dev/)

## Support

If you encounter any issues or have questions, please:
1. Check the existing issues on GitHub
2. Create a new issue with detailed information
3. Include steps to reproduce any bugs


