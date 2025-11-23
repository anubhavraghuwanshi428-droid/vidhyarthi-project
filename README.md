Hostel Roommate Matcher

A Python-based interactive tool that helps match hostel students into compatible roommate pairs.

The program asks for lifestyle preferences, including sleep habits, cleanliness, noise tolerance, smoking habits, and personality type. Then it calculates a compatibility score to suggest the best roommate matches.

Features

✔ Add Students

Enter details such as:

Sleep time preference

Cleanliness level

Noise tolerance

Smoking habit

Personality type

✔ Automatic Compatibility Scoring

The algorithm assesses:

Sleep schedule match

Cleanliness similarity

Noise tolerance gap

Smoking compatibility

Introvert/Extrovert alignment

✔ Suggest Best Roommate Pairs

Uses a greedy matching approach to form the best possible pairs based on compatibility scores.

✔ Handles Odd Number of Students

If there is an odd number of students, then the last one appears unpaired.

How Compatibility Score Works ????
Each pair of students is compared on 5 attributes:
Preference	Scoring Logic
Sleep time	+20 if same, +5 if different
Cleanliness  Up to +20 (closer is better)

Noise tolerance	Up to +20 (closer is better) Smoking: +20 if same, -10 if mismatch Personality	+15 if same, +8 if different Higher score = More compatible roommates.
