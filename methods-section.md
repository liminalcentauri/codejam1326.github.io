# Method

## Overview

This research employs a two-study design to investigate how AI interaction characteristics shape psychological mechanisms and, ultimately, relational outcomes in the context of AI-enabled emotional support. Study 1 is an exploratory pilot that uses naturalistic user-generated data to surface recurring themes and refine the conceptual model grounded in the Stimulus–Organism–Response (SOR) framework (Mehrabian & Russell, 1974). Study 2 is a cross-sectional survey that subjects the resulting model—and its four focal hypotheses—to a quantitative test. This iterative sequence reflects a growing consensus in consumer-AI research that lived user experience should inform, rather than merely illustrate, theory development (Puntoni et al., 2021).

---

## Study 1: Exploratory Pilot

### Purpose

Because empirical evidence on how consumers experience generative-AI chatbots in mental-health contexts remains scarce, a necessary first step is to capture the user perspective in a systematic yet open-ended fashion. Study 1 therefore examines naturally occurring online discourse to identify the interaction characteristics, psychological mechanisms, and relational outcomes that users themselves regard as salient.

### Data Collection

Data were collected in early 2026 from the subreddit r/therapyGPT using a web-scraping procedure implemented in R. The subreddit describes itself as "a community for people using AI as a tool for emotional support, self-reflection, and personal growth," making it a theoretically appropriate source for the phenomena under investigation. At the time of data collection, the community comprised approximately 25,000 members and attracted roughly 32,000 weekly visitors, ensuring sufficient volume and variety of discourse. The scraping procedure yielded an initial corpus of 645 posts. After removing duplicates, deleted entries, and posts that fell outside the scope of the study (e.g., purely technical troubleshooting), the final analytical sample comprised 554 posts.

### Ethical Considerations

All data are publicly available and were anonymized prior to analysis: usernames, identifying details, and direct quotations that could enable re-identification were removed or paraphrased. These precautions align with established ethical guidelines for internet-mediated research (British Psychological Society, 2021).

### Analytical Approach

We conducted a reflexive thematic analysis following Braun and Clarke's (2006) six-phase protocol. The analysis proceeded as follows. First, the lead author engaged in repeated close reading of the corpus to achieve familiarization. Second, initial codes were generated inductively by identifying recurring semantic and latent patterns across posts. Third, codes were grouped into candidate themes through iterative comparison. Fourth, candidate themes were reviewed against both the coded extracts and the full data set to ensure internal coherence and external distinctiveness. Fifth, themes were defined, named, and mapped onto the theoretical dimensions of the SOR framework. Sixth, the final thematic structure was documented in a detailed audit trail.

To enhance the rigor and transparency of this process, we applied the 6R (Relevance, Rigor, Reflexivity, Reporting, Resonance, and Reach) and the 4R (Relevance, Rigor, Resonance, Reflexivity) quality frameworks as articulated by Naeem et al. (2023). This structured evaluation ensured that emergent themes were not only data-driven but also theoretically coherent and methodologically defensible.

### Expected Contribution of Study 1

The pilot is designed to accomplish two goals. First, it provides ecological validity for the constructs specified in the conceptual model—namely, accessibility, personalization, non-judgment, and support quality as stimuli; emotional support, perceived effectiveness, and trust as organism-level mechanisms; and relational bond (emotional attachment and dependence) and continuance intention as response-level outcomes. Second, it allows us to detect any salient dimensions that the extant literature may have overlooked, thereby refining the measurement model prior to the confirmatory phase.

---

## Study 2: Cross-Sectional Survey

### Design Rationale

Study 2 tests the full conceptual model (Figure 1) using structural equation modeling (SEM). A cross-sectional survey design is appropriate here for three reasons. First, the model involves a substantial number of latent constructs—four stimulus-level variables, three organism-level mediators, two relational-bond dimensions, one behavioral-intention outcome, and a three-faceted moderator—making experimental manipulation impractical. Second, the research question centers on the covariance structure among these constructs as experienced by actual users rather than on causal effects elicited through randomized treatments. Third, survey methodology allows for efficient data collection from a geographically dispersed population of chatbot users whose behavior occurs in naturalistic, private settings that are difficult to observe directly.

### Participants and Sampling Strategy

Participants are recruited from two complementary channels. The first channel is Prolific, an online research platform that provides access to a pre-screened, demographically diverse participant pool. The second channel consists of targeted recruitment on Reddit communities whose members actively discuss AI-mediated emotional support, thereby increasing the ecological relevance of the sample.

*Inclusion criteria.* Participants must (a) be 18 years of age or older, and (b) have used a generative-AI chatbot (e.g., ChatGPT, Gemini, Claude, Replika, or a comparable service) for emotional support, self-reflection, or personal growth at least once in the preceding three months. The recency criterion ensures that participants can draw on salient, accessible memories of their interactions.

*Sample size.* The target sample size is 300–400 completed responses. This range is derived from an a priori power analysis conducted with G\*Power 3.1 (Faul et al., 2009), specifying a medium effect size (*f*² = 0.15), α = .05, and statistical power = .80. These parameters ensure adequate power to detect the hypothesized direct, mediated, and moderated effects in the SEM framework while providing a reasonable buffer for incomplete or low-quality responses.

### Procedure

The survey is administered via Qualtrics and is designed to be completed within approximately ten minutes to minimize respondent fatigue and dropout. After providing informed consent, participants complete a brief screening module to confirm eligibility. Qualified respondents then proceed through the following sections in sequence:

1. **Introduction and orientation.** Participants are reminded of the study's focus on their personal experience with AI chatbots used for emotional support. They are asked to keep in mind the chatbot they have used most frequently for this purpose.

2. **Main survey items.** All multi-item scales are presented in a randomized order within each construct block to control for potential order effects. The measurement instruments are detailed below (see *Measures*).

3. **Platform and usage information.** Participants report the primary chatbot platform they use (e.g., ChatGPT, Claude, Gemini, Replika) along with approximate frequency and duration of use.

4. **Demographics.** Standard demographic items (age, gender, education, country of residence) are collected.

5. **Debriefing.** Participants receive a debriefing statement that explains the study's objectives, provides mental-health resources, and offers contact information for follow-up questions.

Attention checks are embedded at multiple points throughout the survey. Responses that fail more than one attention check are flagged for exclusion during data cleaning.

### Measures

All constructs are measured with multi-item scales drawn from or adapted from validated instruments in the marketing, information-systems, and consumer-psychology literatures. Unless otherwise noted, items are rated on 7-point Likert scales ranging from 1 (*strongly disagree*) to 7 (*strongly agree*). The full item wordings appear in the Appendix (Measurement Model Table).

#### Stimulus Variables: AI Interaction Characteristics

**Accessibility** (3 items). Captures the perceived ease and availability of the chatbot for emotional-support purposes, including always-on availability and low barriers to entry relative to traditional alternatives. Items are adapted from Chen et al. (2022) and Borsci et al. (2021). A sample item is: "The AI chatbot is available to me whenever I need it."

**Personalization** (4 items). Measures the degree to which users perceive the chatbot as tailoring its responses to their individual needs, usage behavior, and preferences. Items draw on Won and Kim (2025) and Lavado-Nalvaiz et al. (2022). A sample item is: "The information provided by AI chatbot is tailored to me."

**Non-judgment** (3 items). Assesses the extent to which users perceive the chatbot as responding without social evaluation or criticism. The items adapt the logic of the Fear of Negative Evaluation scale (Leary, 1983) to the chatbot context, informed by Zhang (2025). Two items are reverse-coded (e.g., "I felt judged by this chatbot [R]").

**Support quality** (3 items). Captures users' overall evaluation of how helpful, relevant, and appropriate the chatbot's responses are in the context of emotional support. Items are adapted from the AI Chatbot Service Quality (AICSQ) scale of Chen et al. (2022). A sample item is: "The chatbot's responses were helpful and relevant."

#### Organism Variables: Psychological Mechanisms

**Emotional support** (3 items). Measures the felt experience of being comforted, validated, and emotionally understood during and after the interaction. Items are adapted from the Online Social Support Scale of Nick et al. (2018), focusing on the esteem and emotional support dimensions. A sample item is: "This chatbot made me feel understood."

**Perceived effectiveness** (4 items). Reflects the cognitive appraisal that chatbot use helps the user cope, reflect, or manage personal issues more effectively. Items build on Bhattacherjee's (2001) confirmation and effectiveness measures. A sample item is: "Using this chatbot helped me cope more effectively in this situation."

**Trust** (3 items). Captures users' willingness to rely on generative AI in situations involving personal vulnerability and uncertainty. Items are drawn from Esfahani et al. (2025). A sample item is: "I trust Generative AI to support decision-making in the absence of a therapist."

#### Response Variables

**Relational bond—Emotional attachment** (5 items). Measures the sense of personal meaningfulness, familiarity, closeness, and forward-looking engagement with the chatbot. Items are drawn from the AI Attachment Scale of Kasturiratna and Hartanto (2025), specifically the emotional closeness dimension. A sample item is: "I feel a sense of closeness/connection with this chatbot."

**Relational bond—Dependency** (3 items). Captures the degree to which the chatbot serves as a primary or irreplaceable source of support. Items adapt the social substitution dimension of the AI Attachment Scale (Kasturiratna & Hartanto, 2025). A sample item is: "It would be hard to replace this chatbot with another source of support."

**Continuance intention** (3 items). Measures the behavioral intention to continue using the chatbot in the future. Items are adapted from Bhattacherjee's (2001) IS continuance model and Ngo et al. (2025). One item is reverse-coded: "If I could, I would like to discontinue use of this chatbot [R]."

#### Moderator Variable

**Perceived risk** is operationalized as a three-dimensional construct:

- *Privacy concerns* (3 items). Assesses worry about the confidentiality and potential misuse of information shared with the chatbot. Items are adapted from Featherman and Pavlou's (2003) privacy-risk facet. A sample item is: "I worry my data could be shared without my consent."

- *Safety concerns* (3 items). Captures perceived potential for the chatbot to cause psychological harm or to lead the user in a harmful direction. Items adapt the psychological and overall risk logic of Featherman and Pavlou (2003). A sample item is: "This chatbot could lead me in the wrong direction in a harmful way."

- *Frustration* (3 items). Measures concerns about wasted effort, misunderstanding, and conversational derailment. Items draw on the time and performance risk logic of Featherman and Pavlou (2003). A sample item is: "I worry the chatbot could misunderstand me and derail the conversation."

### Analytical Strategy

Data analysis proceeds in two stages, following the two-step approach recommended by Anderson and Gerbing (1988).

*Stage 1: Measurement model.* We first estimate a confirmatory factor analysis (CFA) to evaluate the psychometric properties of all latent constructs. Convergent validity is assessed through standardized factor loadings (≥ .60), average variance extracted (AVE ≥ .50), and composite reliability (CR ≥ .70). Discriminant validity is evaluated using the Fornell–Larcker criterion (Fornell & Larcker, 1981) and the heterotrait–monotrait (HTMT) ratio of correlations (Henseler et al., 2015). Model fit is evaluated using a combination of fit indices, including the comparative fit index (CFI ≥ .90), the Tucker–Lewis index (TLI ≥ .90), the root mean square error of approximation (RMSEA ≤ .08), and the standardized root mean square residual (SRMR ≤ .08).

*Stage 2: Structural model.* Once adequate measurement properties are established, we estimate the full structural equation model to test the hypothesized paths:

- **H1** posits that AI interaction characteristics (accessibility, personalization, non-judgment, and support quality) positively predict the three psychological mechanisms (emotional support, perceived effectiveness, and trust).
- **H2** posits that the psychological mechanisms positively predict relational bond (emotional attachment and dependence).
- **H3** posits that relational bond positively predicts continuance intention.
- **H4** posits that perceived risk (privacy concerns, safety concerns, and frustration) negatively moderates the relationship between psychological mechanisms and relational bond—that is, at higher levels of perceived risk, the positive effects of emotional support, perceived effectiveness, and trust on attachment and dependence are attenuated.

The moderation effect (H4) is tested by including the interaction terms between the organism-level variables and the second-order perceived-risk construct. To reduce multicollinearity, all indicators are mean-centered before computing interaction terms (Aiken & West, 1991). We use bootstrapping with 5,000 resamples to obtain bias-corrected confidence intervals for all direct, indirect, and conditional effects (Hayes, 2022), providing robust inference that does not rely on distributional assumptions.

All analyses are conducted using Mplus (Muthén & Muthén, 2017) or the *lavaan* package in R (Rosseel, 2012), both of which accommodate the estimation of complex mediated-moderation models with latent variables.

### Controls

To rule out alternative explanations, we include several covariates: participant age, gender, education level, the specific chatbot platform used, and self-reported frequency of use. These variables are included as controls on the endogenous variables in the structural model to ensure that observed relationships are not artifacts of demographic differences or usage intensity.

---

## Summary

The two-study design balances ecological validity with statistical rigor. Study 1 grounds the conceptual model in the lived experience of AI-chatbot users, leveraging naturalistic discourse to ensure that the theoretical constructs resonate with actual use patterns. Study 2 then subjects the model to a confirmatory quantitative test, using validated multi-item measures and structural equation modeling to evaluate the hypothesized stimulus → organism → response pathways and the moderating role of perceived risk. Together, the studies provide a comprehensive empirical basis for understanding how and why consumers form relational bonds with AI-enabled emotional-support chatbots—and under what conditions those bonds are strengthened or suppressed.
