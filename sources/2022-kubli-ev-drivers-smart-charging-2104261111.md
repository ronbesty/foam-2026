---
type: source
tags:
  - source
authors:
  - "Merla Kubli"
year: 2022
doi: "10.2139/ssrn.4052231"
url: "https://ssrn.com/abstract=4052231"
citekey: "Kubli2022EvDW"
date-added: 2026-04-21
---

# 2022-kubli-ev-drivers-smart-charging-2104261111

## BibTeX Entry

Copy this block directly into `.bib` file for LaTeX.
```bibtex
@article{Kubli2022EvDW,
    author    = {Kubli, Merla},
    title     = {{Ev Drivers' Willingness to Accept Smart Charging: Measuring Preferences of Potential Adopters}},
    journal   = {SSRN Electronic Journal},
    year      = {2022},
    month     = {August},
    doi       = {10.2139/ssrn.4052231},
    url       = {https://ssrn.com/abstract=4052231}
}
```

## Summary

- Choice experiment to measure EV drivers (current and potential’) willingness to smart chargeing.
- The headline finding is that EV drivers are willing to participate in smart charging, but they require compensation. 
- A willingness-to-accept (WTA) analysis then translates the part-worth utilities into concrete Swiss franc compensation figures that operators would need to offer in order to shift drivers from a standard home-charging baseline to alternatives such as workplace charging or ECO charging.


## Gap (Why?) 

- Consumer preferences for smart charging are under-studied. Kubli explicitly builds on calls by Gschwendtner et al. (2021) and Sovacool et al. (2017, 2018), writing that "existing knowledge about EV drivers' preferences for participating in smart charging solutions is limited" and that "a more in-depth understanding of the conditions under which EV drivers are willing to participate in smart charging solutions is needed.
- Prior work is skewed toward V2G contracts. Kubli observes that "there has been a strong focus on the contract-based implementation of V2G" while "other forms of smart charging have enjoyed less attention so far from consumer research, even though unidirectional charging approaches and solar charging face fewer technological and regulatory constraints for implementation today."
- Most prior samples are not early adopters. She notes that several studies "responded to low EV penetration rates with samples that address the broad public," which limits practical relevance because "respondents without EV experience and little or no knowledge about smart charging who asked for their preferences to choose a V2G contract, have low predictive power for early adopters." She names Huang et al. (2021), Delmonte et al. (2020), and Ma et al. (2022) as the notable exceptions. 
- The moment-of-charging decision is empirically thin. Kubli identifies three possible entry points for initiating smart charging (at EV purchase, through contracts, at the charging event itself) and states that the third, "in the moment of charging," is "relatively unchartered terrain" empirically.

- RQ: "To what extent are EV drivers willing to adjust the charging location, duration, and charging mode to enable smart charging?"
  - "Which consumer segments are crucial to consider when designing smart charging solutions?"
  - "Which compensation should operators offer to incentivize EV drivers to adopt smart charging?"


## Contributions (What?)

- The "sweet home bias" finding. Kubli concludes that "a bias for home charging among EV drivers was found. The sweet home bias implies that other charging options at other locations will have to be disproportionally more attractive, so EV drivers choose to switch to these alternatives."
- Segment 1, the price-sensitive majority (53.2 percent). These respondents weight charging costs very heavily (importance of 51.3) and care relatively little about the charging mode (importance of 11.0). Kubli describes them as good targets for smart charging offers that come with financial incentives, and positions them as the likely early and late majority of smart charging diffusion. 
- Segment 2, the comfort-protective group (18.7 percent). These respondents weight the charging mode attribute far above everything else (importance of 47.1), driven by a strongly negative evaluation of ECO charging specifically. They reject having the provider manage the charging process aggressively, though they tolerate Standard mode. Kubli describes them as unsuitable targets for advanced smart charging offers.
- Segment 3, the smart-charging-curious group (28.1 percent). These respondents have a relatively balanced weighting across location, charging costs, and charging mode, and uniquely among the three segments they actively prefer ECO mode. Their part-worth utility curve on the charging mode attribute runs in the opposite direction to the other two segments. Kubli identifies them as the priority early-adopter target for smart charging providers and notes that non-financial compensation (for example, framing around climate contribution or grid support) may work for this group.
- Practical marketing implication: Segment 3 should be targeted first, with communication emphasising innovativeness, grid support, and renewable energy integration; Segment 1 (price-sensitive early and late majority) should be targeted later with financial arguments.
- willingness-to-adopt (WTA): A typical driver's home baseline costs 10 CHF. Kubli calculates that workplace ECO charging has to be priced at 2.79 CHF or lower (a 7.21 CHF reduction) before the average driver would accept it as an equivalent option.


### Concepts Extracted

- 

### Relevant Quotes or Data

- 

### My thoughts

- 

## Methodology (How?)

- Approach: A web-based choice experiment using the choice-based conjoint analysis method. Kubli motivates this by noting that choice experiments are "excellent tools to measure consumers' preferences for products or services where revealed preferences cannot yet be measured due to a lack of market penetration (Hensher et al., 2005)."
- Theoretical grounding: The method builds on utility maximisation theory, where the utility of a decision option is modelled as the sum of part-worth utilities for each attribute level (Equation 1 in the paper).
- Experimental design: Four attributes, each with three levels:
1. Location: at home, at work, at a public charging station.
2. Charging costs: 0 CHF, 10 CHF, 20 CHF.
3. Charging duration: 2 hours, 4 hours, 6 hours.
4. Guaranteed range after 50 percent of the charging duration, operationalising charging mode: 5 percent (ECO), 50 percent (Standard), 95 percent (Comfort).
Each respondent was presented with a narrative scenario (departing in the morning, needing a 120 km range extension during the day, three charging options available) and then nine choice tasks, each with three charging offers. Choice tasks were generated using full computerised randomisation with a "balanced overlap" approach (Chrzan and Orme, 2000).
- Scenario design rationale: Kubli explicitly controlled for three things: avoiding range anxiety interference, providing light decision pressure without emergency framing, and allowing all charging options to be combined with planned activities.
- Early scoping: "The early scoping phase of this research was supported by three interviews with practitioners active in the field of smart EV charging." These interviews highlighted location, duration, and time of day as grid-relevant attributes, and location and duration were subsequently included in the choice experiment.
- Sample: 202 qualified respondents, drawn from a larger Swiss-representative sample of 1,021 (Cousse et al., 2020) recruited by a Swiss market research agency (intervista). Three screening criteria: (a) current EV or PHEV owners; (b) intending to buy a car in the next two years with EV as first or second choice; (c) intending to buy a car in the next three to five years with EV as first or second choice.
This yielded 9 percent actual owners, 31 percent 2-year intenders, and 60 percent 3-to-5-year intenders. The survey was run in German and French in early 2020, using Sawtooth's Lighthouse Studio.
- Estimation: Hierarchical Bayes (HB) estimation for the part-worth utilities, which Kubli justifies with reference to Orme (2000) and Lenk et al. (1996) on the grounds that HB produces more precise estimates under preference heterogeneity. Model fit is reported as RLH = 0.61, which she notes is 1.83 times better than the null likelihood of 0.333 (three options per task).
- Willingness-to-accept calculation: WTA is computed as the difference between the part-worth utility of a reference level and the target level, divided by the linear monetary utility value of the charging cost attribute (Equations 2 and 3). Negative WTA means compensation is required; positive WTA means the driver would pay extra.
- Segmentation: Latent class multinomial logit analysis via Sawtooth (2021), tested with two, three, four, and five groups. Statistical criteria split: BIC and CAIC favoured the 3-group model, AIC and ABIC favoured the 5-group model. Kubli selected the 3-group model based on the qualitative distinctness and explanatory power of the resulting segments, noting that adding further groups "could not provide fundamentally new insights of the same practical value."
- Scenario analysis: WTA values are applied to three concrete application scenarios (shifting to workplace ECO charging, shifting to faster ECO home charging, shifting to public ECO charging), each producing a break-even charging tariff.
 - One methodological caveat Kubli herself flags: the study does not include an explicit attribute for the electricity source (for example, whether the charging power is solar), and she notes that "on individual level there may however some interactions remaining" between attributes despite the balanced-overlap design being intended to avoid this. She positions location-specific analysis, solar-power attributes, and later-adopter segments as future work.       

---

**Backlinks:** (Foam auto-populates this section)