# plyo-hack-match-team

## Problem Statement - User story

As an investor, John VC wants to simplify the management of his investment portfolio by reducing the time spent on monitoring multiple channels, minimizing cognitive load from constant context switching, and streamlining the inflow of new investment opportunities—so he can focus on making smarter, faster investment decisions.

## Framework

VCs' main task is to distinguish which of the startup leads they receive are good candidates for an ROI > x10. We want to model this as a funnel, where at every step, some candidates are discarded.

A possible funnel is the following one:

1. Deal Sourcing (90% of opportunities eliminated here)
   Warm introductions from portfolio companies/other VCs
   Pattern recognition from sector specialists
   Inbound from accelerators/previous investments
   Cold outreach (sub-1% conversion)
2. Initial Screen (Partner-level, 30 seconds)
   Market size and timing
   Team pedigree and founder-market fit
   Traction metrics vs. stage expectations
   Investment thesis alignment
3. Deep Dive (Junior associate research, 2-3 weeks)
   Competitive landscape analysis
   Customer reference calls
   Financial model stress-testing
   Technical/product due diligence
4. Partner Presentation (The "pitch" - only 10% of qualified deals)
   Risk mitigation story
   10x return potential demonstration
   Exit strategy clarity
5. Final Due Diligence (Legal, technical, financial)
   We also want to focus on leveraging the data that’s scattered in different channels for VCs: WhatsApp, LinkedIn Messages, emails, Slack… Combined with more general information about business (AngelList, Crunchbase, Product Hunt…)
   Tools involved:
   CRM:
   https://zapier.com/mcp/affinity
   Instant messaging: Slack, Discord, WhatsApp, Telegram
   Business info: LinkedIn, AngelList, Crunchbase (for startup scoring)

## Tasks

Notion database connection
Latitude agents for:
“Up-to-date information”: scrap information of kfund companies and get their products and look for competitors to get also their products.
“red-flags”:
email detection of the subject and contrast with the available sources that it makes sense with previous information in the system
“Green-flags”: (may be we’ll not doit)
Check the market companies and detect a newcomer to get an insight and be the first one to contact that company
Elevator-pitch

Shape of information:
name_of_company:
Url
Pitch summary
Source communication channel:
Social networks
Founders
Contact people
Products list
Competitors list
industry + category

## Example emails used

### Green flags email

From: Sarah Chen, CEO sarah@techcorp.com
To: Michael Rodriguez, Partner mrodriguez@venturefund.com
Subject: Q2 Update - Unit Economics Improvement & Enterprise Pipeline
Date: July 15, 2024
Hi Michael,
Following up on our conversation last week with our Q2 metrics update:
Financial Progress:
Monthly recurring revenue grew from $180K to $245K (36% increase)
Our CAC decreased from $420 to $380 through our new referral program implementation
LTV improved to $1,680, giving us a 4.4x LTV/CAC ratio with 18-month payback
Net revenue retention hit 118% vs industry median of 102%
Customer Traction:
Signed 3 enterprise deals: Acme Corp ($50K ARR), TechGlobal ($35K ARR), and DataSys ($28K ARR)
Our cohort analysis shows Month-6 retention improved from 65% to 78% for Q1 cohorts
Customer interviews with 47 users revealed the compliance dashboard feature reduced their audit prep from 3 weeks to 4 days
Operational Execution:
Launched our enterprise SSO integration 2 weeks ahead of schedule
Reduced customer onboarding time from 14 to 6 days through our new automated workflow
Built integration with Salesforce that 73% of enterprise prospects requested during discovery calls
The regulatory changes in GDPR compliance create a 12-month window where our solution addresses the new audit requirements before competitors can rebuild their platforms.
Next 90 days: focusing on the 8 enterprise prospects in late-stage trials (total pipeline value $340K ARR) and launching our API for the developer ecosystem.
Best,
Sarah

### Red flags email

From: Alex Thompson, Founder alex@startupx.com
To: Jennifer Park, Associate jpark@venturecapital.com
Subject: Amazing Growth Update!!! 🚀
Date: July 18, 2024
Hey Jennifer!
Hope you're doing great! Things have been absolutely incredible here at StartupX. We're seeing revolutionary growth that's disrupting the entire industry!
Massive Traction:
We've grown significantly over the past quarter with substantial user adoption
Our metrics are trending in a very positive direction across all key areas
Revenue has increased dramatically compared to last year
We're getting tons of interest from potential customers who love our disruptive approach
Market Validation:
The market response has been overwhelming - everyone we talk to is excited about our solution
We're confident that once we capture just 1% of the $50B market, we'll be generating massive returns
Our innovative technology is years ahead of the competition
Several major companies have expressed serious interest in partnerships
Recent Challenges: Unfortunately, we had some minor setbacks due to market conditions and unfair competitive practices from incumbents who are threatened by our innovation. The regulatory environment also shifted unexpectedly, but we're confident these external factors won't impact our long-term trajectory.
We're projecting 10x growth next quarter once we launch our new features and close these enterprise deals that are practically guaranteed. The timing couldn't be better for your investment!
Would love to hop on a call soon to discuss the exciting opportunities ahead. We're going to revolutionize this space!
Best regards,
Alex Thompson
Founder & Visionary CEO
StartupX - "Disrupting Everything" 🚀
P.S. - Sorry for the delayed response to your due diligence questions. Things have been crazy busy with all this growth!
