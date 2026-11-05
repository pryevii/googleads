# Product Feed

*Converted from `PPC Co Pilot/Performance Max for Ecommerce/Optimization/Product Feed.rtfd`*

**Required feed attributes**

- id (Unique identifier for each product)
- title (Product title)
- description (Product description)
- price (Product price)
- availability (Product availability)
- link (Product URL)
- image\_link (Product image URL)
- brand (Product brand)
- gtin (Global Trade Item Number)

**Optional feed attributes**

**[Recommended]** = Highly impactful, prioritize these

**Core Identifiers**

- **mpn** - Manufacturer Part Number **[Recommended]**
- **product\_type** - Your internal product categorization **[Recommended]**
- **google\_product\_category** - Google's standardized category **[Recommended]**
- **item\_group\_id** - Groups product variants (shares reviews/social proof) **[Recommended]**

**Product Details**

- **color** - Product color
- **size** - Product size
- **gender** - Target gender (male, female, unisex)
- **age\_group** - Target age group (adult, kids, toddler, infant, newborn)
- **material** - Product material
- **pattern** - Product pattern
- **weight** - Product weight

**Additional Info**

- **condition** - Product condition (new, refurbished, used)
- **shipping** - Product-specific shipping info
- **occasion** - Product occasion (birthday, wedding, etc.)
- **scent** - Product scent (for applicable products)
- **features** - Product features (bullet points)

**Image Attributes**

- **additional\_image\_link** - Additional product images (up to 10) **[Recommended]**

- Use for lifestyle variations
- Use for different angles
- Google tests these across placements

**Strategic Segmentation**

- **custom\_label\_0** - Custom label (e.g., margin tier) **[Recommended]**
- **custom\_label\_1** - Custom label (e.g., best sellers) **[Recommended]**
- **custom\_label\_2** - Custom label (e.g., seasonal) **[Recommended]**
- **custom\_label\_3** - Custom label (e.g., price tier) **[Recommended]**
- **custom\_label\_4** - Custom label (e.g., new arrivals) **[Recommended]**

**Biggest Needle Movers**

- **Price** 🔥🔥🔥🔥🔥

- Always wins (but often can't be changed due to MAP pricing)

- **Title** 🔥🔥🔥🔥🔥

- Bake in top performing keywords

- **GTIN** 🔥🔥🔥

- Critical for comparison searches & exact product matching

- **Image** 🔥🔥

- Lifestyle images can get 2-3x CTR

- **Description** 🔥

- Important but focus 80% effort on titles, 20% on descriptions

- **Category** 🔥

- Often auto-assigned by Google if you have valid GTIN

**⚠️ Critical Reminder**

**Check your Merchant Center Diagnostics tab WEEKLY**

- Go to: Products → All Products → Needs Attention → View History

Fix disapprovals immediately - they kill performance

**Price**

**The Reality**

- If you're 20% cheaper for the same product, you win regardless of feed quality
- Price is often outside your control (MAP pricing, margin constraints)
- Focus on what you CAN control (title, images, attributes)

**Price Guidelines**

✅ **DO THIS:**

- Be competitive within your market
- Use sale\_price attribute for promotions
- Keep pricing consistent with your website

❌ **NEVER DO THIS:**

- Price baiting (low price in feed, higher at checkout)
- Fake sale prices
- Misleading pricing tactics
- Google will catch you

**Title**

**Why Titles Matter Most**

- **Top ranking signal** for Google Shopping
- First 30-70 characters show in snippet (most critical)
- Full 150 characters used by Google for matching
- **Word order matters** - front-load your best keywords

- Google can automatically shift keywords around depending on search

**How to Find Your Best Keywords**

1. Go to Google Ads → Shopping Campaign
2. Click: Insights & Reports → Search Terms
3. Filter by: Conversions
4. Find patterns in what's actually converting
5. Use these exact terms in your titles (front-loaded)

**Title Structure by Product Category**

![339c34e93d1b4f7b93a240d2a5acc3e3c93f27e0868b4ef0a9f003b7c2deebee.png](Product%20Feed.assets/339c34e93d1b4f7b93a240d2a5acc3e3c93f27e0868b4ef0a9f003b7c2deebee.png)

**Title Optimization Rules**

✅ **DO THIS:**

- Front-load your highest-converting keywords
- Use natural language (how people actually search)
- Include size, color, gender when relevant
- Match the structure to how YOUR customers search
- Test and iterate based on search terms data

❌ **NEVER DO THIS:**

- ALL CAPS IN TITLES
- Excessive punctuation (!!!, \*\*\*, etc.)
- Keyword stuffing that doesn't make sense
- Generic titles without search-relevant terms
- Ignore your search terms report

**Title Optimization Case Study:**

Simply changing the Title from a generic title to an optimized title for this online furniture company lead to a 10x in clicks and impressions

**Old Title:** Ali Sofa in Oscar Sterling **New Title:** Kid & Pet Friendly Sectional Sofa | Washable | Ali in Oscar Sterling | Home Reserve

**Key Insight:** We added "kid & pet friendly" and "washable" because that's what was converting in search terms. Brand went to the back because Home Reserve isn't a household name.

![522463978d994e18af177ead1c84654f5d4d68abe50d4a45b0f5bd4f92a9da1c-md.png](Product%20Feed.assets/522463978d994e18af177ead1c84654f5d4d68abe50d4a45b0f5bd4f92a9da1c-md.png)

**Why It Matters**

- **Critical for exact product matching** in comparison searches
- Required for barcode scans and model number searches
- Missing/incorrect GTIN = invisible in high-intent searches
- Google heavily emphasizes this (more than 5 years ago)

**How to Find GTIN**

1. Ask your manufacturer or supplier
2. Use barcode lookup: <https://gepir.gs1.org/index.php/search-by-gtin>
3. Check product packaging (usually the barcode number)

**When GTIN Isn't Available**

For handmade, vintage, or custom products:

- Set identifier\_exists: no
- This tells Google the product legitimately doesn't have a GTIN
- Can be set via supplemental feeds or feed rules in Merchant Center

**Impact:** This one fix alone can unlock huge chunks of underperforming inventory.

**Image**

**The 2026 Image Strategy Has Changed**

**OLD APPROACH (2024):**

- White background only
- Studio photos
- Professional photoshoot required
- Expensive and time-consuming

**NEW APPROACH (2026):**

- White background for MAIN image (standardization)
- Multiple lifestyle variations via additional\_image\_link
- Use Google Product Studio (FREE in Merchant Center)
- Use AI generation (ChatGPT/Gemini) for lifestyle scenes
- Test what works, scale winners

**Image Performance Data**

- Lifestyle images: **2-3x higher CTR** vs white background alone
- Multiple image variations: More placement opportunities
- Seasonal/themed images: Higher engagement during relevant periods

**The 2026 Image Workflow**

**MAIN IMAGE (image\_link)**

**Purpose:** Clean, professional, standardized for comparison shopping

**Requirements:**

- White or transparent background
- High resolution (minimum 800x800px)
- Product clearly visible and centered
- No watermarks or text overlays
- No hands, models, or props (unless product requires demonstration)

**How to Create:** Use Google Product Studio's **"Remove Background"** feature if needed:

1. Go to Merchant Center → Creative Content → Product Studio
2. Click "Remove background" tab
3. Upload your product image
4. One-click background removal
5. Add to Merchant Center as main image

**ADDITIONAL IMAGES (additional\_image\_link)**

**Purpose:** Lifestyle context, emotional connection, higher CTR

**Strategy:** Create 3-5 lifestyle variations per product using:

**Option 1: Google Product Studio (FREE)**

**Access:** [merchants.google.com/mc/productstudio](http://merchants.google.com/mc/productstudio)

**Features:**

1. **Generate Scene** - AI creates lifestyle backgrounds

- Seasonal themes (Christmas, Summer, Black Friday)
- Studio settings (modern, rustic, minimalist)
- Room contexts (living room, kitchen, outdoor)
- 4 variations generated per prompt

2. **Increase Resolution** - Upscale low-quality images
3. **Animate Images** - Turn static photos into short videos
4. **Generate Video** - Create product videos from images

**How to Use:**

1. Go to Product Studio in Merchant Center
2. Select "Generate Scene"
3. Upload your white background product image
4. Describe the scene you want:

- *Example:* "Product photography of a sectional sofa in a modern living room with natural lighting, hardwood floors, contemporary decor, and large windows"

5. Or choose a pre-made theme template
6. Generate 4 variations
7. Add best performers to Merchant Center as additional images

**Best Practices for Product Studio:**

- ✅ Use products with clean white backgrounds as input
- ✅ Center your product in the image
- ✅ Leave white space around the product
- ✅ One main product per image (not multiple products)
- ✅ No hands, models, or people in the input image
- ✅ Describe the scene in detail (lighting, surroundings, style)

**Option 2: AI Image Generation (ChatGPT/Gemini)**

**Cost:** $20/month (ChatGPT Plus or Gemini Advanced)

**When to Use:**

- You have a lifestyle image that performed incredibly well
- You want to recreate that scene for other products
- You need more creative control than Product Studio offers

**Workflow:**

**Step 1: Simple Scene Creation**

`Upload your white background product image

Prompt: "Create a modern living room scene with this exact product. Use natural lighting, contemporary furniture, and a neutral color palette. The product should be the focal point, clearly visible and accurately represented. Style: professional product photography."`

**Step 2: Reference-Based Recreation (Advanced)**

`Upload TWO images:

1. Your product (white background)
2. A winning lifestyle image from past campaigns

Prompt: "Create a living room scene from the first image (my product) similar to the second image (reference scene). Match the lighting style, composition, and room aesthetic while keeping my exact product accurately represented."`

**Step 3: Quality Check (CRITICAL)** Before using ANY AI-generated image, verify:

- ❓ Is this MY exact product? (not a similar approximation)
- ❓ Are the proportions accurate?
- ❓ Are the colors true to my product?
- ❓ Would I be comfortable if a customer ordered based on this image?

**⚠️ ETHICAL WARNING:** Do NOT use "close enough" AI images that aren't your actual product. This is misleading advertising and will damage customer trust. If the AI can't accurately represent your specific product, don't use it.

**Image Testing Strategy**

**Phase 1: Top 20% of Products (Week 1-2)**

- Start with highest revenue products
- Create 1 white background (main) + 3-5 lifestyle variations (additional)
- Use Product Studio for speed and zero cost

**Phase 2: Performance Analysis (Week 3-4)**

- Track CTR by product before/after
- Identify which scene types perform best
- Document winning formulas

**Phase 3: Template & Scale (Month 2+)**

- Use winning scene styles as templates for similar products
- Expand to next 30% of catalog
- Continuously test seasonal variations

**Tracking Metrics:**

- Click-through rate (CTR)
- Conversion rate
- Revenue per click
- Cost per click (should decrease with better CTR)

**Description**

**The 80/20 Rule**

- Spend **80% of effort on titles**
- Spend **20% of effort on descriptions**
- Descriptions matter, but title optimization moves the needle more

**Description Best Practices**

✅ **DO THIS:**

- Include primary converting keywords naturally
- Use secondary/alternative keywords
- Write in natural, readable sentences
- Include key features and benefits
- Keep it accurate and honest

❌ **DON'T DO THIS:**

- Keyword stuffing
- Copying your competitor's descriptions
- Over-optimizing at the expense of titles
- Using all caps or excessive punctuation

**Priority Order:**

1. Fix titles first (biggest impact)
2. Ensure descriptions are decent (but don't obsess)
3. Move on to images and other optimizations
   ![251c5a1ab15a4d1b8828b80de4b6abc2caf95ebd0ac644bc9b2e73aaf9f32bf7-md.png](Product%20Feed.assets/251c5a1ab15a4d1b8828b80de4b6abc2caf95ebd0ac644bc9b2e73aaf9f32bf7-md.png)

**Category**

**Google's standardized taxonomy with 6,000+ categories**

**The Good News:** If you have valid GTINs, Google auto-assigns the category (you can leave it blank)

**When to Manually Set:**

- Products without GTINs
- Custom/handmade products
- When Google auto-assigns incorrectly

**Taxonomy:** <https://www.google.com/basepages/producttype/taxonomy.en-US.txt>

**PRODUCT\_TYPE**

**YOUR internal categorization for segmentation and reporting**

**Difference from Google Product Category:**

![9532f2c028db472998ce287459008e0b2cf76bbcffb941698b5e6b74868ef41e.png](Product%20Feed.assets/9532f2c028db472998ce287459008e0b2cf76bbcffb941698b5e6b74868ef41e.png)

**Why This Matters:**

- Use product\_type for strategic custom labels
- Segment campaigns by YOUR business logic
- Bid differently on categories that matter to YOUR business

**Custom Labels**

**Why Custom Labels Matter**

**Not a feed quality signal**, but critical for campaign management and control.

**The Power of Custom Labels**

Without them: Your Performance Max campaign optimizes across your entire catalog randomly

With them: You can create separate campaigns for:

- High-margin bestsellers (4x ROAS target, premium creative)
- Clearance products (1.5x ROAS target, volume focus)
- New arrivals (2.5x ROAS target, awareness creative)
- Seasonal products (aggressive during peak season)

**This is the difference between letting the algorithm do whatever it wants vs. giving it strategic direction.**

**Recommended Custom Label Strategy**

![02a9c6f0c93f454c9e11c75242d2028baaa5b1e5bf8c4d5b97b8153f567cd4f1.png](Product%20Feed.assets/02a9c6f0c93f454c9e11c75242d2028baaa5b1e5bf8c4d5b97b8153f567cd4f1.png)

**Implementation Examples**

**Example 1: Margin-Based Segmentation**

High Margin Products (>40%): custom\_label\_0 = "High Margin" Medium Margin (20-40%): custom\_label\_0 = "Medium Margin" Low Margin (<20%): custom\_label\_0 = "Low Margin"

**Campaign Strategy:**

- High Margin PMax: Target 4x ROAS, premium creative, aggressive bidding
- Medium Margin PMax: Target 3x ROAS, standard creative
- Low Margin PMax: Target 1.5x ROAS, volume focus, clearance creative

**Example 2: Seasonal Segmentation**

Halloween Products: custom\_label\_2 = "Halloween" Christmas Products: custom\_label\_2 = "Christmas" Summer Products: custom\_label\_2 = "Summer"

**Campaign Strategy:**

- Ramp up Halloween campaign in September-October
- Pause it in November
- Switch budget to Christmas campaign
- No wasted impressions on off-season products

**Custom Label Best Practices**

✅ **DO THIS:**

- Plan your segmentation strategy before implementing
- Keep it simple (3-5 custom labels is plenty)
- Document what each label means
- Use consistent naming conventions
- Update seasonally if needed

❌ **DON'T DO THIS:**

- Use all 5 labels just because you can
- Create overly complex segmentation schemes
- Forget to document your label system
- Change label meanings mid-campaign

**Warning:** Too many custom labels make campaign management harder, not easier. Keep it strategic and simple.

**Other Attributes**

**Brand**

**Why It Matters:**

- Critical for brand-specific searches
- Missing/incorrect brand = you lose entire segment of high-intent traffic
- Example: Someone searches "Nike running shoes" - Google needs to see "Nike" clearly in brand attribute

**Other Attributes**

Add as many relevant product attributes to your product feed as possible. It tells Google what your product is and exactly what characteristics it has. That goes a long way in helping them show your listing in the right place and for the right searches.

Google, after all, can’t take a look at a picture and quite tell the difference between a pair of black and white running shoes and a penguin laying flat. (At least not yet). It’s up to us to explain what the products are.

And remember that the more attributes you give to your products, the more opportunities you have to show up when users apply filters to their Shopping results.

![1ac1c44182e2472c941a2c739d127e50dad571ca090d4019af16aa210de2e994-md.png](Product%20Feed.assets/1ac1c44182e2472c941a2c739d127e50dad571ca090d4019af16aa210de2e994-md.png)

**Recommended Tools**

Some of the top data feed management tools to consider are:

- [Channable](https://www.channable.com/) (my #1 recommendation)
- [Feednomics](https://feedonomics.com/) (expensive - more enterprise level)
- [DataFeedWatch](https://www.datafeedwatch.com/) (great inexpensive tool but will require some learning to use)
