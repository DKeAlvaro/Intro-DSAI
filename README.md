# Will I Like This Movie?
## A Hands-On Introduction to Data Science & AI

You want to know if a movie is worth watching before investing 2 hours of your time. **Can we predict if a movie will be good based on its characteristics?**

By the end of this workshop, you'll be able to:
- Load and explore real-world data using Python
- Create visualizations to find patterns
- Build a simple prediction model
- Draw data-driven conclusions

---

## Getting Started

### GitHub Codespaces

1. Click the green **"Code"** button at the top of this repository
2. Select **"Codespaces"** tab
3. Click **"Create codespace on main"**
4. Wait for the environment to load (~2 minutes)
5. Open `notebooks/workshop.ipynb` and start!

## Workshop Checkpoints

Open `notebooks/workshop.ipynb` and follow along!

### Checkpoint 1: Environment Setup
- [ ] Open the repository in Codespaces (or locally)
- [ ] Open `notebooks/workshop.ipynb`
- [ ] Run the first cell to import libraries
- [ ] Verify no errors appear

---

### Checkpoint 2: Load the Data
- [ ] Load the movie dataset using pandas
- [ ] Display the first 5 rows
- [ ] Check how many movies are in the dataset
- [ ] Explore the column names

---

### Checkpoint 3: Explore the Data
- [ ] Find the average rating of all movies
- [ ] Identify movies with the highest and lowest ratings
- [ ] Check for missing values
- [ ] Understand what each column represents

---

### Checkpoint 4: Visualize Patterns
- [ ] Create a histogram of movie ratings
- [ ] Make a scatter plot of budget vs. revenue
- [ ] Visualize average rating by genre
- [ ] Identify any interesting patterns

---

### Checkpoint 5: Find Correlations
- [ ] Calculate correlation between features
- [ ] Identify which features relate to high ratings
- [ ] Create a correlation heatmap
- [ ] Form hypotheses about what makes movies successful

---

### Checkpoint 6: Build a Simple Predictor
- [ ] Prepare the data for machine learning
- [ ] Split data into training and testing sets
- [ ] Train a linear regression model
- [ ] Make predictions on new data

---

### Checkpoint 7: Evaluate Your Model
- [ ] Calculate prediction accuracy
- [ ] Visualize predicted vs. actual ratings
- [ ] Discuss model limitations
- [ ] Think about improvements

---

### Checkpoint 8: Conclusions & Next Steps
- [ ] Summarize your findings
- [ ] Answer: "What makes a movie successful?"
- [ ] Celebrate completing your first DS project!

---

## Project Structure

```
intro-dsai-movie-predictor/
├── README.md              
├── .devcontainer/         
├── data/
│   └── movies.csv         
├── notebooks/
│   └── workshop.ipynb     
├── solutions/
│   └── workshop_solutions.ipynb
└── requirements.txt       
```

---

## What You're Learning

This workshop introduces skills you'll develop throughout your Data Science & AI degree:

| Skill | Courses |
|-------|---------|
| **Python Programming** | Year 1: Procedural Programming, Objects in Programming |
| **Data Manipulation** | Year 1: Intro to DS & AI, Principles of Data Science |
| **Visualization** | Year 1: Principles of Data Science |
| **Statistics** | Year 2: Probability & Statistics |
| **Machine Learning** | Year 2: Machine Learning |
| **Version Control (Git)** | Year 1: Software Engineering |

---

## Dataset Information

We're using a curated subset of the **TMDB 5000 Movie Dataset**, which includes:

- Movie titles and release dates
- Budget and revenue information
- Genres and keywords
- Popularity and vote average (our target!)
- Runtime and other metadata

---

## Bonus Challenges

Finished early? Try these:

1. **Genre Analysis**: Which genre has the best average rating?
2. **Budget Impact**: Do expensive movies get better ratings?
3. **Time Trends**: Are movies getting better or worse over time?
4. **Better Predictions**: Can you improve the model accuracy?

---

## Need Help?

- **Stuck on code?** Check the hints in each notebook cell
- **Python error?** Read the error message - it often tells you what's wrong!
- **Still stuck?** Ask your instructor or peek at `solutions/workshop_solutions.ipynb`
