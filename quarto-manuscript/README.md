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

### Current as of: March 21, 2025, 15:18:56

Here is a summary of the commits made to this repository:

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
<td style="text-align: left;">2025-03-21 15:16:59 GMT</td>
<td style="text-align: left;">2025-03-21 15:16:59 GMT</td>
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
    ##      Also assign letter grades to each contributor.  [{"who":"ben.baumer@gmail.com","num_commits":1,"first_commit":"2025-03-21 15:16:59 GMT","last_commit":"2025-03-21 15:16:59 GMT","days":0}]

\[1\] “
<p>
Okay, I’d be happy to analyze the contribution data you’ve provided!
</p>
<p>
Based on the data, we have one contributor:
</p>
<ul>
<li>
<strong><a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a></strong>
</li>
</ul>
<p>
Here’s a breakdown of the contribution and my assessment:
</p>
<ul>
<li>
<strong>Contribution:</strong> Ben made 1 commit on March 21, 2025. All
the commits occurred on the same day.
</li>
<li>
<strong>Analysis:</strong> Ben has made an initial contribution, which
is a good start. However, one commit is a relatively small contribution
to the project.
</li>
</ul>
<p>
<strong>Grade and Justification:</strong>
</p>
<ul>
<li>
<strong>Grade: C+</strong>
</li>
</ul>
<p>
<strong>Explanation:</strong>has submitted a commit, which demonstrates
their participation in the project. However, the limited number of
commits suggests a need for more active engagement.
</p>
<p>
<strong>Recommendations for Ben:</strong>
</p>
<ul>
<li>
I would encourage Ben to increase their contributions by exploring other
parts of the project.
</li>
<li>
Consider reviewing existing code, fixing bugs, or adding new features.
</li>
<li>
Active participation and further contributions are key to improving the
grade!
</li>
</ul>

”
