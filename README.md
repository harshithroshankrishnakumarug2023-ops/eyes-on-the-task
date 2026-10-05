# Eyes on the Task: Cognitive Load, Distractors and Attention

Completed group project, 2026. Department of Psychology, Ashoka University.
Supervisor: **Professor Dipanjan Ray**.

**Research question.** What is the effect of task difficulty and distractor
relevance on attentional distraction in university students performing a
logical reasoning task, as measured by eye-tracking?

Cognitive load theory holds that processing capacity is limited, so
performance declines once demand exceeds capacity. Attentional control theory
adds that the effort involved in a task changes how attentional resources are
allocated: under high load, top-down control should dominate and distraction
should fall. Most previous work has looked at relevant and irrelevant
distractors separately; this study looks at both at once, at two levels of
load, which is closer to how attention is actually competed for in digital
settings.

## Method

| | |
| --- | --- |
| Design | 2 (cognitive load: high, low) × 2 (distractor relevance: relevant, irrelevant), within-subjects |
| Participants | 10 undergraduate students aged 17–22 at Ashoka University, recruited by nomination |
| Task | Raven's Progressive Matrices levels 1 (low load) and 5 (high load), in 15-minute slots |
| Distractors | Animated ghost images as irrelevant distractors; answer options as relevant distractors |
| Measures | Gaze points on relevant and irrelevant distractors, counted manually by three researchers; correct answers recorded |
| Software | PsychoPy, Tobii Pro Fusion, Jamovi 2.3 |

Participants were told only the task procedure, not the study's objectives.
The first five completed the high-load condition first and the remainder the
low-load condition first, with a break between conditions, and were debriefed
at the end.

Analysis used descriptive statistics and Shapiro-Wilk tests for all four
conditions, then a two-way repeated-measures ANOVA. With two levels per factor,
sphericity was already satisfied.

## Findings

Participants were distracted by irrelevant distractors significantly more than
by relevant ones, regardless of load. Task difficulty had no significant main
effect on total distraction, but it interacted with relevance: under low load,
gaze points on irrelevant distractors were higher.

- Main effect of distractor relevance: F(1, 9) = 66.92, p < .001, η² = .881
- Relevance × difficulty interaction: F(1, 9) = 17.31, p = .002, η² = .658

Attentional control theory holds up; cognitive load on its own does not predict
distraction.

## Team

Supervisor: Professor Dipanjan Ray. Experimental design and programming,
eye-tracker calibration, manual gaze coding and analysis by Harshith Roshan
Krishna Kumar, with Aditi Dahiya, Cheryl Joshi, Himanshi Lashkari, Khushi Mohta
and Sumi Gupta.

## Documents

- [`Eyes_on_the_Task_Report.pdf`](Eyes_on_the_Task_Report.pdf) — full project report
- [`Eyes_on_the_Task_Stimulus_Sheets.pdf`](Eyes_on_the_Task_Stimulus_Sheets.pdf) — stimulus sheets

## Links

- [Project page](https://harshithroshankrishnakumarug2023-ops.github.io/harshithroshan.github.io/research/eyes-on-the-task/)
- [Website](https://harshithroshankrishnakumarug2023-ops.github.io/harshithroshan.github.io/)