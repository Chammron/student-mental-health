# Analyzing Students' Mental Health

![Mental Health](mentalhealth.jpg)

Utilized SQL to analyze and explore whether length of stay affects mental health scores for international students at a Japanese university.

## About

This project used SQL to analyze survey data from international students, looking at:
- Depression scores (PHQ-9)
- Social connectedness scores (SCS)
- Acculturative stress scores (ASISS)

## Key Finding

Longer-staying international students report higher acculturative stress, while depression scores remain relatively stable. Sample sizes for students staying 5+ years are too small to draw conclusions.

## Data

Field Name	|                Description
inter_dom	Types of students (international or domestic)
japanese_cate	Japanese language proficiency
english_cate	English language proficiency
academic	Current academic level (undergraduate or graduate)
age	Current age of student
stay	Current length of stay in years
todep	Total score of depression (PHQ-9 test)
tosc	Total score of social connectedness (SCS test)
toas	Total score of acculturative stress (ASISS test)

## Tools Used

- PostgreSQL
- DataCamp Workspace

---
*This was a pre-setup project by DataCamp. The work was mine, but the plan was theirs.*