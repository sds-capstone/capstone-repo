## Quarto Manuscript

<!-- badges: start -->

[![paper](https://github.com/sds-capstone/quarto-manuscript/actions/workflows/publish.yml/badge.svg)](https://github.com/sds-capstone/quarto-manuscript/actions/workflows/publish.yml)
<!-- badges: end -->

You can view the published work at:
<https://sds-capstone.github.io/quarto-manuscript/>

## Note

This is a template repo for generating a manuscript from Quarto that
accompanies the tutorial at: [Quarto Manuscripts:
RStudio](https://quarto.org/docs/manuscripts/authoring/rstudio.html)

## Repository analysis via `chchchanges`

### Current as of: March 21, 2025, 15:29:18

Here is a summary of the commits made to this repository:

    git2r::commits()

    ## [[1]]
    ## [739143b] 2025-03-21: Merge branch 'main' of https://github.com/sds-capstone/capstone-repo

    chchchanges::tbl_commits() |>
      knitr::kable()

<table>
<colgroup>
<col style="width: 26%" />
<col style="width: 13%" />
<col style="width: 15%" />
<col style="width: 44%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">what</th>
<th style="text-align: left;">who</th>
<th style="text-align: left;">when</th>
<th style="text-align: left;">why</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td
style="text-align: left;">739143b23de38b1bb32fbacf515682a00c5c9053</td>
<td style="text-align: left;"><a href="mailto:ben.baumer@gmail.com"
class="email">ben.baumer@gmail.com</a></td>
<td style="text-align: left;">2025-03-21 15:27:24 GMT</td>
<td style="text-align: left;">Merge branch ‘main’ of <a
href="https://github.com/sds-capstone/capstone-repo"
class="uri">https://github.com/sds-capstone/capstone-repo</a></td>
</tr>
</tbody>
</table>

    chchchanges::summarize_commits() |>
      knitr::kable()

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 11%" />
<col style="width: 23%" />
<col style="width: 23%" />
<col style="width: 4%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">who</th>
<th style="text-align: right;">num_commits</th>
<th style="text-align: left;">first_commit</th>
<th style="text-align: left;">last_commit</th>
<th style="text-align: right;">days</th>
<th style="text-align: right;">commits_per_week</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><a href="mailto:ben.baumer@gmail.com"
class="email">ben.baumer@gmail.com</a></td>
<td style="text-align: right;">1</td>
<td style="text-align: left;">2025-03-21 15:27:24 GMT</td>
<td style="text-align: left;">2025-03-21 15:27:24 GMT</td>
<td style="text-align: right;">0</td>
<td style="text-align: right;">Inf</td>
</tr>
</tbody>
</table>

The following analysis is automated via [Google
Gemini](https://en.wikipedia.org/wiki/Gemini_(chatbot)) and the
[`chchchanges`](https://github.com/beanumber/chchchanges) package.

    chchchanges::summarize_git_with_llm(
      show_prompts = TRUE, 
      user_prompt = "Also assign letter grades to each contributor. "
    ) |>
      markdown::mark()

    ## Using model = "gemini-2.0-flash".
    ## System prompt: You are a friendly, supportive, college professor 
    ##     evaluating student contributions to a git repository.
    ## 
    ## Prompt: Analyze the following data from a git repository 
    ##     and tell me who deserves what credit for 
    ##     contributing to the project. 
    ##      Also assign letter grades to each contributor.  [{"who":"ben.baumer@gmail.com","num_commits":1,"first_commit":"2025-03-21 15:27:24 GMT","last_commit":"2025-03-21 15:27:24 GMT","days":0}]

\[1\] “
<p>
Okay, let’s break down the contribution data you’ve provided.
</p>
<p>
<strong>Analysis:</strong>
</p>
<p>
We have one contributor:
</p>
<ul>
<li>
<strong><a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a>:</strong>
This individual has made 1 commit to the repository. This commit was the
first and last, occurring on 2025-03-21, indicating a single day of
contribution.
</li>
</ul>
<p>
<strong>Credit Allocation and Grades:</strong>
</p>
<p>
Based on this data, here’s my assessment:
</p>
<ul>
<li>
<p>
<strong><a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a>:</strong>
Given the single commit, it’s difficult to assess the depth of the
contribution. However, they did initiate activity in the repository.
</p>
<ul>
<li>
<strong>Grade:</strong> C. A passing grade, acknowledging the initial
contribution. To achieve a higher grade, we’d need to see more commits
demonstrating engagement with the project over a longer period.
</li>
</ul>
</li>
</ul>
<p>
<strong>General Feedback:</strong>
</p>
<ul>
<li>
<p>
A single commit is a start, but a successful project typically involves
more sustained effort. To improve their grade, they should aim to:
</p>
<ul>
<li>
Contribute regularly: Make commits frequently, addressing different
aspects of the project.
</li>
<li>
Demonstrate a deeper understanding: Tackle more complex issues.
</li>
<li>
Engage with others: Participate in discussions, review code, and offer
assistance to other contributors.
</li>
</ul>
</li>
</ul>
<p>
I’m here to help! Please let me know if you have more data to analyze,
or if you’d like suggestions on how your contributors can improve their
contributions. Keep up the good work!
</p>

”
