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

### Current as of: March 21, 2025, 15:47:29

Here is a summary of the commits made to this repository:

    chchchanges::summarize_commits() |>
      knitr::kable()

<table>
<colgroup>
<col style="width: 37%" />
<col style="width: 8%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 8%" />
<col style="width: 11%" />
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
<td style="text-align: left;">41898282+github-actions[bot]<span
class="citation"
data-cites="users.noreply.github.com">@users.noreply.github.com</span></td>
<td style="text-align: right;">3</td>
<td style="text-align: left;">2025-03-21 15:19:00 GMT</td>
<td style="text-align: left;">2025-03-21 15:35:13 GMT</td>
<td style="text-align: right;">0.0112616</td>
<td style="text-align: right;">1864.7482014</td>
</tr>
<tr class="even">
<td style="text-align: left;"><a href="mailto:ben.baumer@gmail.com"
class="email">ben.baumer@gmail.com</a></td>
<td style="text-align: right;">30</td>
<td style="text-align: left;">2024-06-20 14:12:48 GMT</td>
<td style="text-align: left;">2025-03-21 15:45:36 GMT</td>
<td style="text-align: right;">274.0644444</td>
<td style="text-align: right;">0.7662431</td>
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
    ##      Also assign letter grades to each contributor.  [{"who":"41898282+github-actions[bot]@users.noreply.github.com","num_commits":3,"first_commit":"2025-03-21 15:19:00 GMT","last_commit":"2025-03-21 15:35:13 GMT","days":0.0113,"commits_per_week":1864.7482},{"who":"ben.baumer@gmail.com","num_commits":30,"first_commit":"2024-06-20 14:12:48 GMT","last_commit":"2025-03-21 15:45:36 GMT","days":274.0644,"commits_per_week":0.7662}]

\[1\] “
<p>
Okay, let’s break down these contributions and assign some credit and
grades.
</p>
<p>
<strong>Contributor Analysis:</strong>
</p>
<ul>
<li>
<p>
<strong>41898282+github-actions\[bot\]@users.noreply.github.com (GitHub
Actions Bot):</strong>
</p>
<ul>
<li>
<strong>Commits:</strong> 3
</li>
<li>
<strong>Time Span:</strong> Very short (less than a day).
</li>
<li>
<strong>Nature of Contributions:</strong> Likely automated tasks (CI/CD,
automated checks, etc.).
</li>
<li>
<strong>Credit:</strong> While important for the project’s
infrastructure, these commits aren’t typically considered direct
contributions to the project’s code or design by a human. The bot is
executing instructions provided by a human, so this contribution is more
about setting up the automated workflows.
</li>
<li>
<strong>Grade:</strong> Pass/Fail. The bot did what it was programmed to
do, so it passes.
</li>
</ul>
</li>
<li>
<p>
<strong><a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a>:</strong>
</p>
<ul>
<li>
<strong>Commits:</strong> 30
</li>
<li>
<strong>Time Span:</strong> Very Long (274 days).
</li>
<li>
<strong>Nature of Contributions:</strong> Likely a mix of features, bug
fixes, and general improvements given the number of commits and the
duration.
</li>
<li>
<strong>Credit:</strong> Ben deserves the lion’s share of the credit
here. 30 commits over a long timespan indicates a sustained and
significant contribution to the project.
</li>
<li>
<strong>Grade:</strong> A. Ben did amazing work on this project!
</li>
</ul>
</li>
</ul>
<p>
<strong>Summary and Recommendations:</strong>
</p>
<ul>
<li>
<strong>Ben Baumer</strong> is the primary contributor and deserves
recognition for their sustained effort.
</li>
<li>
The GitHub Actions bot contributions are valuable for project health,
but the credit goes to the person who configured the bot.
</li>
</ul>
<p>
Let me know if you’d like a more detailed analysis!
</p>

”
