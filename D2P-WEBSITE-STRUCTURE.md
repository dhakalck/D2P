# Data to Policy (D2P) Global Website - Complete Structure

## Overview
This is a comprehensive, professional website for the global Data to Policy program. The website includes main pages, sub-pages, country pages, and training program details.

## File Structure

```
d2p-website/
├── index.html                    # Main home page
├── about.html                    # About D2P program
├── styles.css                    # Main stylesheet
├── images/
│   └── D2P.jpg                  # Partner logos
│
├── training/
│   ├── d2p-training.html        # D2P training overview
│   ├── d2p-agenda.html          # Sample agenda
│   ├── d2p-materials.html       # Training materials list
│   ├── unit1.html               # Unit 1 details
│   ├── unit2.html               # Unit 2 details
│   ├── unit3.html               # Unit 3 details
│   ├── ttt.html                 # Train-the-Trainer program
│   ├── ttt-agenda.html          # TTT agenda
│   └── he-tot.html              # Health Economics TOT
│
├── countries/
│   ├── index.html               # Countries overview
│   ├── bangladesh.html          #  Individual country pages
│   ├── rwanda.html              #  with D2P implementation
│   ├── south-africa.html        #  details, policy briefs,
│   ├── tanzania.html            #  and success stories
│   ├── thailand.html            #
│   ├── uganda.html              #
│   ├── zambia.html              #
│   └── lebanon.html (GGP)       #
│
├── resources/
│   ├── index.html               # Resources hub
│   ├── mentor-guide.html        # D2P Mentor Guide
│   ├── 10-steps.html            # 10 Steps guide
│   ├── modules.html             # All 20+ modules (L00-L20)
│   ├── templates.html           # Templates & tools
│   ├── policy-briefs.html       # Example briefs
│   └── videos.html              # Video tutorials
│
├── activities.html              # Global activities & events
├── contact.html                 # Contact information
└── README.md                    # Setup instructions
```

## Main Navigation Structure

1. **Home** (index.html)
   - Program overview
   - Impact statistics
   - Success stories
   - Quick links to key sections

2. **About D2P** (about.html)
   - Mission & vision
   - Program goals
   - Methodology (10 Steps)
   - Who should participate
   - Partners

3. **Training Programs** (dropdown)
   - **D2P Training**
     - Overview
     - Agenda
     - Training materials
     - Unit 1: Problem & Policy Analysis
     - Unit 2: Economic Evaluation
     - Unit 3: Advocacy & Communications
   - **Train-the-Trainer**
     - TTT overview
     - TTT agenda
     - Becoming a mentor
   - **Health Economics TOT**
     - HE TOT overview
     - Advanced economics training

4. **Focus Countries**
   - Countries overview map/list
   - Individual country pages:
     - D2P implementation history
     - Number of cohorts
     - Policy briefs produced
     - Success stories
     - Contact information

5. **Resources**
   - D2P Mentor Guide
   - 10 Steps to Developing a Policy Brief
   - Training modules (L00-L20)
   - Templates & tools
   - Example policy briefs
   - Video tutorials
   - Publications

6. **Global Activities**
   - Regional workshops
   - Policy forums
   - Annual conferences
   - Cross-country learning events
   - Upcoming events calendar

7. **Contact**
   - Program contacts
   - Regional coordinators
   - How to bring D2P to your country
   - Technical support

## Training Module Structure (L00-L20)

### Unit 1: Problem & Policy Analysis
- L00: Introduction and Big Picture
- L01: Policy and Policy Briefs
- L02: Literature Search and Other Data Sources
- L03: Framing the Problem
- L04: Root Cause Analysis
- L05: Gender Analysis for Policy Development
- L06: Epidemiologic Measures in Policy Briefs
- L07: Identify Policy Options
- L07b: Policy Implementation & Enforcement (Optional)
- L08: Stakeholder Analysis

### Unit 2: Economic Evaluation of Policy
- L09: Framing an Economic Evaluation
- L10: Assessing Health Impact
- L11: Cost Analysis
- L12: Economic Evaluation Methods
- L13: Sensitivity Analysis

### Unit 3: Policy Advocacy & Communications
- L14: Effective Writing
- L15: Writing the Problem Statement
- L16: Writing Policy Options
- L17: Making and Writing Recommendations
- L18: Data Visualization and Presentation
- L19: Writing Key Messages and Title
- L20: Advocacy Strategy and Communications

## Country Page Content Template

Each country page should include:
1. Country overview
2. D2P implementation timeline
3. Number of cohorts completed
4. Total participants trained
5. Policy briefs produced (with links/summaries)
6. Policy changes achieved
7. Success stories
8. Local facilitators/mentors
9. Partner organizations
10. Contact information

## Resource Categories

### 1. Training Materials
- PowerPoint presentations for all modules
- Facilitator notes
- Participant handouts
- Case studies

### 2. Templates & Tools
- Policy Brief Template (Word)
- PowerPoint Presentation Template
- Decision Tree Excel Template
- Cost Inventory Worksheet
- Fishbone Diagram Template
- Stakeholder Analysis Table
- Policy Analysis Table
- Literature Search Activity Sheet

### 3. Guides
- D2P Mentor Guide (comprehensive)
- 10 Steps to Developing a Policy Brief
- Facilitation Guide
- Policy Brief Checklist

### 4. Example Materials
- Completed policy briefs from multiple countries
- Sample presentations
- Case studies (Syphilis screening, Motorcycle helmets, etc.)

## Design Elements

### Color Scheme
- Primary: Deep purple (#52307C) - D2P brand color
- Secondary: Orange/gold (#FF9933) - Data for Health
- Accent: Blue (#0066CC) - CDC Foundation
- Success: Green (#00A878)
- Text: Dark gray (#333333)
- Backgrounds: White, light gray (#F5F5F5)

### Typography
- Headers: Bold, clear hierarchy
- Body: Readable, professional
- Consistent sizing across pages

### Components
- Hero sections with overlay
- Card-based layouts
- Process timelines
- Statistics/impact numbers
- Country flags/icons
- Module badges
- Dropdown menus
- Resource links
- Call-to-action buttons

## Responsive Design
- Desktop (1200px+)
- Tablet (768px-1199px)
- Mobile (< 768px)

## Implementation Priority

### Phase 1 (Essential)
- ✅ index.html
- ✅ about.html
- ⏳ d2p-training.html
- ⏳ countries/index.html
- ⏳ resources/index.html
- ⏳ styles.css (comprehensive)

### Phase 2 (High Priority)
- training/unit1.html, unit2.html, unit3.html
- training/ttt.html
- countries/[key countries].html
- resources/modules.html

### Phase 3 (Medium Priority)
- Individual module pages
- All country pages
- Complete resources section
- activities.html
- contact.html

### Phase 4 (Nice to Have)
- Blog/news section
- Photo galleries
- Video embeds
- Interactive maps
- Search functionality

## Maintenance Notes

- Keep partner logos updated
- Add new policy briefs as they're completed
- Update country statistics annually
- Refresh training materials when revised
- Add new countries as D2P expands
- Update contact information as staff changes

## Technical Requirements

- Modern web browser
- No server-side code required
- Static HTML/CSS
- Can be hosted on GitHub Pages
- Mobile-responsive
- Print-friendly pages

## Future Enhancements

- Participant login area
- Online module library with tracking
- Policy brief repository with search
- Interactive decision tree tool
- Economic evaluation calculator
- Country comparison tools
- Success story database
- Event calendar integration
- Multi-language support

