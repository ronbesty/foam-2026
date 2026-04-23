---
type: source
tags:
  - source
  - project/at-risk-user-study/literature-review
authors:
  - "Daniela Napoli"
year: 2018
doi: ""
url: "https://repository.library.carleton.ca/},
    note        = {School of Computer Science"
citekey: "0904261411"
date-added: 2026-04-10
---

# 2018-napoli-vi-security-privacy-strategies-0904261411

## BibTeX Entry

Copy this block directly into `.bib` file for LaTeX.
```bibtex
@mastersthesis{Napoli2018accessible,
    author      = {Napoli, Daniela},
    title       = {{Accessible and Usable Security: Exploring Visually Impaired Users' Online Security and Privacy Strategies}},
    school      = {Carleton University},
    year        = {2018},
    type        = {Master of Arts},
    address     = {Ottawa, Ontario},
    month       = {May},
    url         = {https://repository.library.carleton.ca/},
    note        = {School of Computer Science}
}

```

## Summary

-  Napoli (2018) in his masters thesis discussed that there is a significant lack of documented literature exploring the intersection of web accessibility and usable security. While security mechanisms (solutions) exist, they are primarily vision-based. Aditionally, the unique security and privacy needs, barriers, and mental models of visually impaired users are largely undocumented. Also, the existing security mechanisms (solutions) are unsupported by current standards like the WCAG. 

- Mix method approach was adopted:
  1. Expert Evaluation: An assessment of 10 popular websites using automated checkers and an expert cognitive walkthrough/heuristic evaluation using the JAWS (18) screen reader, guided by nine newly proposed "ACCUS" heuristics. This was researcher led. 
  2. User Study: A task-based study with 14 visually impaired participants (blind and partially sighted) to observe their security habits, concerns, and ability to manage web-based threats like phishing on real and spoofed websites. 

- The thesis proposes a set of Accessible and Usable Security (ACCUS) heuristics rooted in HCI best practices (based on literature review). The thesis also  provides empirical evidence showing that current security indicators (like lock icons and SSL dialogues) are often unreadable or inaccessible via assistive technology, indicating that Standard web security cues are not accessible for VI users. Additionally, it also documented the Failure of Standards (WCAG) with security solutions, The tradeoff Between Security solutions and Accessibility (disabling the auto popup).  

## Gap (Why?) 

1. Prior research on security and privacy for VI users was sparse and typically conducted with small samples using limited methodologies. 
2. Existing security solutions for web-based threats are predominantly visual, making them inaccessible to VI users. 
3. The existing standards for accessibility, like the WCAG, or W3C, provide a checklist for accessibility, but we do not know how well they are implemented in the security solutions. 
4. The thesis aimed to comprehensively investigate VI users' online security and privacy concerns, the accessibility of web security cues, and their perception of web-based security threats. 

## Contributions (What?)

- The thesis laid the groundwork that was later published as the SOUPS 2021 paper (Napoli et al., 2021). Findings discussed that VI users face many barriers: assistive technology (screen readers) that misinterpret or obscure security indicators, inaccessible antivirus software, password masking issues with screen readers, and reliance on sighted helpers, which compromise autonomy and security. The thesis contributed to the development of the "accessible and usable security heuristics" (ACCUS) framework. Additionally, it also documented the Failure of Standards: Compliance with WCAG 2.0 Level AA is insufficient for security. Automated checkers found few errors, while the expert evaluation uncovered "catastrophic" usability issues that prevented users from completing tasks securely. The Choice Between Security and Accessibility: Visually impaired users are often forced to choose between security and the ability to use their technology. For example, participants reported disabling automatic updates because updates often "ruin the accessibility" of their system. The "Invisible" Security State: Standard web security cues are inaccessible to VI users. For example, lock icons and SSL dialogues in browsers like Internet Explorer were found to be unreadable by JAWS, meaning the "Information needed for Secure Behavior" was technically inaccessible. Phishing vulnerability: 0 out of 6 participants correctly identified a spoofed "CCNIB" website. Participants relied on "unreliable" indicators such as brand reputation and page content rather than technical security cues because these cues were not communicated audibly in a useful way.       

### Concepts Extracted

- 

### Relevant Quotes or Data

- ACCUS (Accessible and Usable Security) 
  - Basis: The framework was built by extracting and "open-coding" 172 best practices, recommendations, and documented behaviors from 25 peer-reviewed articles published between 1999 and 2017.
  - Integration: It specifically includes W3C WCAG 2.0 (accessibility standards), Nielsen’s usability heuristics, and established usable security principles (such as those by Whitten and Tygar).
    - Thematic Foundation: The author mapped Nielsen’s 10 usability heuristics directly onto the four W3C WCAG 2.0 principles (Perceivable, Operable, Understandable, and Robust).
    - Literature Synthesis: The researcher surveyed 25 peer-reviewed articles published between 1999 and 2017.
    - Data Extraction: From these articles, 172 best practices, expert recommendations, and documented user behaviors (from both sighted and non-sighted users) were extracted.  
    - Open-Coding Process: The author used an open-coding process to categorize these excerpts into common themes, successfully sorting 154 pieces of data into the final categories.
  - The Framework: It consists of 9 specific heuristics: Informative, Verifiable, Recognizable, Assistive, Functional, Controllable, Responsive, Diverse, and Memorable.
    1. Informative: Messages must be clear, brief, and parsable for audible delivery.
    2. Verifiable: The state of security and available options must be explicit and described in plain language.
    3. Recognizable: Security information and functions must be easy to distinguish and organize to match the user's mental model.
    4. Assistive: The system should guide users through decisions, prevent errors, and allow users to diagnose and fix mistakes.
    5. Functional: Security cues and functions (like authentication) must work quickly and as expected.
    6. Controllable: Security mechanisms must be compatible with assistive technology and offer customizable protection.
    7. Responsive: Feedback regarding actions or threats must be effective and provided without interrupting the user's workflow.
    8. Diverse: Content and context must accommodate users with varying degrees of sight loss, providing both visual and aural alternatives.
    9. Memorable: Functions should require low cognitive load to ensure the system is easy to learn and recall.

### My thoughts

- Evidence for the accessibility standards W3C and WCAG, and how they are implemented in security solutions. The heuristic framework developed is a good hook to base an analysis on, if we decide to take the route of policy implementation. "Do different, not do more".    

## Methodology (How?)

1. Expert evaluation: 
   - In this phase, the lead researcher performed the walkthroughs themselves.
   - The researcher acted as the "expert" evaluator to assess the websites.
   - The researcher navigated the sites using JAWS 18 screen reading software and relied solely on keyboard shortcuts, mimicking the experience of a visually impaired (VI) user.
   - The goal was to provide an estimate of obstacles and assess whether sites meeting WCAG guidelines actually supported usable security from a technical standpoint.
   - The researcher evaluated the websites against the ACCUS heuristics they had developed

2. User Study (VI User-Led)
   - The VI users did not perform the expert walkthroughs; instead, they participated in a separate task-based user study.
     1. Verifying if a website was real or fake.
     2. Logging into a site.
     3. Completing a sensitive transaction, such as buying stamps or making a donation.
   - 14 visually impaired participants (7 blind, 7 partially sighted) were observed by the researcher while completing security-related tasks.
   - Participants were encouraged to "think-aloud" to explain their rationale and mental models while the researcher took notes and recorded the sessions.
   - The researcher used this empirical data to validate or supplement the issues identified during the initial expert evaluation.

---

**Backlinks:** (Foam auto-populates this section)