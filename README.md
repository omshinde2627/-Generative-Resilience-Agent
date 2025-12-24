# Generative Resilience Agent (GRA) — Local Climate Adaptation Planner

An AI-powered Generative Resilience Agent designed to create hyper-local climate adaptation plans for rural communities in India. GRA leverages advanced AI and real-world agricultural data to generate personalized resilience strategies, helping farmers and communities adapt to changing climate conditions.

![GRA Logo](./logo_GRA.jpeg)

## 🏆 AWS ImpactX Challenge - IIT Bombay

**🎉 FINALIST PROJECT** - Team COSMOS has been selected for the **Final Round** of the prestigious AWS ImpactX Challenge at IIT Bombay! Our Generative Resilience Agent (GRA) represents an innovative approach to addressing climate adaptation challenges in rural India through AI-powered local planning solutions.

### Challenge Focus
Our GRA project addresses critical climate resilience needs in agriculture, leveraging AWS cloud infrastructure and generative AI services to create scalable, locally-adapted solutions for communities facing climate change challenges.

## 🌾 Overview

The Generative Resilience Agent (GRA) is an intelligent local climate adaptation planning system that uses generative AI to create personalized resilience strategies for rural communities. GRA combines real-world agricultural and climate data with advanced AI models to generate actionable, location-specific adaptation plans that help communities build resilience against climate change impacts.

## ✨ Key Features

### 🎯 Generative AI Capabilities
- **AI-Powered Adaptation Plans**: Generate comprehensive, locally-tailored climate resilience strategies
- **Dynamic Plan Generation**: Create adaptive plans that evolve with changing conditions
- **Multi-Scenario Planning**: Generate multiple adaptation pathways for different climate scenarios
- **Contextual Recommendations**: AI-driven suggestions based on local climate, soil, and socio-economic factors

### 📊 Local Climate Intelligence
- **Hyper-Local Analysis**: Community-specific climate risk assessment and adaptation planning
- **Resilience Mapping**: Visual representation of climate vulnerabilities and adaptation opportunities
- **Resource Optimization**: Intelligent allocation of local resources for maximum resilience impact
- **Community-Centric Design**: Plans tailored to local knowledge, practices, and constraints

### 🎛️ Dashboard Components
- **Interactive Resilience Charts**: Visualize climate risks, adaptation progress, and community resilience metrics
- **Adaptation Plan Designer**: Create and customize local climate adaptation strategies
- **Scenario Comparison**: Compare multiple resilience pathways and their effectiveness
- **Community Impact Analysis**: Track adaptation outcomes and community resilience building

### 🌐 Data Integration
- Local climate and weather pattern data
- Agricultural productivity and crop resilience datasets
- Socio-economic and demographic information
- Traditional knowledge and local practices integration

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager
- Google Gemini API key (for AI features)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Gra-2-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   GEMINI_API_KEY=your_google_gemini_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production
```bash
npm run build
npm run preview
```

## 🏗️ Project Structure

```
Gra-2-main/
├── components/           # React components
│   ├── BudgetBreakdown.tsx    # Resource allocation and cost planning
│   ├── Dashboard.tsx          # Main GRA dashboard interface
│   ├── DataInsights.tsx       # Climate and resilience analytics
│   ├── FarmLayoutBlueprint.tsx # Local adaptation planning tools
│   ├── Header.tsx             # Application header
│   ├── VillageForm.tsx        # Community data input form
│   └── VisualBlueprint.tsx    # Visual adaptation planning
├── services/            # AI and data services
│   ├── dataService.ts         # Climate data processing and predictions
│   └── geminiService.ts       # Generative AI integration for plan creation
├── public/data/         # Climate and agricultural datasets
│   ├── agricultural_data_india.csv
│   ├── Crop_recommendation.csv
│   ├── Rainfall_Data_LL.csv
│   └── seeds.csv
├── types.ts             # TypeScript type definitions
└── App.tsx             # Main GRA application component
```

## 🛠️ Technology Stack

### Frontend
- **React 19.2.3** - Modern React with latest features
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and development server
- **Recharts** - Data visualization library
- **Lucide React** - Beautiful icon library

### AI & Data
- **Google Gemini AI** - Generative AI for creating adaptive resilience plans
- **CSV Data Processing** - Real climate and agricultural datasets from India
- **Predictive Analytics** - Climate risk modeling and adaptation effectiveness prediction

### Development Tools
- **ESLint** - Code linting and quality
- **TypeScript Compiler** - Type checking
- **Vite Dev Server** - Hot module replacement

## 📈 Features in Detail

### 1. Community Data Input
- Location-based climate vulnerability assessment
- Local resource and capacity evaluation
- Traditional knowledge and practices documentation
- Community resilience baseline establishment

### 2. Generative Adaptation Planning
- AI-generated climate resilience strategies
- Multi-pathway adaptation plan creation
- Context-aware recommendation generation
- Dynamic plan optimization and updates

### 3. Resource Allocation Planning
- Community resource mapping and optimization
- Cost-benefit analysis for adaptation measures
- Implementation timeline and priority setting
- Funding and investment planning tools

### 4. Visual Adaptation Design
- Interactive community resilience mapping
- Adaptation infrastructure planning
- Resource flow and system design
- Implementation visualization tools

### 5. Climate Scenario Modeling
- Future climate risk assessment
- Adaptation strategy effectiveness testing
- Resilience pathway comparison
- Long-term sustainability analysis

## 🌍 Data Sources

The GRA uses comprehensive datasets including:
- Local and regional climate vulnerability data
- Agricultural resilience and adaptation case studies
- Socio-economic and demographic information
- Traditional ecological knowledge databases
- Climate projection and risk assessment data

## 🔧 Configuration

### Environment Variables
- `GEMINI_API_KEY`: Your Google Gemini API key for AI features
- `VITE_API_URL`: API endpoint (if using external services)

### TypeScript Configuration
The project uses modern TypeScript with:
- ES2022 target
- React JSX support
- Path aliases for clean imports
- Strict type checking

## 🔮 Future Enhancements

- Mobile GRA application for field deployment
- Offline adaptation plan generation
- Multi-language support for diverse communities
- Advanced climate projection integration
- Community collaboration and knowledge sharing features
- IoT sensor integration for real-time monitoring
- Blockchain-based adaptation impact tracking

## 🏆 AWS ImpactX Challenge Recognition

### About the Challenge
The AWS ImpactX Challenge at IIT Bombay is a prestigious competition focused on leveraging cloud technologies to create solutions with significant social and environmental impact. The challenge brings together innovative teams to address real-world problems using AWS services and cutting-edge technology.

### Our Achievement
- **Status**: Selected for Final Round at IIT Bombay
- **Team**: COSMOS
- **Project**: Generative Resilience Agent (GRA) — Local Climate Adaptation Planner
- **Focus Area**: AI-Powered Climate Resilience & Community Adaptation
- **Impact**: Empowering rural communities with AI-generated climate adaptation strategies

### Project Alignment with AWS ImpactX Goals
- **Scalability**: Cloud-native generative AI architecture for nationwide deployment
- **Impact**: Direct empowerment of rural communities through localized resilience planning
- **Innovation**: Generative AI for creating adaptive, context-specific climate solutions
- **Sustainability**: Building long-term community resilience against climate change
