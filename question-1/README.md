# Question 1

Predict the **total AI Pipe cost in US dollars for 2–8 November 2026**, using UTC dates. Add the seven daily `total.spend_usd` values from the [public usage feed](https://stats.aipipe.org/usage.json).

The market offers 17 cost ranges, from 0–1¢, 1–2¢, 2–5¢ and higher, through $500–$1,000 and $1,000 or more. Each range includes its lower limit and excludes its upper limit: exactly 1¢ belongs in 1–2¢. The total is not rounded before choosing the winning range.

Choose a cost range in the market. Read new reports, update your prediction, and explain your reasons. Trading closes on **9 November at 00:00 UTC**. Start early: your marks depend on how long you hold each prediction and how you use new evidence. Trading credits are optional practice points.

> Unexpected token 'U', "Unauthorized" is not valid JSON Reload this exam to try again.

## Rules: what counts, and when

- The target is the **sum of seven completed UTC days**, not an average, token count, number of users, or your own bill. One cent is $0.01. The market uses the unrounded total, so exactly $2 belongs in $2–$5, not $1–$2.
- Use each day's `total.spend_usd` once. Do not add the provider subtotals again. Free models, personal provider keys, and unmetered requests are outside this feed's totals.
- Before 2 November, recent costs are comparison data. During the week, the displayed total includes only completed target days. Today's incomplete row is excluded. Missing or unavailable data is not zero.
- The feed is normally published every six hours; the market checks hourly and retains completed days as they leave the seven-day feed. Reports can be revised. Trading pauses if the latest report is more than 12 hours old.
- Trading ends on **9 November, 00:00 UTC (05:30 IST)**. The teacher sets the result during 9–16 November, once all seven completed daily costs are available. A missing day delays the result; it is never guessed as zero.

## How prices, shares, and credits work

- You begin with **1,000 practice credits**. These are not US dollars or real money. Each share pays **1 credit if its range wins, 0 otherwise**. That is the payout, not your profit: subtract what you spent.
- An automated market maker, called LMSR, quotes trades without needing another student to take the opposite side. Buying a range raises its price and lowers the others; selling does the reverse. A large order changes its own price as it executes.
- A price of 0.20 credits per share can be read as a market-implied chance of about 20%. All 17 ranges start equally likely (about 5.9% each). Those starting prices are not a forecast from usage data. Later prices reflect trades, not a guaranteed result.
- Choose **Spend credits** for a fixed budget, or **Buy shares** for a fixed quantity. The displayed share price times your quantity is only an estimate because prices move during the order. Always use **Review trade**, read the total cost and quantity, then **Confirm trade**.
- If another action changes the quote, review it again. Your amount must not be silently changed. In **Your shares**, sell some or all of an owned holding by explaining why, reviewing the credits returned, then confirming. You cannot sell shares you do not own or spend credits you do not have.
- You may make **five trades in any rolling four hours**, with a further cap of **20 per UTC day**. Buys and sales both count. There is no fixed wait between trades while slots remain. One trade may move any range's chance by at most **15 percentage points**; an oversized order is rejected.

## How to earn marks

**Trading is optional.** Choose your range, write a reason, leave credits at 0, and press **Save prediction**. You can do this even after spending all your credits. Saving a prediction uses no trading slot.

- **10% participation:** save a prediction before trading closes.
- **45% accuracy over time:** each prediction counts for how long you kept it during the full market window. Time before your first answer earns no accuracy credit. In the page's single-choice mode, a wrong range gets no accuracy credit for that time, even if it is next to the winning range.
- **22.5% early participation:** the earlier your first prediction, the larger this component.
- **22.5% evidence-based revision:** change your prediction at least once after a genuinely different source report arrives, and explain the change. Refreshing the same report, using dummy data, or repeating the same answer does not qualify.

Reasons need at least **3 words and 15 characters**, up to 1,000 characters. More words or trades do not earn more marks. The computer checks these rules; it does not use AI to judge the quality of your writing. Credit profits do not increase your marks.

A confirmed buy also saves the prediction selected in that form. A sale changes your holdings but does not save a new prediction: use **Save prediction** separately when your view changes. Check **My answers** after every action. Notes saved after the close cannot improve your marks.

## Strategies and useful habits

1. **Start with a baseline.** Estimate a typical completed day's cost, then multiply by seven. For example, a hypothetical $2 per day suggests $14 for the week, in the $10–$20 range. State how much data supports your estimate.
2. **Update the remaining days.** During the week, estimate `completed target-day total + remaining days × expected daily cost`. For example, $8 across three completed days plus four more days at $2 suggests $16. Consider deadlines, weekends, model choices, and changing demand rather than assuming every day will be identical.
3. **Track uncertainty near a boundary.** A $9.90 estimate is close to $10, so a small change could move the answer to another range. Explain a plausible low and high total. Revisit your choice when new evidence arrives; do not change it just to generate activity.
4. **Compare your belief with the price.** If you think a range has a 20% chance, its expected payout is 0.20 credits per share. A lower average purchase price may offer value; a higher price may not. This is a way to reason about a trade, not a promise of profit. Review the whole order because buying pushes the price upward.
5. **Keep room to act.** Start with small trades and retain credits and trading slots for later evidence. You can hold several ranges to spread trading risk, but your page prediction is still one selected range. Selling part of a holding can reduce risk or recover credits; it can also give up a later winning payout.
6. **Keep a clear record.** Write the dates and costs you used, your estimated total, and what would change your mind. Separate your evidence from the crowd's prices. Save early, then return for genuinely new reports.

## Things to avoid

- Do not confuse cents, US dollars, practice credits, or shares. Do not round the cost before choosing a range.
- Do not treat today's partial cost, missing data, or a pre-November comparison report as a completed target day.
- Do not chase the most popular range or buy a cheap range just because it looks cheap. Check the evidence and the price you would actually pay.
- Do not assume buying then immediately selling will return all your credits, or that the displayed sale estimate is guaranteed.
- Do not wait until the last day, spend all your credits at once, or use all five trade slots without a reason. More trades and forced answer changes do not improve your score.
- Do not spend real AI Pipe usage just to influence a market with practice credits.
- Keep your sign-in code private. Sharing your choice and sharing your reason are separate controls, private by default. You can change sharing later, but someone may already have copied what you shared.
- If a request is interrupted, check **My answers** and **Your shares** before submitting again. Do not repeatedly confirm an action whose result you have not checked.
- Do not submit your sign-in code as your answer. After settlement, get the signed **result token**, then Check and Save it here.

## What to submit

After the market's final result is set (9–16 November), copy your signed result token from the market and paste it below. Your sign-in code is not a result token. Until settlement, no final result token is available.

**Prediction market result token**
