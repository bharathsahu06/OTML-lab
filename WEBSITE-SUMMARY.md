# Website Summary & Structure

## 📋 Complete File Structure

```
website/
├── index.html                          # Main landing page - lists all 19 experiments
├── guide.html                          # Quick start guide
├── reference.html                      # Glossary and reference materials
├── README.md                           # Documentation
│
├── css/
│   └── style.css                       # Complete styling (responsive design)
│
├── experiments/                        # All 19 experiment pages
│   ├── exp1.html   - Gradient Descent
│   ├── exp2.html   - Newton's Method
│   ├── exp3.html   - Stochastic Gradient Descent
│   ├── exp4.html   - Quadratic Optimization (CVXPY)
│   ├── exp5.html   - Linear Optimization (CVXPY)
│   ├── exp6.html   - Quadratic with Linear Constraints
│   ├── exp7.html   - Linear Programming (PuLP)
│   ├── exp8.html   - Sub-gradient L1-Regularization (Dataset 1)
│   ├── exp9.html   - Sub-gradient L1-Regularization (Dataset 2)
│   ├── exp10.html  - Interior Point Method (1D)
│   ├── exp11.html  - Interior Point Method (2D)
│   ├── exp12.html  - Mini-batch Gradient Descent (Dataset 1)
│   ├── exp13.html  - Distributed Gradient Descent
│   ├── exp14.html  - Mini-batch Gradient Descent (Dataset 2)
│   ├── exp15.html  - Distributed Gradient Descent (Dataset 2)
│   ├── exp16.html  - L1/L2 & Elastic Net Regularization
│   ├── exp17.html  - Group Lasso Sparsity
│   ├── exp18.html  - Conjugate Gradient Method
│   └── exp19.html  - Quasi-Newton Method (BFGS)
│
└── js/                                 # (Reserved for future interactive features)
```

## 🎯 Content Organization

### By Course Outcome (CO)

**CO1: Gradient Descent & Optimization Fundamentals**
- Exp 1-3: Basic optimization concepts
- Focus: Understanding how algorithms learn

**CO2: Convex Optimization & Linear Programming**
- Exp 4-7: Constrained optimization
- Focus: Solving optimization problems with constraints

**CO3: Sub-gradient & Interior Point Methods**
- Exp 8-11: Advanced techniques for difficult problems
- Focus: Non-smooth and constrained optimization

**CO4: Mini-batch & Distributed Gradient Descent**
- Exp 12-15: Scalable optimization
- Focus: Large-scale and parallel learning

**CO5: Regularization & Advanced Optimization**
- Exp 16-19: State-of-the-art techniques
- Focus: Professional optimization methods

## 📄 Page Components (Each Experiment)

Every experiment page includes:

1. **Breadcrumb Navigation** - Shows current location
2. **Aim** - Learning objectives
3. **Description** - Conceptual explanation
4. **Algorithm** - Step-by-step procedure
5. **Formulas** - Mathematical equations (highlighted)
6. **Mathematical Procedure** - Worked example with calculations
7. **Python Program** - Simple, readable code
8. **Expected Output** - Sample results
9. **Navigation Buttons** - Previous/Next/Home links

## 🎨 Design Features

### Responsive Layout
- Desktop: 3-column grid for experiments
- Tablet: 2-column grid
- Mobile: Single column
- All pages work on any device

### Color Scheme
- **Purple/Indigo (Main)**: Headers, links, emphasis
- **Light Gray**: Code blocks, formulas backgrounds
- **Green**: Successful output
- **Yellow**: Important formulas
- **Blue**: Hyperlinks

### Styling Elements
- Section titles with colored left borders
- Card-based experiment listing with hover effects
- Syntax highlighting in code (keywords, strings, comments)
- Highlighted output boxes
- Step-by-step numbered procedures

## 🚀 How to Use

1. **Open in Browser**: Double-click `index.html` or open in any web browser
2. **Navigate**: Click on any experiment card from the home page
3. **Learn**: Read through each section (aim → program → output)
4. **Practice**: Copy code and run in Python/Jupyter

## 💻 Required Libraries

For running the experiments:
```bash
pip install numpy scipy scikit-learn cvxpy pulp matplotlib
```

## 🔗 Navigation Features

- **Home Page**: Overview of all experiments organized by CO
- **Experiment Pages**: Detailed content with navigation buttons
- **Guide Page**: Learning paths and tips
- **Reference Page**: Glossary and quick lookup
- **Breadcrumbs**: Click to jump back to home or CO section

## 📊 Key Statistics

- **Total Experiments**: 19
- **Total Pages**: 24 (19 experiments + home + guide + reference + landing)
- **CSS File**: Single comprehensive stylesheet
- **Learning Hours**: 25-30 hours recommended
- **Topics Covered**: 8+ optimization algorithms

## ✨ Highlight Features

### For Beginners
- Clear explanations without heavy jargon
- Worked examples showing actual calculations
- Simple Python code easy to understand
- Progressive difficulty (CO1 → CO5)

### For Practitioners
- Professional algorithms (CVXPY, PuLP, BFGS)
- Real-world datasets and practical examples
- Performance considerations
- Implementation details

### For Educators
- Self-contained learning resource
- No external dependencies for content viewing
- Can be hosted locally or on web servers
- Easy to modify and customize

## 🎓 Educational Benefits

1. **Hands-on Learning**: Every concept has working code
2. **Visual Learning**: Formatted explanations with examples
3. **Interactive**: Students can modify code and experiment
4. **Progressive**: Concepts build on each other
5. **Self-paced**: Learn at your own speed

## 📱 Mobile-Friendly

- Responsive design works on all devices
- Touch-friendly navigation
- Readable on phones, tablets, laptops
- No external dependencies (fast loading)

## 🔒 Accessibility

- Clean semantic HTML structure
- High contrast color scheme
- Readable fonts (default system fonts)
- No auto-playing media
- Screen reader friendly

## 🚀 Quick Start Steps

1. Extract files to a folder
2. Open `index.html` in any web browser
3. Click on any course outcome
4. Browse available experiments
5. Click to view detailed content
6. Copy code and run in Python

## 📚 Additional Resources

- README.md: Comprehensive documentation
- Quick Start Guide (guide.html): Learning paths
- Glossary (reference.html): Term definitions
- Code Examples: Self-documented Python code

## 💡 Tips for Customization

You can easily modify:
- Colors by editing `css/style.css`
- Experiment content by editing HTML files
- Add new experiments by copying template structure
- Add interactive visualizations with JavaScript (js/ folder reserved)

## 🎯 Recommended Learning Path

**Week 1**: CO1 (3 experiments)
**Week 2**: CO2 (4 experiments)
**Week 3**: CO3 (4 experiments)
**Week 4**: CO4 (4 experiments)
**Week 5**: CO5 (4 experiments)

Total: ~5 weeks × 30 hours = 150 hours for comprehensive mastery

## 🌐 Online Hosting

Can be hosted on:
- GitHub Pages (free, static content only)
- Netlify (free with GitHub)
- AWS S3 + CloudFront
- Any web server (Apache, Nginx)
- Local server (python -m http.server 8000)

---

**Website Created**: 2024  
**Total Experiments**: 19  
**Total Pages**: 24  
**Educational Purpose**: Learning Optimization & Machine Learning  
**Target Audience**: Students, Practitioners, Educators
