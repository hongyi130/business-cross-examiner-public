# Intake And Scorecard

Use this reference for Full审讯.

## Minimum Intake

Collect or infer these fields. If the user cannot answer, mark `unknown`.

| Field | Question |
|---|---|
| idea | What exactly is the business idea? |
| target_user | Who uses it? Be specific. |
| payer | Who pays? Is this person different from the user? |
| pain | What painful job does it solve? What happens if nothing changes? |
| offer | What is the concrete paid deliverable or outcome? |
| price | What price, pricing model, or budget category? |
| channel | Where will the first 10 qualified buyers come from? |
| assets | What unfair advantages, credibility, content, cases, relationships, or skills does the founder have? |
| constraints | Time, money, engineering, operations, emotional tolerance, or compliance constraints. |
| proof | Any prior sales, waitlist, inbound, repeated user behavior, or strong qualitative signal? |
| dirty_work | What repetitive unpleasant work must be done for this to live? |
| validation_window | How long is the test window? |

## Stage Field

Add one stage before scoring:

- **Idea-only**: concept with little evidence.
- **Offer-shaping**: target user or pain is known, paid offer unclear.
- **Validation**: external actions already happened.
- **Post-result**: user has validation data or non-execution data.

Stage determines the next decision state. Do not score an idea-only user as if they already had validation data.

## Decision Gate Field

Before scoring, identify:

- **当前卡口**: the one constraint deciding the next move.
- **后置风险**: real constraints that matter later or in parallel.
- **Verdict-changing unknown**: the missing fact most likely to change the conclusion.

If there is a validation mission, it must target the 当前卡口, not the most interesting topic. Red verdicts may end with stop, pause, or reframe instead of a mission.

## Scorecard

Score 0-3. Do not over-score unknowns.

Treat the score as triage, not truth. If the score conflicts with the concrete facts, explain why the facts override the score.

| Axis | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| Buyer pain | Vague interest | Nice-to-have | Clear pain | Urgent/frequent/expensive pain |
| Willingness to pay | No proof | Says interested | Has paid adjacent solutions | Pays or deposits now |
| Distribution | Unknown | Friends only | One credible channel | Repeatable channel with proof |
| Asset fit | Opposite of founder assets | Weak fit | Some fit | Moat sits in founder's strengths |
| Defensibility | Pure commodity | UI/prompt wrapper | Judgment/workflow/data edge | Compounding memory/cases/community |
| Operational fit | Requires unavailable capacity | Heavy mismatch | Manageable with tradeoffs | Fits current resources |
| Retention | One-off curiosity | Occasional use | Repeat workflow | Recurring habit or renewal reason |
| Speed to signal | Months before learning | Needs build first | Concierge test possible | Can sell or test this week |

Total: 0-24.

- **0-8 Red**: likely itch or fantasy. Do not build. Satisfy the itch cheaply or reframe.
- **9-15 Yellow**: possible wedge, not a business yet. Run a narrow validation.
- **16-20 Green-ish**: worth a time-boxed test. Keep scope small and define kill metric.
- **21-24 Strong**: rare. Still require dirty-work plan and kill metric.

## Verdict Confidence

Always state confidence:

- **Low**: fewer than 4 intake fields known.
- **Medium**: 4-8 fields known, but no behavior proof.
- **High**: clear buyer, offer, channel, and proof.

## Kill Metric Templates

Use behavior, not compliments.

- 14 days: get 3 paid deposits or paid calls from target users.
- 30 days: publish 6 specific teardown posts and get 10 qualified conversations.
- 30 days: manually deliver 5 concierge cases; at least 2 users ask for a second paid session.
- 60 days: convert 10 paying users and see at least 50 percent repeat usage.
- 90 days: reach 20 paying members and at least 50 percent weekly active participation.

## Result 回填

When the user returns after validation, ask:

1. What action was taken?
2. How many target users saw it?
3. How many responded?
4. How many paid, deposited, booked, or returned?
5. What words did users use unprompted?
6. What part did they ignore?
7. What was harder than expected?
8. What should be killed, narrowed, or doubled down?

Then update the verdict. Do not protect the old recommendation.

## 裁断卡 Template

Use this at the end of serious sessions:

```markdown
## 裁断卡
- Verdict:
- Confidence:
- Stage:
- Score:
- 当前卡口:
- 后置风险:
- User constraint:
- Verdict-changing unknown:
- Proceed condition:
- Living wedge:
- Do-not-build-yet:
- 7-14 day mission, if justified:
- Kill metric or revive condition:
- Return trigger/date, if any:
- 回填问题:
- Pattern to watch:
```
