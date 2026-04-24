# Can One Number Tell You If a Food Is Actually Healthy?

## The Health Impact Score: An Interactive Data Story

---

## Executive Summary

Every day, millions of Americans make food decisions based on nutrition labels that were designed for regulatory compliance, not consumer clarity. The standard Nutrition Facts panel presents over fifteen data points in small print with no clear signal about whether a food is actually good for you. This project addresses that gap by building the Health Impact Score — a composite scoring system that analyzes 7,500+ foods from the USDA FoodData Central database and ranks each one on a 0 to 1 scale. The formula rewards six positive nutrients (dietary fiber, Vitamin C, potassium, protein, magnesium, and calcium) and penalizes four negative ones (sugars, saturated fat, cholesterol, and sodium). The key finding: foods that score highest share one thing in common — high fiber and low sugar. Ultra-processed foods score near zero not because of one flaw, but because they fail on every dimension simultaneously. The result is a practical, transparent tool for everyday grocery shoppers.

---

## How to Interact

- **Click the arrows** at the bottom of the story to move between slides
- **Use the dropdown menu** on the Food Category Explorer slide to filter by category (Pizza, Vegetables, Fast Food, etc.)
- **Hover over any bar** to see the exact score and food name
- **Green bars** = healthy (0.65+) · **Amber bars** = moderate (0.35–0.64) · **Red bars** = poor (below 0.35)

---

## The Story

<div class="flourish-embed flourish-chart" data-src="story/3658570"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/story/3658570/thumbnail" width="100%" alt="Health Impact Score Data Story" /></noscript></div>

---

## About This Project

This data story was built as part of a graduate capstone project at Howard University. The full statistical analysis — including hypothesis testing, VIF multicollinearity diagnosis, and exploratory data analysis — is available in the project repository.

**Dataset:** USDA FoodData Central via Kaggle (7,500+ foods)
**Tools:** Python, Pandas, Scikit-learn, Flourish
**Author:** Kayla Robertson

[← Back to Home](/) · [📄 View Resume](resume) · [💻 View Code on GitHub](https://github.com/kaylarobertson36-creator/Kayla_Robertson_Capstone)
