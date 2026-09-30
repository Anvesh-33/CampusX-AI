# CampusX AI

A modern AI-powered hackathon prototype that helps college students discover complementary teammates from different departments and form multidisciplinary project teams.

## 🎯 Problem Statement

Students from different departments (CSE, ECE, EEE, Mechanical, Civil) have complementary skills, ideas, and interests, but they don't have an intelligent way to discover the right people and form multidisciplinary teams for projects, hackathons, and innovation.

## ✨ Solution

CampusX AI uses AI agents to:
1. **Analyze** your project idea and extract required skills
2. **Match** students with complementary expertise from different departments
3. **Build** the best multidisciplinary team with assigned roles
4. **Detect** missing skills and recommend fill-in students
5. **Plan** project timeline and responsibilities

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ and npm

### Installation

```bash
# Clone the repository
git clone https://github.com/Anvesh-33/CampusX-AI.git
cd CampusX-AI

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will open at `http://localhost:5173`

## 📱 Features

### Home Screen
- Clean hero section with CampusX AI branding
- Tagline: "Find the right people. Build the right team."
- Quick access to "Create Project" button
- Animated floating cards showcasing AI team matching

### Create Project
- Input project name, description, and required skills
- AI analyzes your project and generates recommended team

### AI Team Recommendation
- Displays project requirements and identified skills
- Shows team skill coverage summary
- Lists 5 recommended students with:
  - Department affiliation
  - Assigned role in the team
  - Detailed explanation of why they were selected
  - Complete skill profile

### Skill Gap Detection
- Identifies missing capabilities in the selected team
- Recommends additional students to fill specific gaps
- Shows why each skill is needed

### Project Dashboard
- Final team members list with roles
- Individual responsibilities for each team member
- AI-generated 4-week project timeline with milestones and tasks

## 🤖 AI Agents

### 1. Project Analyzer Agent
- Parses project description and extracts skills
- Identifies suitable departments
- Normalizes skill names across departments

### 2. Student Matcher Agent
- Compares required skills with student profiles
- Scores and ranks students by skill match
- Ensures team diversity (one student per department max)

### 3. Team Builder Agent
- Selects best 5 students for multidisciplinary team
- Assigns specialized roles based on skills
- Generates personalized reasons for each selection

### 4. Skill Gap Detection Agent
- Compares project requirements with team skills
- Identifies missing capabilities
- Recommends the best student to fill each gap

### 5. Project Planner Agent
- Assigns responsibilities to each team member
- Creates 4-week project timeline
- Defines weekly milestones and deliverables

## 👥 Demo Student Database

12 pre-loaded students across 5 departments:

**CSE (Computer Science & Engineering)**
- Aanya Sharma - AI/ML expert
- Nikhil Rao - Web & UI/UX developer
- Rahul Das - Backend & cloud engineer

**ECE (Electronics & Communication)**
- Rohan Iyer - Embedded systems & IoT specialist
- Sneha Verma - Computer vision & robotics expert
- Aditya Menon - Wireless & AI hardware engineer

**EEE (Electrical & Electronics)**
- Meera Nair - Power systems & energy optimization
- Vishal Kumar - PCB design & power electronics

**Mechanical**
- Arjun Patel - CAD & 3D modeling
- Pooja Bansal - Manufacturing & robotics

**Civil**
- Kavya Reddy - Project planning & structural design
- Ishita Sen - Sustainability & GIS specialist

## 🏗️ Tech Stack

- **Frontend:** React 18 + Vite
- **Styling:** Custom CSS with modern dark theme
- **Logic:** Pure JavaScript with functional components
- **State Management:** React hooks (useState, useMemo)

## 📊 Default Demo Project

**"Smart Waste Segregation System"**
- AI-powered waste classification using computer vision
- Sensor integration for data collection
- Dashboard for campus waste management
- Focus on sustainability tracking

Try modifying the project to see how the AI agents adapt team recommendations!

## 🎨 UI/UX Highlights

- Modern dark theme optimized for AI hackathon
- Glassmorphism design with backdrop blur effects
- Smooth animations and transitions
- Color-coded department badges
- Gradient accents and hover effects
- Fully responsive design
- Accessible form inputs and interactive elements

## 📦 Project Structure

```
CampusX-AI/
├── src/
│   ├── App.jsx          # Main app with all AI logic
│   ├── index.css        # Modern dark theme styling
│   └── main.jsx         # React entry point
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
└── README.md            # This file
```

## 🔄 AI Team Formation Flow

```
Project Idea
    ↓
Project Analyzer Agent
    ↓
Required Skills Identified
    ↓
Student Matcher Agent
    ↓
Top Candidates Ranked
    ↓
Team Builder Agent
    ↓
Multidisciplinary Team Selected
    ↓
Skill Gap Detection Agent
    ↓
Missing Skills Identified
    ↓
Project Planner Agent
    ↓
Final Team + Timeline Generated
```

## 🎓 Educational Value

This prototype demonstrates:
- AI-powered matching algorithms
- Skill normalization and semantic matching
- Constraint satisfaction (department diversity)
- Data-driven decision making
- UI/UX for complex workflows

## 💡 Future Enhancements

- Real student database integration
- Skill verification & endorsements
- Team collaboration tools
- Project progress tracking
- Mentor assignment
- Hackathon integration
- Email notifications
- Analytics dashboard

## 📝 Notes

- This is a **hackathon prototype** with no backend, authentication, or production features
- All data is stored locally in React state
- Student profiles are demo data
- Perfect for showcasing AI-powered team formation concepts

## 👨‍💻 Developer

Built with ❤️ for the AI hackathon

## 📄 License

MIT License - feel free to use this as a starting point for your own team-building platform!

---

**Ready to find your perfect team?** Click "Create Project" and let the AI agents work their magic! ✨
