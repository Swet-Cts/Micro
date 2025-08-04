# MicroMoment - Personalized Content Generator

A cutting-edge, AI-powered web application that creates personalized content based on your mood, preferences, and needs. Built with Next.js 14, TypeScript, and Tailwind CSS.

## ✨ Features

### 🎵 **Mood Playlist Generator**
Create the perfect playlist based on your current mood, energy level, and music preferences.

### 👔 **Weather Outfit Suggestions**
Get stylish outfit recommendations tailored to the weather, occasion, and your personal style.

### 💪 **Workout Routine Creator**
Generate personalized workout plans based on your fitness goals, experience level, and available equipment.

### 🍳 **Recipe Suggestions**
Discover recipes that match your dietary preferences, cooking time, and skill level.

### 📚 **Study Plan Generator**
Create optimized study schedules based on your learning style and available time.

### 🗺️ **Travel Itinerary Planner**
Plan perfect trips with activities based on your destination, interests, and budget.

## 🎨 Design Features

- **Modern Glass Morphism UI** - Beautiful, translucent cards with backdrop blur effects
- **Cyber-themed Animations** - Smooth transitions, floating elements, and neon accents
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Interactive Forms** - Dynamic form generation with various input types
- **Real-time Generation** - Simulated AI content generation with loading states

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd MicroMoment
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

## 🛠️ Technology Stack

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS with custom animations
- **Icons**: Lucide React
- **Animations**: CSS transitions and keyframes
- **Deployment**: Optimized for Vercel

## 📱 Usage

1. **Select a Generator**: Choose from 6 different content generators on the homepage
2. **Fill the Form**: Complete the personalized questionnaire for your selected generator
3. **Generate Content**: Click the generate button and watch the AI create your content
4. **Enjoy Results**: View your personalized content with options to regenerate, download, or share

## 🎯 Generator Types

### Mood Playlist
- **Inputs**: Current mood, preferred genres, energy level, playlist duration
- **Output**: Curated list of songs with artists, genres, and mood tags

### Weather Outfit
- **Inputs**: Weather conditions, occasion, style preference, color preferences
- **Output**: Complete outfit suggestions with categories, items, colors, and descriptions

### Workout Routine
- **Inputs**: Fitness goals, experience level, workout duration, available equipment
- **Output**: Exercise list with sets, reps, duration, and difficulty levels

### Recipe Suggestions
- **Inputs**: Dietary preferences, cuisine type, cooking time, difficulty level
- **Output**: Recipe recommendations with prep time, ingredients, and descriptions

### Study Plan
- **Inputs**: Subject/topic, available time, learning style, topic difficulty
- **Output**: Structured study sessions with methods, materials, and tips

### Travel Itinerary
- **Inputs**: Destination, interests, budget range, trip duration
- **Output**: Activity suggestions with types, duration, costs, and descriptions

## 🎨 Design System

### Colors
- **Primary**: Blue gradient (#3b82f6 to #2563eb)
- **Accent**: Purple gradient (#8b5cf6 to #7c3aed)
- **Cyber**: Neon blues, purples, and pinks
- **Background**: Multi-layer gradients with grid pattern

### Typography
- **Font**: Inter (Google Fonts)
- **Hierarchy**: Multiple font weights and sizes for clear information hierarchy

### Components
- **Glass Cards**: Translucent backgrounds with blur effects
- **Cyber Buttons**: Gradient backgrounds with animated shine effects
- **Form Elements**: Custom styled inputs with focus states
- **Icons**: Lucide React icons with consistent sizing

## 🔧 Customization

### Adding New Generators

1. **Update Types**: Add new interfaces in `types/generators.ts`
2. **Add Configuration**: Extend the generators array in `components/GeneratorGrid.tsx`
3. **Handle Generation**: Update the mock generation function in `app/page.tsx`
4. **Add Display Logic**: Extend the render function in `components/ResultsDisplay.tsx`

### Styling

The project uses Tailwind CSS with custom utilities defined in `app/globals.css`:
- `.glass-card` - Glass morphism effect
- `.cyber-button` - Animated gradient buttons
- `.neon-border` - Glowing border effects
- `.text-gradient` - Gradient text effects

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help, please open an issue in the GitHub repository.

---

**Made with ❤️ for creating personalized experiences** 