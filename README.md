# NewsLens
**Comparing News Coverage Across Sources**

## Project Overview

NewsLens is a small programming project that aims to compare
articles from different news sources covering the same or
similar events.

News reports may focus on different details, use different
wording, or describe an event from different perspectives.
NewsLens will explore these similarities and differences
through basic text analysis.

## Research Question

How can a simple tool compare the language and content of
articles about the same event across different news sources
and identify differences that may deserve closer review?

## Planned Features

- Compare the text of selected news articles.
- Calculate text similarity using TF-IDF and cosine similarity.
- Display a pairwise similarity table and a heatmap.
- Identify shared and distinctive wording for further inspection.

## Planned Workflow

1. Select 6–9 articles from 3 news sources, covering 2–3 events.
2. Record each article's title, source, date, event, and URL.
3. Prepare the texts for analysis.
4. Calculate similarity between articles.
5. Visualize the results and discuss the findings.

## Tools

- Python
- pandas
- scikit-learn
- matplotlib

## Limitations

Text similarity does not prove that an article is true or false
or that a news source is biased. The results will support
human review rather than make automatic judgments.

## Project Status

Initial setup. The dataset, analysis, and visualizations
are planned and will be developed step by step.
