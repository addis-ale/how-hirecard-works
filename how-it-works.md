# Card Data Sources: Current vs Required

This table shows what data sources are currently being used for each card and what additional data sources are needed but not currently available.

## Data Sources Legend

**Currently Available:**
- **LinkedIn** - Job postings and candidate profiles
- **Glassdoor** - Job postings and salary data
- **Indeed** - Job postings

---

## Table: Card Data Sources - Current vs Required

| Card # | Card Name | Currently Using (LinkedIn/Glassdoor/Indeed) | Additional Data Sources Needed (Not Currently Using) |
|--------|-----------|---------------------------------------------|-------------------------------------------------------|
| 1 | **Reality Card** | ✅ LinkedIn (similar jobs)<br>✅ Glassdoor (similar jobs)<br>✅ Indeed (similar jobs)<br>✅ LinkedIn (candidates)<br>✅ Glassdoor (salaries) | • Quality of Hire data<br>• Time-to-fill historical data<br>• Offer acceptance rates<br>• Real conversion rate data |
| 2 | **Role Card** | ✅ LinkedIn (similar jobs)<br>✅ Glassdoor (similar jobs)<br>✅ Indeed (similar jobs) | • Internal company data (team size, reporting structure)<br>• Company culture data<br>• Success metrics from similar roles<br>• Real-time job posting trends |
| 3 | **Market Card** | ✅ LinkedIn (similar jobs)<br>✅ Indeed (similar jobs)<br>✅ Glassdoor (similar jobs)<br>✅ LinkedIn (candidates) | • Real-time job posting trends<br>• Candidate activity data (who's looking)<br>• Geographic talent migration patterns<br>• Job posting velocity data |
| 4 | **Skill Card** | ✅ LinkedIn (similar jobs)<br>✅ Glassdoor (similar jobs)<br>✅ Indeed (similar jobs) | • Skill demand trends<br>• Emerging skills data<br>• Skill combination patterns<br>• Industry skill evolution data |
| 5 | **Pay Card** | ✅ Glassdoor (salaries)<br>✅ LinkedIn (similar jobs with salary info)<br>✅ Indeed (similar jobs with salary info) | • Real offer data<br>• Total compensation breakdowns (equity, benefits)<br>• Location-adjusted salaries<br>• Salary APIs (Payscale, Salary.com, Levels.fyi)<br>• Industry-specific compensation data |
| 6 | **Funnel Card** | ❌ None (uses industry benchmarks only) | • Real conversion rate data by industry/role<br>• Time-to-hire by stage<br>• Response rate data<br>• Industry-specific benchmarks<br>• Outreach effectiveness data<br>• **CRITICAL:** Currently returns null - needs real benchmark data |
| 7 | **Fit Card** | ⚠️ Optional: LinkedIn (candidates) | • Real candidate preference data<br>• Company culture match data<br>• Work style preferences<br>• Salary vs. culture trade-offs<br>• Candidate survey data<br>• Psychometric assessment data |
| 8 | **Message Card** | ❌ None (uses AI research only) | • A/B test results on messaging<br>• Response rate data by message type<br>• Industry-specific messaging patterns<br>• Competitor messaging analysis<br>• Email open/response rates |
| 9 | **Outreach Card** | ❌ None (uses AI research only) | • Email open/response rates<br>• Best time to send data<br>• Channel effectiveness (email vs. LinkedIn)<br>• Personalization impact data<br>• Outreach campaign performance data |
| 10 | **Talent Map Card** | ✅ LinkedIn (candidate profiles) | • Company layoff data<br>• Company growth data<br>• Funding rounds data<br>• Employee movement patterns<br>• Industry trends<br>• Company hiring velocity data |
| 11 | **Interview Card** | ❌ None (uses AI research only) | • Interview pass rates by question type<br>• Time-to-hire by interview stage<br>• Candidate feedback data<br>• Industry interview best practices<br>• Interview effectiveness metrics |
| 12 | **Scorecard Card** | ❌ None (uses AI research only) | • Evaluation bias data<br>• Scorecard effectiveness metrics<br>• Inter-rater reliability data<br>• Hiring success correlation data |
| 13 | **Plan Card** | ❌ None (uses AI research only) | • Historical hiring success data<br>• SLA compliance rates<br>• Timeline accuracy data<br>• Resource allocation data<br>• Industry-specific timeline benchmarks |

---

## Summary Statistics

### Cards with Comprehensive Data Sources (5 cards)
- Reality Card
- Role Card  
- Market Card
- Skill Card
- Pay Card
- Talent Map Card

### Cards with Limited/No External Data Sources (8 cards)
- Funnel Card ⚠️ **CRITICAL GAP** (returns null)
- Fit Card
- Message Card
- Outreach Card
- Interview Card
- Scorecard Card
- Plan Card

### Current Data Source Usage
- **LinkedIn**: Used by 6 cards (Reality, Role, Market, Skill, Pay, Talent Map)
- **Glassdoor**: Used by 5 cards (Reality, Role, Market, Skill, Pay)
- **Indeed**: Used by 4 cards (Reality, Role, Market, Skill)

---

## Priority Recommendations

### 🔴 High Priority (Immediate Impact)
1. **Funnel Card** - Fix industry benchmarks (currently returns null)
2. **Pay Card** - Add real salary/compensation APIs (Payscale, Salary.com, Levels.fyi)
3. **Outreach Card** - Track email response rates and campaign performance
4. **Market Card** - Add real-time job posting trends
5. **Fit Card** - Add candidate preference data

### 🟡 Medium Priority (Significant Improvement)
1. **Reality Card** - Add quality of hire and time-to-fill data
2. **Message Card** - Add A/B test results and response rate data
3. **Talent Map Card** - Add company growth/layoff data
4. **Interview Card** - Add interview pass rate data
5. **Plan Card** - Add historical hiring timeline data

### 🟢 Low Priority (Nice to Have)
1. **Role Card** - Add internal company data
2. **Scorecard Card** - Add evaluation bias data

---

_Last Updated: Based on current implementation and documentation review_

