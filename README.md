# 💔 Anti-Valentine Song Trend Analysis

## 📌 Project Overview

With the rise of **Anti-Valentine Week**, it becomes important to understand which songs resonate with audiences who celebrate independence, heartbreak themes, or emotional detachment from romantic commitment.

For this analysis, I used a Kaggle dataset containing song information and lyrics to identify tracks that align with Anti-Valentine sentiments.

Dataset Used:  
https://www.kaggle.com/datasets/suraj520/music-dataset-song-information-and-lyrics

---

## 🛠 Tools Used

- Python  
- Pandas  
- TextBlob (Sentiment Analysis)  
- Matplotlib / Seaborn  
- Plotly (Sunburst Visualization)

---

## 🧠 Methodology

### Step 1: Define Anti-Valentine Keywords

The following words were used to detect Anti-Valentine sentiment in lyrics:

```
"breakup", "broken", "heartbreak", "alone", "lonely", 
"cry", "tears", "hate", "toxic", "cheat", 
"goodbye", "regret", "pain", "sad", "hurt", 
"lost", "leave", "left", "lie", "betray"
```

These keywords were matched against song lyrics to create a **Keyword Score**.

---

### Step 2: Sentiment Analysis

- Sentiment polarity was calculated using TextBlob.
- Negative sentiment values indicate emotional distress or breakup themes.
- Combined with keyword frequency to build an **Anti-Valentine Index**.
<img width="695" height="545" alt="image" src="https://github.com/user-attachments/assets/720c09f5-6f0f-42a7-a60c-cf38434e119d" />
<img width="571" height="453" alt="image" src="https://github.com/user-attachments/assets/f3352e44-0d91-41c3-99af-b3d2cf419f5e" />

---

### Step 3: Visualization

- Scatter plot: *Anti-Valentine Trend Detection*
- Sentiment Distribution Histogram
- Sunburst Graph (Artist → Album → Song)

---

## 📊 Key Insights

### 1️⃣ Songs That Strongly Reflect Anti-Valentine Trends

The following songs scored high on the Anti-Valentine Index:

- **Too Many Nights (feat. Don Toliver & with Future)**
- **Waterloo Sunset - Mono Version**
- **A Design for Life – Remastered**
- (Additional songs available in GitHub repository)

These songs contain repeated emotional distress, separation, or anti-romantic expressions.

---

### 2️⃣ Popularity vs Sentiment Insight

From the graph:

**"Anti-Valentine Trend Detection"**

- Most highly popular songs lie in the positive sentiment spectrum.
- Negative romantic songs exist but are less dominant in mainstream popularity.
- Breakup-related words frequently appear even in neutral or slightly positive songs.

This suggests:

> People still prefer emotional songs, but full anti-romantic themes are less commercially dominant.

This is further supported by:

**"Sentiment Distribution"**

Which shows a significant presence of mild negativity but fewer extreme negative songs.

---

### 3️⃣ Anti-Valentine Themes & Anti-Marriage Interpretation

Some songs show sentiment that could be interpreted as resistance to conventional love or marriage norms:

- Waterloo Sunset - Mono Version  
- Queen of Belle la Vie  
- A Design for Life – Remastered  
- Sea of Problems  
- Past Lives  

Prominent artists reflecting these sentiments:

- The Kinks  
- The Band That Saved the World  
- Others contributing to emotional and anti-romantic narratives  

These songs often reflect:

- Emotional detachment  
- Disillusionment with love  
- Personal independence  

---

### 4️⃣ Sunburst Visualization

A Sunburst Graph was created to visualize:

```
Artist → Album → Song
```

This visualization helps identify:

- Which artists dominate Anti-Valentine trends
- Album clusters with emotional themes
- Relative strength of Anti-Valentine Index

An animated sunburst video version was also created to enhance interpretability.

---

## 📌 Conclusion

The analysis reveals that:

- Anti-Valentine themes are present but not dominant in mainstream popularity.
- Breakup and emotional distress keywords are frequently embedded even in commercially successful songs.
- Certain artists consistently explore anti-romantic or emotionally detached themes.
- While emotional music remains popular, strong anti-love sentiment remains a niche but growing pattern.

---

## Author
Sibankar Saha
---
