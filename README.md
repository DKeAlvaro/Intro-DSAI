# 🎬 Will I Like This Movie?
## A Hands-On Introduction to Data Science & AI

Welcome to your first Data Science project! In this workshop, you'll analyze movie data to discover what makes a movie successful and build a simple model to predict movie ratings.

---

## 🎯 The Problem

You want to know if a movie is worth watching before investing 2 hours of your time. **Can we predict if a movie will be good based on its characteristics?**

By the end of this workshop, you'll be able to:
- Load and explore real-world data using Python
- Create visualizations to find patterns
- Build a simple prediction model
- Draw data-driven conclusions

---

## 🚀 Getting Started

### Option A: GitHub Codespaces (Recommended - No Installation Required!)

1. Click the green **"Code"** button at the top of this repository
2. Select **"Codespaces"** tab
3. Click **"Create codespace on main"**
4. Wait for the environment to load (~2 minutes)
5. You're ready to go! 🎉

### Option B: Local Setup

If you prefer to work locally:

```bash
# Clone the repository
git clone <repository-url>
cd intro-dsai-movie-predictor

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook
```

---

## 📋 Workshop Checkpoints

Open the notebook `notebooks/workshop.ipynb` and follow along!

### Checkpoint 1: 🔧 Environment Setup
- [ ] Open the repository in Codespaces (or locally)
- [ ] Open `notebooks/workshop.ipynb`
- [ ] Run the first cell to import libraries
- [ ] Verify no errors appear

**You're ready when:** All imports run without errors! ✅

---

### Checkpoint 2: 📂 Load the Data
- [ ] Load the movie dataset using pandas
- [ ] Display the first 5 rows
- [ ] Check how many movies are in the dataset
- [ ] Explore the column names

**You're ready when:** You can see the movie data in a table format! ✅

---

### Checkpoint 3: 🔍 Explore the Data
- [ ] Find the average rating of all movies
- [ ] Identify movies with the highest and lowest ratings
- [ ] Check for missing values
- [ ] Understand what each column represents

**You're ready when:** You can answer: "What's the average movie rating?" ✅

---

### Checkpoint 4: 📊 Visualize Patterns
- [ ] Create a histogram of movie ratings
- [ ] Make a scatter plot of budget vs. revenue
- [ ] Visualize average rating by genre
- [ ] Identify any interesting patterns

**You're ready when:** You have at least 3 visualizations! ✅

---

### Checkpoint 5: 🔗 Find Correlations
- [ ] Calculate correlation between features
- [ ] Identify which features relate to high ratings
- [ ] Create a correlation heatmap
- [ ] Form hypotheses about what makes movies successful

**You're ready when:** You know which factors correlate with good ratings! ✅

---

### Checkpoint 6: 🤖 Build a Simple Predictor
- [ ] Prepare the data for machine learning
- [ ] Split data into training and testing sets
- [ ] Train a linear regression model
- [ ] Make predictions on new data

**You're ready when:** Your model can predict ratings! ✅

---

### Checkpoint 7: 📈 Evaluate Your Model
- [ ] Calculate prediction accuracy
- [ ] Visualize predicted vs. actual ratings
- [ ] Discuss model limitations
- [ ] Think about improvements

**You're ready when:** You can explain how well your model works! ✅

---

### Checkpoint 8: 🎉 Conclusions & Next Steps
- [ ] Summarize your findings
- [ ] Answer: "What makes a movie successful?"
- [ ] Celebrate completing your first DS project! 🎊

---

## 📁 Project Structure

```
📁 intro-dsai-movie-predictor/
├── 📄 README.md              ← You are here!
├── 📁 .devcontainer/         ← Codespaces configuration
├── 📁 data/
│   └── 📄 movies.csv         ← Our movie dataset
├── 📁 notebooks/
│   └── 📓 workshop.ipynb     ← Main workshop notebook
├── 📁 solutions/
│   └── 📓 workshop_solutions.ipynb  ← Complete solutions (no peeking! 👀)
└── 📄 requirements.txt       ← Python dependencies
```

---

## 🎓 What You're Learning

This workshop introduces skills you'll develop throughout your Data Science & AI degree:

| Skill | Courses |
|-------|---------|
| **Python Programming** | Year 1: Procedural Programming, Objects in Programming |
| **Data Manipulation** | Year 1: Intro to DS&AI, Principles of Data Science |
| **Visualization** | Year 1: Principles of Data Science |
| **Statistics** | Year 2: Probability & Statistics |
| **Machine Learning** | Year 2: Machine Learning |
| **Version Control (Git)** | Year 1: Software Engineering |

---

## 🆘 Need Help?

- **Stuck on code?** Check the hints in each notebook cell
- **Python error?** Read the error message - it often tells you what's wrong!
- **Still stuck?** Ask your instructor or peek at `solutions/workshop_solutions.ipynb`

---

## 📊 Dataset Information

We're using a curated subset of the **TMDB 5000 Movie Dataset**, which includes:

- **Movie titles** and release dates
- **Budget** and **revenue** information
- **Genres** and **keywords**
- **Popularity** and **vote average** (our target!)
- **Runtime** and other metadata

---

## 🏆 Challenge (Optional)

Finished early? Try these bonus challenges:

1. 🎭 **Genre Analysis**: Which genre has the best average rating?
2. 💰 **Budget Impact**: Do expensive movies get better ratings?
3. 📅 **Time Trends**: Are movies getting better or worse over time?
4. 🔮 **Better Predictions**: Can you improve the model accuracy?

---

**Happy coding! 🚀**

*Remember: Every data scientist started exactly where you are now!*
