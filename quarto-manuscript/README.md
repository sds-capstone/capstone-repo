
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

Here is a summary of the commits made to this repository:

``` r
chchchanges::summarize_commits() |>
  knitr::kable()
```

| who | num_commits | first_commit | last_commit | days | commits_per_week |
|:---|---:|:---|:---|---:|---:|
| <ben.baumer@gmail.com> | 16 | 2024-06-20 14:12:48 GMT | 2025-01-21 18:04:18 GMT | 215.1608 | 0.520541 |

The following analysis is automated via [Google
Gemini](https://en.wikipedia.org/wiki/Gemini_(chatbot)) and the
[`chchchanges`](https://github.com/beanumber/chchchanges) package.

``` r
chchchanges::summarize_git_with_llm(
  show_prompts = TRUE, 
  user_prompt = "Also assign letter grades to each contributor. "
) |>
  markdown::mark()
```

    ## Using model = "gemini-1.5-flash".
    ## System prompt: You are a friendly, supportive, college professor 
    ##     evaluating student contributions to a git repository.
    ## 
    ## Prompt: Analyze the following data from a git repository 
    ##     and tell me who deserves what credit for 
    ##     contributing to the project. 
    ##      Also assign letter grades to each contributor.  [{"who":"ben.baumer@gmail.com","num_commits":16,"first_commit":"2024-06-20 14:12:48 GMT","last_commit":"2025-01-21 18:04:18 GMT","days":215.1608,"commits_per_week":0.5205}]

\[1\] “
<p>
Okay, let’s analyze the contribution data for this project. We only have
data for one contributor, so the analysis will be focused on them.
</p>
<p>
<strong>Contributor:
<a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a></strong>
</p>
<ul>
<li>
<strong>Commits:</strong> 16
</li>
<li>
<strong>Contribution Span:</strong> June 20, 2024 to January 21, 2025
(approximately 7 months)
</li>
<li>
<strong>Commit Frequency:</strong> 0.52 commits per week.
</li>
</ul>
<p>
<strong>Analysis:</strong>
</p>
<p>
A total of 16 commits over seven months indicates a consistent, though
not overwhelmingly frequent, level of engagement. The frequency suggests
a steady, possibly part-time, contribution to the project. It’s not a
huge volume of code, but it’s certainly meaningful, assuming the commits
are of good quality.
</p>
<p>
It’s impossible to evaluate the <em>quality</em> of contributions based
on the provided data. Factors such as code reviews, the complexity of
the commits, and the impact of the changes are not captured here. If the
commits are mostly small bug fixes, then the impact is less than if they
were large features that addressed substantial elements of the project’s
functionality.
</p>
<p>
<strong>Grade:</strong> Based purely on the provided commit data, I
would give
<a href=\"mailto:ben.baumer@gmail.com\">ben.baumer@gmail.com</a> a
<strong>B-</strong>. This reflects consistent contribution over a
considerable period, but also points to the need for more substantial
contributions to warrant a higher grade. To improve their grade, they
could increase their commit frequency or work on larger, more impactful
features.
</p>
<p>
<strong>Recommendations:</strong>
</p>
<ul>
<li>
<strong>More frequent commits:</strong> While consistency is good,
increasing the frequency of commits, even if they are smaller, can
indicate more active engagement.
</li>
<li>
<strong>Larger-scale contributions:</strong> Tackling larger features or
refactoring sections of the codebase would make a substantial impact on
their grade.
</li>
<li>
<strong>Code review engagement:</strong> Actively reviewing other
contributors’ code demonstrates teamwork and understanding of the
project’s overall structure.
</li>
</ul>
<p>
To provide a more complete and accurate evaluation, I need more
information such as:
</p>
<ul>
<li>
<strong>Code review participation:</strong> How many pull requests did
they review?
</li>
<li>
<strong>Code quality:</strong> Were the commits well-written, tested,
and documented?
</li>
<li>
<strong>Project impact:</strong> Did the commits resolve critical bugs
or add significant new features?
</li>
<li>
<strong>Size and complexity of commits:</strong> Were they small fixes
or larger changes?
</li>
</ul>
<p>
With this additional context, I can give a much more informative and
fair grade reflecting the quality and impact of their contributions.
</p>

”
