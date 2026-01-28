# Reddit Pain Point Finder For Food E-Commerce

## Overview
This project identifies real customer meal pain points from Reddit communities that align with Kay’s Curries’ product strengths.

Using Reddit RSS feeds and lightweight text filtering, it surfaces posts from travelers, campers, van-lifers, and people with dietary restrictions—groups that frequently struggle with food cost, kitchen access, and safe meals.

The output is a structured, AI-ready dataset mapping customer pain to product fit.

---

## Data Sources
- r/VisitingIceland  
- r/glutenfree  
- r/Celiac  
- r/camping  
- r/backpacking  
- r/vanlife  
- r/EatCheapAndHealthy  
- r/MealPrepSunday  

---

## Methodology
1. Pull posts via Reddit RSS feeds  
2. Filter for pain-signal keywords (cost, access, allergies, travel)  
3. Remove low-signal content (megathreads, announcements)  
4. Normalize titles into first-person customer pain statements  
5. Tag where Kay’s Curries is a strong solution  
6. Prioritize high-fit opportunities  

---

## Output
The final dataset includes:
- Source subreddit  
- Post title and URL  
- Normalized customer pain  
- Kay’s Curries solution fit  
- Priority flag  

---

## Tech Stack
- Python  
- pandas  
- feedparser  
- Regex-based NLP heuristics  

---

## Use Case
This pipeline converts unstructured online conversations into:
- AI-ingestible customer insights  
- Search and discovery signals  
- Evidence-backed positioning inputs  

---

## Author
Roman  
Kay’s Curries AI Intern
