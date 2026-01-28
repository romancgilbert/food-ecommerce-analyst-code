Reddit Pain Point Finder
Overview

This project identifies real customer meal pain points from Reddit communities that closely match Kay’s Curries’ product strengths.

Using Reddit RSS feeds and lightweight text filtering, it surfaces posts from travelers, campers, van-lifers, and people with dietary restrictions—groups that often struggle with cost, access to kitchens, and safe meals.

The goal is to turn messy internet conversations into structured, AI-ready customer insights.

Data Sources

Reddit RSS feeds from:

r/VisitingIceland

r/glutenfree

r/Celiac

r/camping

r/backpacking

r/vanlife

r/EatCheapAndHealthy

r/MealPrepSunday

Method

Pull posts via RSS (no scraping or auth)

Filter for pain-signal keywords (cost, access, allergies, travel)

Remove low-signal posts (megathreads, announcements, noise)

Normalize titles into first-person customer pain statements

Tag where Kay’s Curries is a strong solution

Prioritize high-fit opportunities

Output

A structured dataset mapping:

Customer pain

Source community

Relevant post links

Kay’s Curries product fit

Priority score

Example pains:

Traveling without a kitchen and need easy meals

Finding quick, reliable gluten-free food

Tech Stack

Python

pandas

feedparser

regex-based NLP heuristics

Why This Matters

This pipeline turns public customer frustration into:

Search-ready insights

AI-ingestible signals

Evidence-based positioning opportunities

It supports Kay’s Curries’ AI, content, and product strategy.

Author

Roman — Kay’s Curries AI Intern
