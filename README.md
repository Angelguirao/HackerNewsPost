# Exploring Hacker News Posts

This project aims to provide an analysis of posts on [Hacker News](https://news.ycombinator.com/), specifically focusing on the differences between `Ask HN` and `Show HN` post types.

## Objectives

The analysis delves into:
1. Comparing the average number of comments that `Ask HN` and `Show HN` posts receive.
2. Investigating if posts created at certain times are more likely to receive comments.

## Initial Observations

- The dataset used for this analysis is named `hacker_news.csv` and is loaded as a list of lists. The first list contains column headers, such as 'id', 'title', 'url', 'num_points', 'num_comments', 'author', and 'created_at'.
- An early separation is made between the post titles that begin with `Ask HN` or `Show HN` (case-insensitive), leading to the creation of two distinct lists. 

## Key Findings

- On average, `Ask HN` posts receive more comments than `Show HN` posts.
- The top hour to maximize the number of comments on `Ask HN` posts is at 15:00 (or 3pm EST).

## Conclusion

For those aiming to maximize their post engagement (in terms of comments) on Hacker News, posting in the `Ask HN` category around 3pm EST might yield the best results.

## Quick Start Guide

If you wish to replicate or continue with this analysis, please follow these steps:

1. Clone this repository.
2. Open the provided Jupyter Notebook (`Exploring Hacker News Posts.ipynb`).
3. Ensure you have the necessary Python libraries installed. For this project, the key libraries used are:
   - `csv` for data reading
   - `datetime` for time-based analysis
4. Run the notebook cells sequentially to view the analysis.

---

**Note:** The dataset used (`hacker_news.csv`) is a sampled dataset and may not represent the complete data from Hacker News. For comprehensive analysis, consider sourcing the complete dataset.
