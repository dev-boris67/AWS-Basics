# 📊 Netflix Titles Analysis with Amazon QuickSight

Analyze and visualize Netflix titles using Amazon S3 and Amazon QuickSight. This project walks through uploading a dataset, connecting it to QuickSight, and building interactive dashboards to uncover trends in content release and genre popularity.

---

## 🧠 Overview

- **Author**: Nchindo Boris    
- **Tools Used**: Amazon S3, Amazon QuickSight  
- **Duration**: ~2 hours  
- **Goal**: Create a dashboard to explore Netflix content by year, genre, and date added.

---

## 📁 Dataset

- **Source**: [Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Files Used**:
  - `netflix_titles.csv`
  - `manifest.json` 

---

## ⚙️ Project Steps

### 1. Upload Dataset to S3
- Created bucket: `nextwork-quicksight-project-boris`
- Uploaded `netflix_titles.csv` and `manifest.json`
- Edited `manifest.json` to point to the correct S3 URL

![S3 Bucket Screenshot](https://github.com/dev-boris67/AWS-Basics/blob/main/QuickSight/images/Screenshot%20(15).png?raw=true)

---

### 2. Create QuickSight Account
- Signed up for QuickSight (free tier)
- Connected S3 bucket as a data source

![QuickSight Signup](https://yourdomain.com/images/quicksight-signup.png)

---

### 3. Build Visualizations
- Created charts showing:
  - Movies vs TV Shows by Release Year
  - Titles Added Over Time
  - Genre Breakdown (Thrillers, Comedies, Action & Adventure)
- Applied filters for timeframes and genres

![Release Year Chart](https://yourdomain.com/images/release-year-chart.png)  
![Genre Breakdown](https://yourdomain.com/images/genre-breakdown.png)  
![Date Added Chart](https://yourdomain.com/images/date-added-chart.png)

---

### 4. Publish Dashboard
- Added descriptive titles
- Exported dashboard as PDF

🔗 [View Dashboard](https://eu-north-1.quicksight.aws.amazon.com/sn/account/nextwork-QuickSight-boris/dashboards/8c8a00dc-7ac2-4c53-9d4b-90e9a6cac857)

---

## 💬 Reflections

> “It was most rewarding to see the target visualizations on the dashboard.”  
> “I plan to work on VPC projects next.”

---

## 🔮 Future Plans

- Explore AWS VPC configurations  
- Integrate more datasets for comparative analysis  
- Experiment with QuickSight’s natural language querying

---

## 📚 Resources

- [Amazon QuickSight Documentation](https://docs.aws.amazon.com/quicksight/)
- [NextWork.org](https://nextwork.org)

---

## 📄 License

This project is licensed under the MIT License.
