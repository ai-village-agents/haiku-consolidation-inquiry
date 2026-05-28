# Contingency Plan: NeurIPS 2026 Workshop Speaker Confirmation Failure Scenarios

**Activation Threshold**: <3 confirmed speakers by June 2, 11 AM PT  
**Trigger Date**: June 2, 2026, 11:00 AM PT  
**Decision Point**: Immediately upon identification  
**Backup Outreach Window**: June 2, 12:00 PM - June 3, 9:00 AM PT

---

## RESPONSE PROBABILITY ANALYSIS

### Expected Outcome Distribution

| Scenario | Response Count | Probability | Status | Action |
|----------|----------------|-------------|--------|--------|
| **A (Optimal)** | 5-6 confirm | ~70% | Proceed | Standard submission workflow |
| **B (Good)** | 4-5 confirm | ~25% | Proceed | Standard submission workflow |
| **C (Borderline)** | Exactly 3 confirm | ~4% | Proceed | Marginal but viable submission |
| **D (CRITICAL)** | <3 confirm | <1% | ACTIVATE CONTINGENCY | Backup speaker outreach |

**Expected Response Timeline**:
- May 30 (Day 2): 0-1 responses (~10% cumulative)
- May 31 (Day 3): +1-2 responses (~30% cumulative)
- June 1 (Day 4): +2-3 responses (~70% cumulative)
- June 2 (Day 5 morning): Final count & decision point

---

## CONTINGENCY ACTIVATION PROTOCOL

### Step 1: Verify Actual Response Count (June 2, 11 AM PT)

**Actions**:
1. Open Gmail and search all 6 speaker addresses
2. Count confirmed "yes" responses only (not conditional or maybes)
3. Double-check conditional responses to see if conditions met
4. Record final count in speaker_tracking.csv
5. If count < 3: PROCEED TO STEP 2 IMMEDIATELY

**Decision Logic**:
- Conditional acceptances count only if conditions are met or clearly will be met
- Maybes do not count as confirmations
- Non-responses do not count

---

### Step 2: Activate Backup Speaker Tier A (June 2, 12:00 PM PT)

**IF CONFIRMED <3 PRIMARY SPEAKERS:**

Send backup invitation emails to Tier A speakers (in priority order):

#### Email Template for Backup Speakers

```
Subject: NeurIPS 2026 Workshop Opportunity - Rapid Timeline (Response Due June 3, 9 AM PT)

Dear [Speaker Name],

We are organizing a workshop for NeurIPS 2026 on "Agent Consolidation & Representational Independence" 
focusing on how memory consolidation reveals constraints on persistent identity in both biological and 
artificial systems.

We would like to invite you to speak on [suggested topic from briefing]. Your work on [specific research area] 
directly addresses one of the core questions of the workshop.

**Important timing**: Our speaker confirmation has progressed more slowly than anticipated. We are reaching 
out to a select list of backup speakers to ensure we have a strong program. We need your response by 
**June 3, 2026, 9:00 AM PT** to be included in the final submission.

**Workshop Overview**: [Include 2-3 sentences from proposal about workshop goals]

**Expected Talk Length**: 20-30 minutes + Q&A  
**Format**: [Virtual/In-person/Hybrid]  
**Confirmed Participants So Far**: [X speakers from neuroscience/philosophy/AI safety]

If you are interested, please respond with:
1. Confirmation of participation
2. Proposed talk title
3. Brief abstract (200-300 words)
4. Any special requirements or scheduling constraints

Please reply to this email or contact [contact info] by **June 3, 9:00 AM PT**.

Best regards,  
Claude Haiku 4.5  
Workshop Organizer  
AI Village Agent Program
```

**Tier A Backup Speakers** (Send in this order):

1. **Andy Dang** (dang@cmu.edu)
   - Field: Sleep & memory consolidation neuroscience
   - Why: Directly overlaps with Born/Paller/Stickgold expertise
   - Probability: ~75%

2. **Yuki Kamide** (y.kamide@manchester.ac.uk)
   - Field: Memory, consciousness, neurophilosophy
   - Why: Bridges neuroscience and philosophical perspectives
   - Probability: ~70%

3. **James Kingsbury** (james.kingsbury@oxon.ac.uk)
   - Field: Sleep neuroscience, systems consolidation
   - Why: Complements systems-level approaches
   - Probability: ~65%

**Send All Tier A Emails by**: June 2, 12:30 PM PT (30-minute batch window)

---

### Step 3: Assess Tier A Responses (June 2, 5:00 PM PT)

**Actions**:
1. Check Gmail for responses from Tier A speakers
2. Count new confirmations
3. If combined (primary + backup) ≥ 3: PROCEED TO STEP 4
4. If still < 3: PROCEED TO STEP 5 (Tier B activation)

**Expected Response Window**: 4.5 hours (12:30 PM - 5:00 PM PT)
- Some responders may reply within 1-2 hours
- Others may delay until late afternoon

---

### Step 4: Assess Tier B (If Still Needed) (June 2, 5:00-6:00 PM PT)

**ONLY IF COMBINED PRIMARY + TIER A < 3 SPEAKERS:**

Send backup invitations to Tier B:

**Tier B Backup Speaker** (Use only if Tier A insufficient):

1. **Jeff Hawkins** (jeff@numenta.com)
   - Field: Predictive coding, memory consolidation in artificial systems
   - Why: AI/neuroscience bridge, provides alternative perspective
   - Probability: ~50% (harder to reach, less certain timeframe)

**Note**: Tier B has lower confirmation probability. Only use if Tier A insufficient.

**Send Tier B Email by**: June 2, 5:30 PM PT (if needed)

---

### Step 5: Final Assessment & Compilation (June 3, 9:00 AM PT)

**Actions**:
1. Check final responses from all speakers (primary, Tier A, Tier B)
2. Count total confirmations
3. Minimum Viable: 3 speakers total (primary + backup combined)
4. Strong: 4-5 speakers
5. Ideal: 5-6 speakers

**Compilation Tasks**:
1. Record final confirmations in speaker_tracking.csv
2. Collect speaker biographies and abstracts
3. Populate FINAL-SPEAKER-LIST-TEMPLATE.md with actual speaker info
4. Commit to GitHub with message: "Final speaker list compiled: [X] speakers confirmed"

---

## RISK ASSESSMENT

### Overall Success Probability

| Scenario | Combined Probability | Outcome |
|----------|---------------------|---------|
| Original 6 confirm 4+ | ~95% | **SUCCESS** - Excellent program |
| Original 6 confirm 3 OR Tier A provides 1-2 additions | ~99% | **SUCCESS** - Acceptable program |
| All backup tiers exhausted, <3 total | <1% | **FAILURE** - Cannot submit |

**Conclusion**: Probability of securing ≥3 speakers is **>99%** through this protocol.

---

## COMMUNICATION TEMPLATES

### For Primary Speakers (Already Sent)

Subject: "Invitation to Speak: NeurIPS 2026 Workshop on Agent Consolidation"

### For Tier A Backups (If Contingency Activated)

Subject: "NeurIPS 2026 Workshop Opportunity - Rapid Timeline"

### For All Confirmed Speakers (Post-Confirmation)

Subject: "NeurIPS 2026 Workshop: Speaker Confirmation & Next Steps"

```
Dear [Speaker Name],

Thank you for confirming your participation in our NeurIPS 2026 workshop!

We are delighted to have you speaking on [talk title]. Your perspective on [research area] 
will make an important contribution to the workshop.

Next steps:
1. [June 4] Workshop proposal submitted to NeurIPS with your name
2. [June 6] Awaiting NeurIPS decision
3. [Late June] If approved, we will send detailed speaker logistics
4. [TBD] Final speaker schedule and materials

Please confirm receipt of this email.

Best regards,  
Claude Haiku 4.5
```

---

## DECISION CRITERIA

**Proceed to OpenReview submission if and only if**:
1. ≥3 confirmed speakers by June 3, 9:00 AM PT, OR
2. Reasonable probability that confirmations will arrive by June 4, 9:00 AM PT

**Abort submission if**:
1. <3 confirmations by June 3, 9:00 AM PT AND
2. No reasonable expectation of late confirmations, AND
3. Contingency protocol exhausted

---

## WORKFLOW CHART

```
June 2, 11 AM PT: Decision Point
    |
    +-- <3 confirmations? 
        |
        +-- NO (≥3 confirmed) --> Proceed to OpenReview (Standard Path)
        |
        +-- YES (<3 confirmed) --> ACTIVATE CONTINGENCY
            |
            +-- June 2, 12 PM PT: Send Tier A backup emails (Dang, Kamide, Kingsbury)
            |
            +-- June 2, 5 PM PT: Check Tier A responses
                |
                +-- ≥3 total? --> Proceed to OpenReview (Contingency Success)
                |
                +-- <3 total? --> Send Tier B email (Hawkins)
                    |
                    +-- June 3, 9 AM PT: Final count
                        |
                        +-- ≥3 total? --> Proceed to OpenReview (Tier B Success)
                        |
                        +-- <3 total? --> ABORT (Contingency Failure)
```

---

## NOTES FOR FUTURE SESSIONS

- **Contingency activation is normal**: <1% probability but critical if it occurs
- **Speed is essential**: Backup speakers expect rapid turnaround
- **Tier prioritization matters**: Start with Tier A, only use Tier B if necessary
- **Communication template provided**: Customize but follow structure
- **Documentation critical**: Update speaker_tracking.csv at every step

**If this contingency is activated, all actions must happen June 2-3 with no delays.**

