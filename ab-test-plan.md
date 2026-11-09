# A/B Test Plan: Study & Sip Homepage Headline

## Page and change
I will test the main headline on my Study & Sip homepage, index.html.

- Version A: “Coffee shops to study in Iowa City”
- Version B: “Find Your Next Study Spot: Iowa City Coffee Shops Compared”

Only the headline will change. All other content, links, and formatting will remain the same.

## Hypothesis and reasoning
Version B will produce a higher percentage of AI visitors answering that they would click through to a study guide. It directly addresses the visitor and emphasizes comparing study spots, which may make the next step more appealing to students.

## Model and persona
I will use Chat GPT Model GPT-6.1 Sol Light for every trial, with the same settings and a fresh conversation each time. I will record the model/version and available settings before testing and keep them consistent.

Each visitor will play a University of Iowa undergraduate looking for a coffee shop where they can study alone for two hours.

## Page presentation and exact prompt
I will save the full homepage text for both versions before testing. Each trial will receive the same prompt below, followed by the full text of its assigned version. The headline will be the only difference. I will not tell visitors which version they received or describe my hypothesis.

“You are a University of Iowa undergraduate looking for a coffee shop in Iowa City where you can study alone for two hours. You have just landed on the following homepage. Based only on this page, would you click a link to explore one of its study guides? Answer Yes or No, followed by one sentence explaining your decision.

Homepage text:
[INSERT THE FULL TEXT OF THE ASSIGNED HOMEPAGE VERSION]”

## Random assignment
Before collecting responses, I will create 100 assignments containing 50 A labels and 50 B labels, randomly shuffle their order, and save the assignment list. I will run trials in that order.

## Primary outcome
The primary outcome is stated willingness to click through to a study guide. I will code Yes as 1 and No as 0. This measures stated intention, not actual clicks.

## Sample size and schedule
I will collect 100 completed trials, 50 per version. I plan to launch by November 17, 2026, and finish by November 24, 2026. I will complete the full sample regardless of preliminary results.

I will retain every output. Unclear responses and technical failures will be logged. Unclear answers will be marked missing, and any replacement trial will use the same assigned version in a fresh conversation.

## Analysis and decision rule
I will calculate the percentage answering Yes in each version and the difference, B minus A, in percentage points. I will use a two-sided Fisher’s exact test with a significance level of 0.05.

A higher Yes percentage for B with p < 0.05 will support my hypothesis. Otherwise, I will report insufficient evidence that B improves the outcome.

## Documentation and search protection
I will retain the committed plan, assignment list, screenshots, page versions, prompts, model details, dates, every output, raw data, analysis, and a dated issue log.

Before launch, I will publish Version B with a noindex tag and exclude it from the sitemap.

AI responses can help compare reactions under a controlled prompt, but they cannot establish how real students will behave.
