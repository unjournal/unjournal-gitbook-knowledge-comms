# Evidence: what happens after an Unjournal evaluation?

Do authors respond to our evaluations? Do they revise their papers? And is there evidence that the work affects research or decisions?

We track these as separate outcomes. A public response is directly observable. A later paper revision is harder to attribute, because authors also receive journal reports, conference feedback, and comments from coauthors. Changes in funding or policy are harder still to observe and attribute.

{% hint style="info" %}
The most detailed and regularly updated source is our [author-response and paper-revision dashboard](https://valentinklotzbuecher.github.io/llm-uj-research-eval/paper_response_analysis.html). It includes the underlying classifications, methods, code, and caveats. The figures below are from the April 2026 version.
{% endhint %}

## Current evidence

| Outcome | What we have observed |
|---|---:|
| Evaluation packages tracked | 57 |
| Papers manually assessed for updating | 22 |
| Clear evidence of substantive updating | 5 of 22 |
| Authors stating an intention to update | 7 of 22 |
| At least some positive update signal | 15 of 22 |
| Papers with a formal or informal author response | 19 |
| Formal written author responses | 16 |

These counts do not all use the same denominator. In particular, many response and revision records have not yet been coded. “Not yet assessed” should not be read as “no response” or “no revision.”

## Three public examples

### Water treatment and child mortality

We commissioned two evaluations of a meta-analysis and cost-effectiveness analysis of water treatment, a paper relevant to major decisions about chlorination funding. The evaluators broadly supported the importance of the work while raising issues about study inclusion, transparency, interpretation, and the cost-effectiveness analysis.

The authors published a [detailed response](https://unjournal.pubpub.org/pub/bgh98s2i/release/1). The [evaluation package](https://unjournal.pubpub.org/pub/evalsumwatertreatment/release/4) records that they also updated the working paper in response, while retaining the headline result. This is our clearest public example of an evaluation leading to a documented author response and changes to an important paper.

### Artificial intelligence and economic growth

In evaluating Philippe Aghion, Benjamin Jones, and Charles Jones's paper on AI and economic growth, an evaluator identified an error in a proof of a central result. The authors acknowledged the problem and confirmed a corrected proof. The main result was preserved, but the reasoning supporting it was corrected and made clearer.

The [evaluation package and author response](https://unjournal.pubpub.org/pub/aimetrics/release/9) provide the public record. This example matters because the contribution was not a change in the headline conclusion; it was a direct check on whether an influential result was actually supported.

### Happier Lives Institute's cost-effectiveness work

Our evaluation of Happier Lives Institute's analysis of StrongMinds and Friendship Bench led to a detailed, 20-page [public response from HLI](https://www.happierlivesinstitute.org/hli-public-response-to-unjournal-evaluation/). HLI agreed with some points, disputed others, and documented its reasoning in detail. The [evaluation package](https://unjournal.pubpub.org/pub/evalsumstrongminds/release/5) keeps the evaluations, ratings, and response connected.

This is strong evidence of substantive engagement, not by itself evidence that the evaluation caused a later paper revision or a funding change.

## Related evidence from Pivotal Questions work

Our March 2026 wellbeing workshop provides a different kind of evidence. Nine participants completed the post-workshop survey, out of roughly 27 attendees. Seven reported improved understanding of practitioner priorities and six reported improved understanding of how academic research could be useful. Several described specific changes in beliefs or research priorities.

The [public survey report](https://uj-wellbeing-workshop.netlify.app/survey-results) includes the full aggregate results and both positive and critical feedback. These are self-reports from a small, selected sample. They provide evidence of engagement and reported belief or priority changes, not an estimate of causal impact or downstream effects.

## Paper-comparison analysis

For a smaller subset, we compared pre- and post-evaluation PDFs and used an LLM to assess whether major changes plausibly addressed evaluator comments.

* Of 22 papers with fetchable DOIs, 8 had meaningful text changes and a matched evaluation suitable for analysis.
* Three of these were already manually confirmed as updates.
* Among the other five, the model classified two as having at least 30% of major changes likely driven by evaluator feedback.
* The median estimated share across all eight papers was 22%.

These figures are exploratory. PDF extraction is noisy, the sample is small and selected, and LLM attribution is not independent confirmation. We report them because they help target cases for human review, not because they establish a causal average effect.

## How to interpret the evidence

We use a simple evidence ladder:

1. **Engagement:** an author responds publicly or discusses the evaluation.
2. **Research updating:** an author states an intention to revise, or a later version contains a change plausibly linked to the evaluation.
3. **Decision use:** a funder, policymaker, or research organization reports using the evaluation or changing a view or action.
4. **Downstream effects:** the resulting decision improves outcomes.

The public evidence is currently strongest for engagement and research updating. We have some self-reported evidence of decision use, but it is less systematic and often cannot be made public. We generally cannot identify downstream effects with confidence.

## Limits and next steps

* **No clean counterfactual:** evaluated papers are not randomly selected, and authors who engage may be more open to feedback than other authors.
* **Multiple sources of feedback:** a post-evaluation revision may also reflect journal reports, workshops, or coauthor discussions.
* **Incomplete coding:** many papers have not yet been manually checked, and later versions may be unavailable or paywalled.
* **Outcome selection:** a response can be useful even when the author disagrees, and an evaluation can add confidence without prompting a revision.

We are continuing to verify specific evaluator suggestions against later paper versions, record author responses consistently, and link each claim to a public evaluation package or response where possible. We also report [author survey results](https://unjournal.github.io/unjournaldata/posts/author-survey-2026/) separately; these are useful but subject to small-sample and response-selection concerns.
