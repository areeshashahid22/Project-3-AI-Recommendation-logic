# Project-3-AI-Recommendation-logic
 "Tech Stack Recommender - DecodeLabs AI Internship Project 3"
 
# Tech Stack Recommender
A content-based recommendation system built for DecodeLabs AI Internship - Project 3. It recommends the top 3 most relevant tech career paths based on a user's input skills, using TF-IDF vectorization and cosine similarity.

## Key Concepts
-> TF-IDF (Term Frequency-Inverse Document Frequency) weighting
-> Cosine similarity for measuring relevance between skill vectors
-> Sorting and filtering to generate Top-N recommendations
-> Reusable function design for handling multiple users

## Files
-> `AI Recommendation Logic.py` — main recommendation script
-> `raw_skills.csv` — dataset of 30 job roles and their associated skills

## How to Run
python recommender.py
## Example Output
Top 3 recommended roles for your skills: ['Python', 'Cloud Computing', 'Automation']
Cloud Architect: 0.603
Solutions Architect: 0.513
DevOps Engineer: 0.475

## Technologies Used
-> Python
-> scikit-learn
-> pandas

## Author
Areesha Shahid — BS Bioinformatics, Quaid-i-Azam University
