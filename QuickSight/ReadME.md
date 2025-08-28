# Visualize data with QuickSight

![Image](https://github.com/dev-boris67/AWS-Basics/blob/main/Project%20images/2.png?raw=true).

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-analytics-quicksight)

**Author:** Nchindo Boris  
**Email:** nchindoboris37@gmail.com

---

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Introducing Today's Project!

In this project, I will;
Upload a dataset into an S3 bucket.
Create an account on Amazon QuickSight.
Connect your dataset (in the S3 bucket) to Amazon QuickSight.
Create a variety graphs, charts and analysis using QuickSight.
Publish a dashboard 


### Tools and concepts

Services I used were Amazon S3 and Quicksight. Key concepts I learnt include;
- Upload a dataset into an S3 bucket
- Connect your dataset to Amazon QuickSight
- Create graphs, charts using QuickSight
- Publish a dashboard of visualizations

### Project reflection

This project took me approximately 2 hours to complete this project. I did not really face major challenges. It was most rewarding to see the target visualizations on the dashboard

After this project, I plan to work on VPC projects on the cloud. I will start this project next

---

## Upload project files into S3

S3 is used in this project to store two files, which are; netflix_titles.csv and manifest.json

I edited the manifest.json file by replacing the URL in the manifest.json file with the S3 URL of my dataset. It’s important to edit this file because it ensures that QuickSight finds and imports the right files using the correct S3 paths

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_3c3cd85a)

---

## Create QuickSight account

Creating a QuickSight account cost no money

Creating an account took me 2 minutes

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_f4ab4214)

---

## Download the Dataset

I connected the S3 bucket to QuickSight by visiting datasets page

The manifest.json file was important in this step because the manifest.json tells QuickSight what your dataset looks like, so QuickSight knows how to understand the data and show it in charts or graphs. Without this map, QuickSight might get confused

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_6f874996)

---

## My first visualization

To create visualizations on QuickSight, I drag fields into the graph. 

The chart/graph shown here is a breakdown of counts of records

I created this graph by dragging and dropping release year and type

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_aff3aad7)

---

## Using filters

Filters are useful for;
- Answering specific questions
- Focus on relevant data

This visualization is a breakdown of count of netflix records according to date added, release year, type and much more. Here I added a filter by;
- Click the filter icon
- Click add filter
- Choose the field to be added in the filter

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_c32248c5)

---

## Setting up a dashboard

As a finishing touch, I added descriptive titles to my visualizations

Did you know you could export your dashboard as PDFs too? I did this by clicking on export and then generating the pdf

![Image](http://learn.nextwork.org/soothed_rose_serene_peach/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Refreshing source data

---

---
