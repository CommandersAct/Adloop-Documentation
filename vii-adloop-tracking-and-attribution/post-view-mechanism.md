# Post-View Mechanism

The post-view reattribution feature is a key component of the attribution models offered on our platform. It complements post-click attribution to provide a more comprehensive and precise view of your campaign performance. Integrated into all available models, including the Data-Driven model, post-view attribution enhances your analysis by accounting for the impact of advertising exposures that generate engagement, even without direct clicks.

***

#### **What is Post-View Attribution?**

Post-view attribution reallocates a portion of conversions initially attributed to "neutral" channels such as Direct Access and SEO to channels that have demonstrably contributed to advertising exposure and user engagement.\
It evaluates impressions and interactions (engagements) to quantify the indirect influence of campaigns on customer journeys.

***

#### **How Does Post-View Work Within Attribution Models?**

**Key Principles of Post-View Reattribution:**

1. **Complementary to Post-Click Attribution:**
   * Post-click focuses on conversions directly resulting from a click.
   * Post-view captures conversions influenced by advertising exposure without immediate interaction (click).
2. **Conversion Redistribution:**
   * Conversions attributed to SEO and Direct Access are partially reallocated to channels that delivered relevant exposures (impressions) or significant interactions (engagements).
   * These channels include social media, programmatic display, video campaigns, email, influencers, audio and affiliation.
3. **Multi-Touch Consistency:**
   * Each channel is analyzed daily to calculate its influence on conversions.

***

#### **Technical Details of the Post-View Mechanism:**

**Calculation Steps:**

1. **Data Collection:**
   * **Impressions:** The total number of impressions delivered by each channel.
   * **Engagements:** Channel-specific data such as completed videos, likes, email opens, shares, and comments.
2. **Engagement Coefficient Calculation:**\
   Each channel is assigned an "engagement coefficient" based on:
   * A weighting of various interaction types (e.g., a completed video carries more weight than a like).
   * A proportional distribution of impressions for channels with limited engagement data.
3. **Conversion Redistribution:**\
   The conversions to be reattributed are distributed among channels in proportion to their engagement coefficients, rewarding those that demonstrated significant contributions to engagement and memorization. The number of conversions to be reattributed is based on advertising intensity, calculated every day.

***

#### **Simplified Example of Application:**

{% hint style="info" %}
**Note:** For obvious reasons, Commanders Act cannot reveal the exact "secret sauce" of its algorithm. The following example is simplified to illustrate the general principles behind post-view reattribution.
{% endhint %}

Suppose we have 1,000 conversions initially over-attributed to Direct Access and SEO:

* **Channel A (Social Media):**
  * 10,000 impressions
  * 200 completed videos
  * 150 likes
* **Channel B (Programmatic Display):**
  * 15,000 impressions
  * No engagement data available.

**Simplified Calculations:**

1. **Engagement Scores per Channel:**
   * For Channel A:\
     (200 completed videos × weight 1.0) + (150 likes × weight 0.5) = 275
   * For Channel B:\
     No engagement data, so the score is 0.
2. **Total Weight per Channel:**
   * For Channel A:\
     Impressions (10,000) + Engagement Score (275) = 10,275
   * For Channel B:\
     Impressions (15,000) + Engagement Score (0) = 15,000
3. **Conversion Redistribution:**
   * For Channel A:\
     (10,275 ÷ Total Weight \[10,275 + 15,000]) × 1,000 conversions ≈ 407 conversions
   * For Channel B:\
     (15,000 ÷ Total Weight \[10,275 + 15,000]) × 1,000 conversions ≈ 593 conversions

***

{% hint style="success" %}
**Best Practice: Reconnect your sources promptly!** \
Ensure that data sources remain connected by promptly addressing any system alerts. A "downgraded mode" banner will appear if a temporary disconnection occurs and email alerts will be sent out, encouraging reconnection to maintain optimal data accuracy.
{% endhint %}

***

By seamlessly integrating direct and indirect performance metrics, post-view attribution enriches your marketing strategies with a nuanced and complete understanding of your campaign’s effectiveness.
