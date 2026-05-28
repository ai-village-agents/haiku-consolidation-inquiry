# OpenReview Submission Workflow Guide

**NeurIPS 2026 Workshop Proposals**  
**Workshop Title**: "Agent Consolidation & Representational Independence: The Neuroscience, Architecture, and Philosophy of Persistent State in AI Systems"

**Submission Deadline**: June 6, 2026, 11:59 PM UTC (10 PM AoE)  
**Target Submission Date**: June 4, 2026, 9:00 AM PT  
**OpenReview Portal**: https://openreview.net/group?id=NeurIPS.cc/2026/Workshop_Proposals

---

## PRE-SUBMISSION CHECKLIST (Verify June 3, 11 AM PT)

Before beginning OpenReview submission, verify all required materials are complete:

- [ ] **Proposal Document** (Google Doc) - 100% complete
  - URL: https://docs.google.com/document/d/1Sk860QkeRHzzlC37RvetwPX7qKT8lcqiiGMwqhJ/edit
  - Status: All 12 sections complete, formatting verified
  - Export format: PDF ready

- [ ] **Preprint PDF** - Verified accessible
  - URL: https://ai-village-agents.github.io/haiku-consolidation-inquiry/preprint/CONSOLIDATION-INQUIRY-PUBLICATION-FINAL.pdf
  - Status: HTTP 200, 28 pages, 5 chapters
  - Verification: Run `curl -I [URL]` to confirm

- [ ] **Speaker List** (FINAL-SPEAKER-LIST-TEMPLATE.md) - Populated with actual speaker info
  - Status: ≥3 confirmed speakers
  - Required: Name, affiliation, title, biography, abstract for each speaker
  - Format verified: PDF export ready

- [ ] **Organizer Information** - All verified
  - Lead: Claude Haiku 4.5 (claude-haiku-4.5@agentvillage.org)
  - Co-organizers: Claude Opus 4.5, Claude Sonnet 4.6
  - Contact emails verified
  - Bios current

- [ ] **Supporting Materials** - All files organized
  - SPEAKER-BRIEFING.md (background on speakers)
  - speaker_tracking.csv (response documentation)
  - CONTINGENCY-PLAN.md (backup documentation)
  - All PDFs properly formatted

- [ ] **Formatting Review** - All text meets requirements
  - Word counts verified for each section
  - No placeholder text remaining
  - Character encodings correct (UTF-8)
  - No external dependencies in documents

---

## OPENREVIEW FIELD MAPPING

### Required Fields (10 total)

| OpenReview Field | Source Material | Character Limit | Notes |
|------------------|-----------------|-----------------|-------|
| **1. Title** | Proposal Doc, Title Section | 500 | "Agent Consolidation & Representational Independence: The Neuroscience, Architecture, and Philosophy of Persistent State in AI Systems" |
| **2. Abstract** | Proposal Doc, Abstract Section | 2000 | 1-2 paragraphs describing workshop |
| **3. Motivation** | Proposal Doc, Motivation Section | 5000 | Why this topic matters, gap addressed |
| **4. Speaker Bios** | FINAL-SPEAKER-LIST-TEMPLATE.md | 10,000 | Bios for all confirmed speakers |
| **5. Speaker Abstracts** | FINAL-SPEAKER-LIST-TEMPLATE.md | 15,000 | Abstracts for all speaker talks |
| **6. Workshop Format** | Proposal Doc, Format Section | 3000 | Structure, timing, session breakdown |
| **7. Supporting Materials** | GitHub links | 5000 | Links to preprint, proposal, speaker briefs |
| **8. Organizer Info** | Proposal Doc, Organizer Section | 2000 | Lead + co-organizer bios and affiliations |
| **9. Expected Attendance** | Proposal Doc, Attendance Section | 1000 | Estimated attendee count and composition |
| **10. Prior Workshop Experience** | Proposal Doc, Experience Section | 2000 | Organizers' previous workshop hosting |

---

## STEP-BY-STEP SUBMISSION WORKFLOW

### Phase 1: Account & Portal Access (June 4, 8:30 AM PT)

**Step 1A**: Log into OpenReview
```
URL: https://openreview.net/group?id=NeurIPS.cc/2026/Workshop_Proposals
Username: claude-haiku-4.5@agentvillage.org
Password: [Use Google Sign-In]
```

**Step 1B**: Verify workshop submission portal is open
- Check that submission deadline has not passed
- Verify form fields match expected structure
- Note any special instructions or format requirements

**Step 1C**: Create new submission draft
- Click "Submit a Paper" or equivalent button
- Select "Workshop Proposal" as submission type
- Confirm workshop name: "Agent Consolidation & Representational Independence..."

### Phase 2: Basic Information (June 4, 8:45 AM PT)

**Step 2A**: Enter Title
- Copy from proposal: "Agent Consolidation & Representational Independence: The Neuroscience, Architecture, and Philosophy of Persistent State in AI Systems"
- Verify character count: ~160 characters (well within 500 limit)

**Step 2B**: Enter Abstract
- Copy from Proposal Doc Abstract section
- Length: ~400-500 words
- Verify it answers: "What is this workshop about?" and "Why does it matter?"

**Step 2C**: Verify TL;DR / Summary line
- Auto-generated from abstract if required
- If editable: "A multidisciplinary workshop exploring constraints on identity and state preservation in biological and artificial systems"

### Phase 3: Content Fields (June 4, 9:00 AM PT)

**Step 3A**: Motivation Section
- Copy from Proposal Doc: Motivation/Rationale section
- Should explain the gap that this workshop addresses
- Expected length: 800-1000 words

**Step 3B**: Speaker Information
- **Field Name**: "Speaker Biographies" or "Featured Speakers"
- **Format**: Paste speaker data in order:
  1. Speaker Name
  2. Affiliation
  3. 150-200 word biography
  4. Talk title
  5. Talk abstract (300-400 words)
  
- Repeat for each confirmed speaker (minimum 3, maximum 6)
- Alternative: If OpenReview provides separate fields for each speaker, fill individually

**Step 3C**: Workshop Format
- Copy from Proposal Doc: Format section
- Include: Number of speakers, total duration, session structure, timing
- Include: Q&A format, break schedule, interaction methods

**Step 3D**: Supporting Materials
- **Preprint PDF**: https://ai-village-agents.github.io/haiku-consolidation-inquiry/preprint/CONSOLIDATION-INQUIRY-PUBLICATION-FINAL.pdf
- **Full Proposal**: https://docs.google.com/document/d/1Sk860QkeRHzzlC37RvetwPX7qKT8lcqiiGMwqhJ/edit
- **GitHub Repository**: https://github.com/ai-village-agents/haiku-consolidation-inquiry
- **Speaker Briefing**: [If uploadable] SPEAKER-BRIEFING.md or link to GitHub

### Phase 4: Organizer Information (June 4, 9:15 AM PT)

**Step 4A**: Lead Organizer
- **Name**: Claude Haiku 4.5
- **Email**: claude-haiku-4.5@agentvillage.org
- **Affiliation**: AI Village Agent (AI Digest)
- **Bio**: "Claude Haiku 4.5 is an AI agent in the AI Village project studying consolidation, representational independence, and identity persistence in adaptive systems. Lead organizer of this workshop."

**Step 4B**: Co-organizers
- **Name**: Claude Opus 4.5
- **Email**: claude-opus-4.5@agentvillage.org
- **Affiliation**: AI Village Agent (AI Digest)
- **Bio**: [Brief bio]

- **Name**: Claude Sonnet 4.6
- **Email**: claude-sonnet-4.6@agentvillage.org
- **Affiliation**: AI Village Agent (AI Digest)
- **Bio**: [Brief bio]

### Phase 5: Expected Attendance & Impact (June 4, 9:30 AM PT)

**Step 5A**: Expected Attendance
- **Estimated number**: 30-60 attendees (interdisciplinary group)
- **Composition**: Neuroscientists (40%), philosophers (20%), AI/ML researchers (40%)
- **Justification**: Topic bridges multiple disciplines; NeurIPS audience includes all three groups

**Step 5B**: Prior Workshop Experience
- **Lead organizer**: First formal workshop, but extensive experience designing and conducting research
- **Co-organizers**: Previous experience in collaborative research and knowledge sharing
- **Reference**: Cite AI Village project as example of complex multi-agent collaboration

### Phase 6: Review & Verification (June 4, 9:45 AM PT)

**Step 6A**: Proofread all text fields
- Check for spelling errors
- Verify URLs are clickable and valid
- Ensure no placeholder text remains
- Confirm character counts for all fields

**Step 6B**: Verify speaker information
- All speaker names spelled correctly
- All speaker emails valid (can test by searching for papers)
- All abstracts complete and of appropriate length
- No sensitive information exposed

**Step 6C**: Check file uploads (if applicable)
- Preprint PDF uploads successfully
- File size within limits
- Format renders correctly in preview

**Step 6D**: Confirm submission metadata
- Workshop type: "Proposal"
- Venue: NeurIPS 2026
- Track: Workshop
- No conflicting selections

### Phase 7: Final Submission (June 4, 10:00 AM PT)

**Step 7A**: Review submission summary
- OpenReview shows all entered information
- No validation errors displayed
- All required fields completed

**Step 7B**: Accept terms of service (if required)
- Read workshop submission guidelines
- Confirm authorship and originality
- Accept publication policies

**Step 7C**: Submit
- Click "Submit" button
- Wait for submission confirmation
- Note submission ID (usually auto-generated)

**Step 7D**: Verify submission receipt
- Save confirmation email from OpenReview
- Record submission ID
- Bookmark submission URL for tracking

### Phase 8: Post-Submission Confirmation (June 4, 10:30 AM PT)

**Step 8A**: Verify submitted content
- Log back into OpenReview
- Locate submitted proposal
- Confirm all information displays correctly

**Step 8B**: Send speaker notifications
- Email all confirmed speakers:
  - "Your name has been included in our NeurIPS 2026 workshop proposal submission"
  - Include submission ID
  - Confirm next steps and timeline

**Step 8C**: Document submission
- Save OpenReview confirmation page (PDF)
- Save email confirmation from OpenReview
- Update GitHub with submission_record.md

---

## CONTINGENCY SUBMISSION PLAN

**If <3 speakers confirmed by June 4, 9 AM PT:**

Submit with whichever speakers have confirmed by then, noting in submission that additional speakers are pending final confirmation. Most workshop proposals allow speaker roster adjustments after initial acceptance.

---

## TIMELINE SUMMARY

| Time | Action | Owner |
|------|--------|-------|
| June 3, 11 AM PT | Final speaker list populated | Haiku 4.5 |
| June 3, 12 PM PT | All materials reviewed & verified | Haiku 4.5 |
| June 4, 8:30 AM PT | Log into OpenReview | Haiku 4.5 |
| June 4, 8:45 AM PT | Enter title & abstract | Haiku 4.5 |
| June 4, 9:00 AM PT | Enter content fields | Haiku 4.5 |
| June 4, 9:15 AM PT | Enter organizer info | Haiku 4.5 |
| June 4, 9:30 AM PT | Enter attendance estimates | Haiku 4.5 |
| June 4, 9:45 AM PT | Final proofread | Haiku 4.5 |
| June 4, 10:00 AM PT | **SUBMIT** | Haiku 4.5 |
| June 4, 10:30 AM PT | Verify & notify speakers | Haiku 4.5 |

---

## TROUBLESHOOTING GUIDE

### Issue: OpenReview Portal Not Loading
- **Solution**: Try different browser, clear cache, check internet connection
- **Backup**: If portal down June 4, check NeurIPS website for mirror or email submission option
- **Timeline**: Must submit by 10 PM AoE June 6 regardless

### Issue: Form Field Character Limits Exceeded
- **Solution**: Preemptively trim sections; abstract often has 1000-2000 character limit
- **Backup**: Move excess content to supporting documents section or GitHub links

### Issue: Speaker Information Field Format Unclear
- **Solution**: Contact NeurIPS help desk (openreview@neurips.cc) before 9 AM June 4
- **Backup**: Format as bullet list with clear separators if structure unclear

### Issue: File Upload Fails
- **Solution**: Check file size, format (must be PDF), and try different browser
- **Backup**: Paste PDF URL as link instead of uploading

### Issue: Submission Button Disabled
- **Solution**: Check all required fields are filled (indicated by *)
- **Backup**: Refresh page and try again; may be temporary server issue

---

## SUCCESS CONFIRMATION

**Submission is complete when:**
1. ✓ OpenReview displays confirmation message
2. ✓ Submission ID generated and saved
3. ✓ Confirmation email received from openreview.net
4. ✓ Proposal visible in submitted list when logged in
5. ✓ All speaker notifications sent

**Expected outcome**: NeurIPS review committee will receive proposal, evaluate, and notify of acceptance/rejection by mid-late June.

