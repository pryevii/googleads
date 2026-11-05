# Bidding & Budget

*Converted from `PPC Co Pilot/Performance Max for Ecommerce/Setup & Structure/Bidding & Budget.rtfd`*

**Bidding When Running Feeder Strategy**

If you're running the Feeder Strategy (Standard Shopping + Non-Brand Search as cold traffic acquisition with Performance Max as middle/bottom funnel remarketing), your bidding approach needs to create a clear hierarchy between your campaigns.

**The Core Principle: PMax tROAS Must Be Higher Than Shopping**

When I say "higher," I mean your Performance Max campaign should have a **more aggressive (higher) tROAS target** than your Standard Shopping campaigns. This creates the desired behavior where Standard Shopping captures cold traffic at a lower efficiency threshold, while Performance Max focuses on warm audiences who convert at higher rates.

**The 20% Rule**

Set your Performance Max tROAS at least **20% higher** than your Standard Shopping tROAS. Calculate this as 20% of your Shopping tROAS added on top.

**Example:** If your Standard Shopping tROAS is set to 200%, then your Performance Max should be at least 240% (200% × 1.20 = 240%).

**Feeder Strategy tROAS Examples:**

![ba0bac0cb57b4da283569467c0a6a60f48a20610c8704f29b325ed5e059afdee.png](Bidding%20%26%20Budget.assets/ba0bac0cb57b4da283569467c0a6a60f48a20610c8704f29b325ed5e059afdee.png)

💡 **Pro Tip:** *Play around with these percentage differences. We find 20% higher to be a good starting point, but some accounts perform better with 25-30% separation. Test and cross-reference with your backend new customer acquisition data.*

**Why This Works**

The idea behind the Feeder Strategy is that you're acquiring cold, new customers through Standard Shopping campaigns, and Performance Max becomes your middle-of-funnel and bottom-of-funnel remarketing back channel. It "feeds" on the warm audience traffic pool of those new customers or cold traffic generated from the Shopping campaign who didn't buy right away—those who clicked but didn't convert that same day.

By setting a higher tROAS on PMax, you're telling Google: "Only spend money on highly efficient conversions." This naturally pushes PMax toward warm, high-intent traffic while your Shopping campaigns do the heavy lifting of new customer acquisition.

**Budget Allocation for Feeder Strategy**

The goal is to push more budget into Standard Shopping for new customer acquisition (cold traffic) and use Performance Max as a remarketing middle-of-funnel component.

**Recommended Budget Split:**

- **70-80% of budget** allocated to Standard Shopping
- **20-30% of budget** allocated to Performance Max

This is not a hard rule. If your PMax is performing exceedingly well at 30% budget allocation, don't be afraid to increase it. The key is cross-referencing with what you see on new customer acquisition on the backend.

**Transitioning to Feeder Strategy**

When we implement the Feeder Strategy, we don't normally hard-switch to 80% Shopping / 20% PMax right away. Usually it's a slow transition:

1. Gradually ramp up Standard Shopping budget
2. Simultaneously decrease PMax spend as Shopping starts to pick up
3. Monitor backend new customer acquisition metrics throughout
4. Adjust the ratio based on actual performance data

**Bidding When NOT Running Feeder Strategy**

If you're not running the Feeder Strategy and Performance Max is your primary campaign (or you're just getting started), here's how to approach bidding and optimization.

**Phase 1: Learning Phase (First 30 Days)**

In the beginning, you're typically going to bid to get volume. The goal is reaching **30-50 conversions per month**. During this phase, expect unprofitable or underwhelming performance—this is normal.

**Starting Bid Strategy Options:**

- **Max Conversion Value** (no tROAS cap) - Standard approach

Let the campaign run for **1-4 weeks** to collect enough data before making changes.

**Phase 2: Setting Your Initial tROAS**

After the learning phase, switch to tROAS bidding. **Critical rule:** Set the tROAS to what the campaign is *already achieving*, not what you wish it would hit.

**⚠️ Warning: If your campaign is hitting 250% ROAS, you cannot just flip to a 400% tROAS target. This will kill the campaign. Smart Bidding doesn't respond well to dramatic changes.**

**Correct Approach:**

1. Check your current ROAS performance (e.g., 200%)
2. Set tROAS to current performance OR slightly higher (180-200%)
3. Wait 1-2 weeks for the campaign to stabilize
4. Incrementally increase tROAS toward your goal

**Phase 3: Optimization - Two Paths Forward**

Once your campaign has stabilized and is hitting around your tROAS goal while generating conversions, you have two optimization options:

**Option A: Scale Volume at Current Performance**

If you're satisfied with your current ROAS and want more conversions at that efficiency level, start increasing your budget in **10-20% increments**.

**Option B: Improve Efficiency**

If you need better ROAS and can't live with current performance, start incrementally increasing your tROAS target in **10-20% increments.**

**⚠️ Caution: If you're only getting 30 conversions per month, increasing tROAS too aggressively can hurt you. If Google decreases that 30 conversion volume, you could suffocate the campaign. Be confident before making this change.**

💡 **Pro Tip:** *Normally you're either adjusting bids OR adjusting budgets—not both at the same time. Make one change, then wait up to a week or longer to see what happened. If you adjust bid and budget simultaneously, you'll second-guess yourself on what caused any problems.*

**Controlling ROAS With Budget**

Budget is one of your primary levers for controlling Performance Max behavior. Here's how to use it effectively:

**When Increasing Budget**

If your campaign is hitting your desired ROAS goal and you are limited by budget, you might notice when you increase budget, **the ROAS will dip**. This is due to Google expanding your audience reach.

**What to do:**

- Give it 1-2 weeks to work the new data out at this higher spend range
- Monitor performance—sometimes it stabilizes back to target
- If it doesn't recover, decrease budget back (see below)

**When Decreasing Budget**

If your campaign struggles to hit ROAS goal with increased budget, start decreasing your budget back. This will **force Smart Bidding to decrease your audience reach** to what it knows works best—the low-hanging fruit.

Sometimes a smaller, more focused budget delivers better efficiency than a larger budget that forces Google to expand into less qualified audiences.

**Golden Rules for Smart Bidding**

![40d538bdf1444b82a35fd5047b60284dd782de4e03304a9d9d6f011fee04d7cb.png](Bidding%20%26%20Budget.assets/40d538bdf1444b82a35fd5047b60284dd782de4e03304a9d9d6f011fee04d7cb.png)

**Quick Reference: Bidding Decision Tree**

**Use this decision tree to determine your next move:**

**Scenario 1: Campaign is hitting ROAS goal**

- Want more volume? → Increase budget 10-20%
- Want better efficiency? → Increase tROAS 10-20%
- Happy with both? → Leave it alone!

**Scenario 2: Campaign is below ROAS goal**

- Just increased budget? → Wait 1-2 weeks or decrease budget
- tROAS set too high? → Lower tROAS to match actual performance
- Getting <30 conversions/month? → Consider Max Conv Value (no cap)

**Scenario 3: Campaign is above ROAS goal**

- Conversion volume is low? → Decrease tROAS to give Google more room
- Conversion volume is good? → Increase budget to scale

**Scenario 4: Running Feeder Strategy**

- PMax tROAS should be 20%+ higher than Shopping tROAS
- Budget split: 70-80% Shopping, 20-30% PMax
- Always cross-reference with backend nCAC data

**Summary**

Bidding and budget management in Performance Max requires patience and a systematic approach. Whether you're running the Feeder Strategy or optimizing a standalone PMax campaign, remember these core principles:

1. **Smart Bidding hates big swings.** Work in 10-20% increments and give changes time to stabilize.

1. \*\*\**This is relative to the amount you are spending. If you only are spending $50 per day you can move up in larger percentage for example $50 → $100 would not be unusual. When you start spending $100s per day or even $1,000s per day the 10-20% increment recommendation really needs to be followed*

2. **Match tROAS to reality.** Set targets based on what the campaign is actually achieving, not what you hope for.
3. **One change at a time.** Adjust either bid or budget, never both simultaneously.
4. **Cross-reference with backend data.** Google Ads metrics don't tell the whole story—always verify with actual new customer acquisition data.
5. **Budget controls reach.** Increasing budget expands audience (may lower ROAS). Decreasing budget focuses on best performers.

The key to success is treating bidding and budgeting as an ongoing optimization process, not a one-time setup. Monitor, adjust in small increments, cross-reference with backend data, and repeat.
