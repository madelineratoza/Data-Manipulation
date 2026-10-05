# Week 4: Data Manipulation in R

An introductory Quarto tutorial for the ReproRehab Intro to R Boot Camp.

This lesson builds on Weeks 2 and 3 with a brief refresher on conditionals and loops, followed by hands-on practice manipulating data with **dplyr**.

## Learning goals

By the end of the lesson, learners will be able to:

- Select columns using `select()`.
- Filter rows using `filter()`.
- Sort observations using `arrange()`.
- Create new variables using `mutate()`.
- Summarize data using `summarise()` and `group_by()`.
- Connect steps using the pipe operator `|>`.

## Practice activities

The tutorial includes a fictional 12-participant rehabilitation dataset, worked examples, independent exercises, and expandable “If you're stuck” hints and answers.

A final mini analysis combines the lesson's skills. An optional activity introduces missing values.

All data and practice thresholds are synthetic and intended solely for learning.

## Using the tutorial

Open `index.html` in a web browser to view the rendered tutorial. Run the examples and exercises in your own RStudio session.

To edit and render the lesson, open `index.qmd` in RStudio or VS Code and run:

```bash
quarto render index.qmd --to html
```

Rendering requires Quarto, R, and the **dplyr** package. The pipe examples require R 4.1 or later.

Install dplyr once from the R Console:

```r
install.packages("dplyr")
```

The practice dataset is included directly in the tutorial; no separate data download is required.

## Files

- `index.qmd`: Editable Quarto source.
- `index.html`: Rendered HTML tutorial.
- `README.md`: Overview and instructions.

## Author

Madeline Ratoza, PT, DPT, PhD
