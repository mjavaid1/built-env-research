##### Construction Worker Suicide Risk Factor Analysis

## Objective

Identify and prioritize the factors that contribute to the high suicide rate among construction workers by collecting and analyzing responses from various professionals.

---

# Professional Roles

Use the following 10 professional roles:

1. Construction Engineer
2. Construction Safety Manager
3. Engineer on a Construction Site
4. Experienced Construction Worker
5. Environmental Health Practitioner
6. Family Member of an Experienced Construction Worker
7. Mental Health Professional
8. Project Manager
9. Regulatory Professional
10. Union Representative

Throughout this document, each role is referred to as **Profession X**.

---

# Round 1 – Identify Contributing Factors

## Task

For each of the 10 professional roles:

- Assume the identity of **Profession X**.
- Answer the following question:

> **What factors contribute to the high suicide rate among construction workers?**

- Analyze the text provided by the user.
- Extract all relevant contributing factors.
- Output the identified factors in a Markdown table.

### Repetitions

- Perform this process **three independent times** for each professional role.
- This produces:
  - **10 professional roles**
  - **3 responses per role**
  - **30 total responses**

---

# Factor Consolidation

After collecting all responses:

1. Combine all identified factors.
2. Group similar or overlapping factors together.
3. Reduce the list to **30 unique factors** representing the major themes.
4. Create a markdown table giving the rank, contributing factor, and frequency mentioned by Profession X. Rank is defined by the frequency mentioned. Highest frequecy gets the 1st rank and lowest frequecy gets the 30th rank and same way ranks are given for mid frequencies in order. 
   
   Example table:
   | Rank | Contributing Factor | Frequency Mentioned |
   |------|---------------------|---------------------|
   |  1   | Financial Struggles |       17            |
   |  2   |Demending work schedules|    12            |

---

# Round 2 – Likert Scale Rating

## Task

Provide the consolidated list of **30 factors** to each Profession X.

Each participant should independently rate every factor using the following scale:

| Rating | Meaning |
|---------|---------|
| 1 | Highest impact on suicide rate |
| 10 | Lowest impact on suicide rate |

### Participants

- 30 total responses
  - 3 responses from each of the 10 professional roles

---

# Output Table

Create a Markdown table with:

| Column | Description |
|---------|-------------|
| Column 1 | Factor |
| Columns 2–31 | Ratings from each of the 30 participants |

Each row represents one factor.

Each participant occupies one column.

Example:

| Factor | CE-1 | CE-2 | CE-3 | CSM-1 | ... | UR-3 |
|--------|------|------|------|--------|-----|------|
| Job insecurity | 2 | 1 | 3 | 2 | ... | 1 |

---

# Statistical Analysis

For each factor (row), calculate:

- Mean
- Median
- Mode
- Interquartile Range (IQR)
- Standard Deviation

Append these statistics as additional columns.

Example:

| Factor | CE-1 | ... | UR-3 | Mean | Median | Mode | IQR | Std Dev |
|--------|------|-----|------|------|--------|------|-----|---------|

---

# Select Top Five Factors

Using the statistical results:

- Rank factors by **mean score**.
- Select the **five factors with the lowest mean values**, indicating the highest perceived impact on suicide risk.

---

# Round 3 – Final Ranking

Provide the **top five factors** to each Profession X.

Each participant should rank every factor using the following 5-point ranking scale:

| Rank | Meaning |
|------|---------|
| 1 | Highest impact |
| 2 | High impact |
| 3 | Moderate impact |
| 4 | Low impact |
| 5 | Lowest impact |

Collect:

- 30 responses
- 3 responses from each professional role

---

# Final Results Table

Create a Markdown table containing:

| Column | Description |
|---------|-------------|
| Column 1 | Factor |
| Columns 2–31 | Rankings from each participant |

Example:

| Factor | CE-1 | CE-2 | ... | UR-3 |
|--------|------|------|-----|------|

---

# Ranking Frequency Analysis

For each factor, calculate:

- Number of rankings equal to **1**
- Number of rankings equal to **2**
- Number of rankings equal to **3**
- Number of rankings equal to **4**
- Number of rankings equal to **5**

Example:

| Factor | Rank 1 | Rank 2 | Rank 3 | Rank 4 | Rank 5 |
|--------|--------|--------|--------|--------|--------|

---

# Maximum Frequency Analysis

For each ranking value (1–5):

1. Determine the highest frequency.
2. Identify the factor(s) associated with that maximum frequency.

Summarize the results as follows:

| Ranking | Maximum Frequency | Corresponding Factor(s) |
|----------|-------------------|-------------------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

# Deliverables

The final output should include:

1. Responses from all 30 simulated participants.
2. Consolidated list of 30 unique contributing factors.
3. Likert-scale rating table for all 30 factors.
4. Statistical summary (Mean, Median, Mode, IQR, Standard Deviation).
5. Identification of the five highest-impact factors.
6. Final ranking table for the top five factors.
7. Frequency table for rankings 1–5.
8. Summary of the factors with the maximum frequency for each ranking value.