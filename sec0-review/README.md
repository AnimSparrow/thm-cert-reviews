<p align="center">
  <img src="assets/banner.svg" width="820" alt="SEC0 - Pre Security Review">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TRYHACKME-1a0633?style=for-the-badge&labelColor=FF2A6D">
  <img src="https://img.shields.io/badge/PRE--SECURITY-1a0633?style=for-the-badge&labelColor=00F0FF">
  <img src="https://img.shields.io/badge/CERT_%231-1a0633?style=for-the-badge&labelColor=A479C4">
</p>

---

## Overview

> [!NOTE]
> **TL;DR** - SEC0 is TryHackMe's entry point cert: foundational IT and computer literacy before security concepts even start. Passed with **580/600** (pass mark 390/600), 24h window, exam time **1h 08m 47s**. Overall score: **4.33/10** (weighted, see below). Verdict below: worth it for a first cert, skip if you already work in the field.

## Fast Facts

| | |
|---|---|
| Full name | TryHackMe Pre Security Certification (SEC0) |
| Position in pathway | Entry point, base of the TryHackMe cert ladder, feeds into SEC1 |
| Format | Hands-on, scenario-based (not multiple choice) |
| Retake | 1 free retake included |
| Validity | 3 years |
| Date passed | 06.03.2026 |
| Score | 580 / 600 (pass threshold: 390 / 600) |
| Exam time | 1h 08m 47s of a 24h window |

## Terrain

Six domains on paper: Computer Fundamentals, Operating Systems, Software Basics, Network Fundamentals, How the Web Works, Cyber Security: Attacks & Defenses.

In practice it reads as help desk territory: locating a host, checking who is logged in, reading an IP, understanding basic network layout. The kind of knowledge a lot of people already carry just from years of actually using a computer for more than browsing. Nothing here goes deep on any single domain. It is a wide but shallow pass across everything you would need before a "real" security concept makes sense at all, similar to confirming someone knows how to hold a scalpel before they touch a patient.

That is not a criticism, it is a scope decision, and TryHackMe is upfront about it: SEC0 explicitly does not claim job readiness. It is closer to a pre-helpdesk credential than a cyber one. The interesting design choice is that it is still scenario based rather than pure recall. You are placed in small simulated situations and asked to act, not asked to define a term. That format alone puts it a notch above most "fundamentals" multiple choice tests on the market, even if the content ceiling is low.

Who this actually lands differently for: someone who has spent 10+ years around a keyboard will find this almost entirely muscle memory. Someone coming in cold, with no prior IT exposure at all, will genuinely learn something in every domain. The cert does not distinguish between those two audiences. The experience does.

## Mission Debrief

- **Time invested:** years of general IT/PC use going in, plus roughly a week working through the Pre Security learning path (legacy version) beforehand.
- **Approach:** worked through the topics in order, no reordering, no pausing to research anything outside the platform.
- **Pacing:** a 24 hour exam window, closed out in 1h 08m 47s. That gap is the whole story of this cert. It is built to be taken in one sitting, over a coffee, not to demand a weekend the way WEB1 did.
- **Turning point:** none of the dramatic kind, and that is the point, not a gap in the writeup. This is a fast, low friction loop: short tasks, quick wins, one after another. Nothing here demands a second read of the scenario, and inventing a "big reveal" moment for the sake of the narrative would misrepresent what the cert actually is.

## Friction Points

> [!WARNING]
> Twice during the exam, the expected answer format was not clear. Genuinely unsure whether the answer wanted `HOSTNAME` or `HOSTNAME.DOMAIN` (or another variant), with no format hint in the question text. Both times cost a few minutes of guessing rather than solving. Reported it to TryHackMe. By the time SEC1 was attempted, the format expectations were spelled out much more clearly in the question wording, a good sign the feedback loop between candidates and the exam team actually works, rather than issues sitting unaddressed across cert generations.

## Debrief Accounting

- **Grading fairness:** fair, once the answer-format issue above is accounted for. It cost time, not understanding, so it should not meaningfully affect the score, and it did not here.
- **Learning path alignment:** the Pre Security path (legacy + current) matched the exam content and then some, over-prepared rather than under-prepared. If anything, the path goes slightly deeper than the exam ever asks for.
- **Outside knowledge required:** none. Everything needed was covered in the path. No prior IT background is strictly required to pass, though it clearly helps with speed.

## S.P.A.R.R.O.W. Score

My own 7-dimension scale, used consistently across this whole review series so all 7 certs stay comparable at the end. Each dimension is scored 1-10.

| Letter | Dimension | What it measures | Weight | Score | Reasoning |
|:---:|---|---|:---:|:---:|---|
| **P** | Practicality | Do the scenarios reflect real work, or are they gamified filler | High | 5/10 | Builds the instinct of knowing where data comes from, but most of it is automated by SIEM/SOAR/XDR today |
| **O** | Outcome | How much this actually signals to an employer | High | 1/10 | Unrecognized on the job market, reads as first-computer-use or help desk training, not a cyber signal |
| **W** | Worth | Price paid vs. everything above, combined | High | 2/10 | Cheap and often discounted or bundled, but the value is not the content, it is the checkpoint moment |
| **S** | Scope | Does actual coverage match what is advertised up front | Medium | 10/10 | 1:1 match between what is promised and what is tested |
| **R** | Rigor | Is grading consistent and fair relative to what was demonstrated | Medium | 8/10 | Docked for the answer-format confusion, otherwise consistent |
| **A** | Access | Is the prep material good enough to actually get you there | Low | 10/10 | Legacy and current Pre Security paths are a solid theory+practice mix, most of it free |
| **R** | Reliability | Does the platform/exam environment hold up technically | Low | 10/10 | Zero platform issues, environment loaded once and stayed stable |

**Weighting logic:** Practicality, Outcome and Worth matter most to someone deciding whether a cert is worth their time and money, so they carry the most weight. Scope and Rigor come next: once you commit to an exam, you want it to test what it claims and grade you fairly. Access and Reliability carry the least weight, useful context, but the least decisive factor in whether the cert itself is worth it.

**Weighted overall score: 4.33 / 10**

| Weight tier | Multiplier | Dimensions | Scores | Weighted subtotal |
|---|:---:|---|---|:---:|
| High | x6 | Practicality, Outcome, Worth | 5, 1, 2 | 48 |
| Medium | x2 | Scope, Rigor | 10, 8 | 36 |
| Low | x1 | Access, Reliability | 10, 10 | 20 |

Total weighted sum 104, over total weight 24, gives **4.33/10**.

> [!TIP]
> **Reading the score:** high Scope/Access/Reliability with low Outcome/Worth is the expected shape for an entry cert like this. It means TryHackMe built exactly what they said they would build, it is just early on the ladder. Don't read the low numbers as "bad cert," read them as "correctly positioned as step one," which is also why the weighting favors Practicality, Outcome and Worth: those are the numbers that actually change your decision.

## Verdict

If you are starting from zero certs, first job after school, or switching in from a completely unrelated field, get it. It is cheap, low effort, and gives you a real "watch me start growing in this direction" marker. If you already work in cyber, skip it unless you are collecting badges for the sake of it.

## Lessons Learned

- Answer-format ambiguity in early TryHackMe exams is worth flagging. They iterate on it, SEC1 confirmed this.
- This cert is a floor, not a differentiator. Treat it as a checkpoint, not a learning goal.

## Certificate

<p align="center">
  <img src="https://assets.tryhackme.com/certification-certificate/69ab329ed862bcf935bb60c7.png" width="700" alt="SEC0 certificate">
</p>

<p align="center">
  <a href="https://tryhackme.com/certification/certificate/1d7fc352-19a9-495e-ba9b-9febd29c4087">
    <img src="https://img.shields.io/badge/VIEW_CREDENTIAL-1a0633?style=for-the-badge&labelColor=00F0FF">
  </a>
</p>

---

<p align="center">
  <a href="#"><!-- replace with link to your review index -->
    <img src="assets/more_reviews.svg" width="360" alt="More TryHackMe cert reviews">
  </a>
</p>
