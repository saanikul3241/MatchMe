# MatchMe
MatchMe is an AI-based foundation shade classifier providing recommendations based on the most inclusive foundation shade brand on the current market (Fenty Beauty). 

Techstack Used: Python (OpenCV) with manual creation of Dictionary for shade names
HaarCascade classifiers and detectMultiScale method was utilized in order to detect and locate the face and eyes in the uploaded image. 

# Optimizations 
A RGB tolerance algorithm was devised in order to calculate average RGB values within selected area and filter pixels within 'tolerance' away from average. Average is thus recalculated without outliers, accounting for hyperpigmentation and acne. 
# Future Optimizations 
The usage of the Fenty Beauty shade range as a reference guide for other popular foundation brands. Instead of manually creating a Dictionary, storing hex codes within a Database such as SQLite or fetching hex codes from websites for web scraping or direct API interaction would likely allow greater applicability. 



