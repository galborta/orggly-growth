# How to Keep This Repository Current

This is a LIVING repository. Here's when and how to update each section.

---

## Daily Updates (During Active Campaigns)

### Every Morning
1. **Open NOW.md**
2. Update "Where We Are" if anything changed yesterday
3. Mark completed actions from "Top 3"
4. Add new "Top 3" based on current priorities
5. Update "Current Traction" with latest metrics

### After Campaign Activity
1. **Open tracking/campaigns.md**
2. Log new submissions with all details
3. Update budget remaining
4. Add quality notes for each submission

### After Posting Content
1. **Open content/tweets-*.md**
2. Move posted tweet from "Drafts" to "Archive"
3. Add engagement metrics (wait 24hrs for accurate data)
4. Note what worked/didn't work

---

## Weekly Updates

### Every Monday Morning
1. **Review tracking/wins.md and fails.md**
   - Add entries for anything that worked/didn't work last week
   - Be specific with metrics
   
2. **Update tracking/experiments.md**
   - Check status of active experiments
   - Move completed ones to archive
   - Add results and learnings

3. **Review NOW.md**
   - Archive old priorities to bottom
   - Set fresh "Top 3" for the week
   - Update "This Week's Focus"

4. **Check playbooks/**
   - Do any tactics need updating based on last week's learnings?
   - Add notes to "Update Log" at top if you make changes

---

## Monthly Updates

### First Monday of Month
1. **Review ALL playbooks**
   - What worked consistently? Reinforce in playbooks
   - What failed repeatedly? Update anti-patterns
   
2. **Update strategy docs IF** major pivot happened
   - Generally these stay stable
   - Only update for significant strategic shifts

3. **Add monthly summary to UPDATES.md**

---

## When Specific Events Happen

### When Pivoting Strategy
1. Update NOW.md immediately with new direction
2. Add entry to UPDATES.md explaining why
3. Update relevant playbooks with new tactics
4. Archive old approach in tracking/fails.md

### When Launching New Campaign
1. Add to tracking/campaigns.md
2. Create content drafts in content/
3. Update NOW.md "Top 3" to include launch actions
4. Set tracking/experiments.md if testing something new

### When Getting Significant Traction
1. Document in tracking/wins.md IMMEDIATELY
2. Update NOW.md "What's Working"
3. Consider: Does this change your "Top 3"?
4. Add to UPDATES.md if it's a major milestone

### When Something Breaks/Fails
1. Document in tracking/fails.md IMMEDIATELY
2. Update NOW.md "What's Not Working"
3. Revise "Top 3" to include fix/pivot
4. Update playbooks to prevent repeat

---

## Git Workflow

### After Each Update Session
```bash
cd orggly-growth
git add .
git commit -m "Update [date]: [what changed and why]"
git push origin main
```

### Commit Message Examples
- "Update Jan 13: First 5 campaign submissions logged"
- "Update Jan 14: Pivot to listening tour - cold launch failed"
- "Update Jan 20: Week 1 complete - 15 participants, $8K paid"

---

## Red Flags (Repository Going Stale)

If you notice:
- NOW.md hasn't been updated in >1 week
- "What's Working/Not Working" empty for >2 weeks
- tracking/wins.md and fails.md have no entries
- Content archive has no posted tweets

**Then:** STOP and do immediate update session. Stale repository = blind decision making.

---

## The Golden Rule

**Update repository BEFORE making decisions, not after.**

Planning next week's content? Check NOW.md first.  
About to DM 20 people? Check playbooks/dm-outreach.md first.  
Campaign not working? Log in tracking/fails.md immediately.

This repository is only valuable if it stays current.

---

**Last updated:** January 13, 2026
