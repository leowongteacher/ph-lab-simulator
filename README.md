# pH Testing Lab Simulator

A teacher guide to an English-language, interactive simulator designed for Hong Kong Secondary 2 science. Students practise testing five substances with universal indicator, pH paper and a pH meter by moving apparatus, observing changes and recording results.

**[Open the simulator](https://leowongteacher.github.io/ph-lab-simulator/)** · [Download the single HTML file](https://github.com/leowongteacher/ph-lab-simulator/blob/master/index.html)

## At a glance

| Item | Details |
| --- | --- |
| Intended learners | Hong Kong Secondary 2 students |
| Language | English |
| Experiments | Universal Indicator, pH Paper, pH Meter |
| Format | One self-contained `index.html`, containing HTML, CSS, JavaScript and SVG apparatus |
| Installation | None; open the website or download the HTML file |
| Input | Mouse or touch drag-and-drop |
| Screen size | Designed for a minimum viewport width of 768px; landscape is recommended on tablets |
| Student accounts | Not required |
| Progress storage | In memory only; refreshing or closing the page loses progress |
| Submission | No teacher dashboard, automatic submission or built-in results export |

## Learning objectives

Use the simulator to help students:

- **Follow procedures:** select and use the three testing methods through practical interactions rather than a sequence of Next buttons.
- **Classify substances:** apply the simulator's rule that pH below 7 is acidic, pH 7 is neutral and pH above 7 is alkaline.
- **Observe and record:** compare colours with a pH 0–14 chart and wait for a stable meter reading.
- **Avoid contamination:** rinse the dropper or probe before changing substances.
- **Compare apparatus:** discuss speed, sample use, colour interpretation and numerical readings.
- **Practise safety habits:** put on the character's goggles before using the apparatus.

This is a teaching model, not a substitute for supervised practical work or a laboratory safety assessment.

## Before the lesson

1. Open the [live website](https://leowongteacher.github.io/ph-lab-simulator/) on the devices students will use. Check the school's network before class.
2. Demonstrate one drag-and-drop action. Move the relevant tip or the centre of the apparatus onto its target, then release.
3. Drag the blue goggles at the top right onto the character's eyes. The status changes to **Goggles on**, unlocking the apparatus.
4. Show students the steps, feedback panel, results table and colour chart. On narrower screens, they will need to scroll to the steps and table.
5. Ask students to complete and capture their work before refreshing or leaving the page.

### Suggested lesson sequence

This is a suggested plan, not a measured completion time. Consider two lessons so students have time to explore errors and discuss the evidence.

| Stage | Teacher action | Student evidence |
| --- | --- | --- |
| Introduction | Review the pH scale and demonstrate goggles and rinsing | Predictions for the five substances |
| First lesson | Guide Universal Indicator, then introduce pH Paper | Completed tables and one explanation of an error |
| Second lesson | Complete pH Meter and the remaining experiments | Stable readings, completed tables and quiz score |
| Discussion | Compare the methods and connect the simulation to a real practical | A justified choice of apparatus for a given task |

For pair work, one student can operate while the other reads the steps and checks the recording. Swap roles between experiments.

## Substance guide

These are the fixed model values used by this simulator, not guaranteed measurements for real samples or commercial products. Tubes A–E and spot plate holes 1–5 follow the same order.

| Tube | Hole | Substance | Model pH | Expected classification |
| --- | --- | --- | --- | --- |
| A | 1 | HCl (dilute) | 1 | Acidic |
| B | 2 | Lemon juice | 2.5 | Acidic |
| C | 3 | Ethanoic acid (dilute) | 3 | Acidic |
| D | 4 | Distilled water | 7 | Neutral |
| E | 5 | Glass cleaner | 10.5 | Alkaline |

## Running the experiments

### Universal Indicator

Complete one tube at a time if preferred; there is no penalty for doing so.

1. Drag the dropper's tip into the matching substance bottle and release. It fills to 2 cm³.
2. Move the tip over the matching test tube and release. Four animated drops transfer the whole 2 cm³ automatically.
3. Move the universal indicator bottle over the tube. The first drop is added automatically; tap or click the positioned bottle twice more, waiting for each drop to finish, to reach three drops.
4. Move the indicator bottle aside. Shake the tube with a quick side-to-side drag, or select the tube and use the SVG **Shake** control.
5. Move the tube onto the white tile, with its centre inside the tile. Only one tube can occupy the tile at a time.
6. Compare the colour with the **UI** chart, choose a pH and classification in the results table, then select **Check**.
7. Move the tube off the tile and rinse the dropper under the distilled water tap before using the next substance.

The target sample volume is 2 cm³, with an accepted range of 1.8–2.2 cm³ before adding indicator. If a tube is overfilled, move it to the waste beaker to empty it, rinse the empty tube at the tap, and refill it.

### pH Paper

1. Drag the spot plate onto the white tile to check holes 1–5.
2. Move the forceps' tip to the pH paper box to pick up a strip.
3. Place the strip into the appropriate hole. Repeat for the other holes as needed.
4. Fill the dropper from the matching bottle, then position its tip over the prepared hole and release. The simulator adds two drops automatically.
5. Keep the plate on the white tile. Compare the changed paper with the **Paper** chart and record the pH and classification.
6. Rinse the dropper at the tap before changing substances.

Touching the paper directly or dipping paper held in the forceps into a bottle or the waste beaker triggers error feedback. This activity deliberately teaches a drop-on-paper method; do not treat its restrictions as instructions for every real indicator-paper product.

### pH Meter

1. Rinse the probe under the distilled water tap before the first measurement.
2. Drag the probe into one of the prefilled 50 cm³ beakers.
3. Wait approximately 2.6 seconds for **Stabilising…** to change to **Stable**.
4. While the probe remains in that beaker, enter the reading and classification, then select **Check**.
5. Lift and rinse the probe before testing another substance.

The shelf bottles are not needed in this experiment. Switching directly between different substances without rinsing produces a deliberately shifted reading that cannot be accepted as a valid result.

## Assessment and feedback

- **Step accuracy:** calculated as successful counted actions divided by successful counted actions plus counted errors. It is an action-based practice measure, not a validated examination mark.
- **Errors:** certain incorrect actions and incorrect table submissions add to the error count. Orange sequence reminders generally do not.
- **Results table:** colour-based pH entries accept a difference of up to ±1 from the model pH. Meter entries accept a difference of up to ±0.1 from the current stable reading. Classification must also be correct.
- **Experiment completion:** all five substances must be successfully recorded in that experiment.
- **Quiz unlock:** by default, complete all three experiments in the same page session to reveal the quiz.
- **Quiz score:** three multiple-choice questions, one point each. The displayed **Total score** is the quiz score out of 3, not a combined practical-and-quiz grade.
- **Answer behaviour:** each quiz question accepts one attempt per page session and then shows feedback. After all three answers, the apparatus comparison table appears.

<details>
<summary>Teacher answer key and discussion prompts</summary>

| Question | Correct answer | Suggested follow-up |
| --- | --- | --- |
| Which apparatus gives the most precise pH value? | C. pH meter | Does showing more decimal places alone prove that a measurement is accurate? |
| Why should pH paper not be dipped directly into a solution in this activity? | B. The dye can dissolve out and contaminate the solution | How does adding a drop to a separate strip help protect the original sample? |
| Why rinse the probe between liquids? | A. To avoid cross-contamination, which gives a wrong reading | What evidence in the simulator shows that an unrinsed probe is a problem? |

Ask students to justify their choice of apparatus for a quick field check, an approximate colour comparison, and a task needing a numerical reading.

</details>

For collecting evidence, ask students to take screenshots of completed results tables and the final quiz summary and submit them through the school's usual platform. The simulator does not send results to the teacher.

## Resetting, saving and offline use

- **Changing tabs:** initialises the selected experiment again, clearing its working apparatus, current results table and current action statistics. Goggles stay on, and completed-experiment summaries are retained in memory for unlocking the quiz.
- **Restart:** resets the current experiment, not the entire session. It does not clear stored completion summaries or previous quiz answers.
- **Fresh session:** refresh the page to clear all progress, completion summaries, quiz answers and goggles status.
- **Offline use:** download `index.html` using GitHub's **Download raw file** control. On a computer, open the downloaded file in a browser; it has no external assets or dependencies. Test the local-file workflow separately on managed tablets.
- **Privacy:** the app has no student login, application database, localStorage or automatic results upload. The public website is hosted by GitHub Pages; this is not a claim about the hosting provider's own traffic logging.

## Teacher customisation

The `CONFIG` object near the beginning of the `<script>` section in `index.html` contains the main teaching settings. Back up the file before editing and test each affected experiment afterwards.

| Setting | Current value or purpose |
| --- | --- |
| `CONFIG.substances` | Five names, model pH values, liquid colours and hazard-symbol flags |
| `CONFIG.colours.ui` / `.paper` | Separate colour palettes; each must contain 15 entries for pH 0–14 |
| `CONFIG.colours.names` | Colour descriptions used in the results table |
| `CONFIG.volume` | Sample volumes, drop counts, container capacities and refill settings |
| `CONFIG.tolerance.colour` | `1`, for colour-based pH answers |
| `CONFIG.tolerance.meter` | `0.1`, for meter answers |
| `CONFIG.meter.stabiliseMs` | `2600`, the meter's stabilisation time in milliseconds |
| `CONFIG.meter.error` | `0.03`, the maximum random deviation added to a clean reading before rounding |
| `CONFIG.quizUnlock` | `'all'` for all three experiments; `'any'` for one completed experiment |
| `CONFIG.steps`, `.intro`, `.msg` | Student instructions and feedback |
| `CONFIG.quiz`, `.compare` | Quiz questions, answers, explanations and comparison content |

For example, change `quizUnlock: 'all'` to `quizUnlock: 'any'` for a shorter activity focused on one apparatus. Set `meter.error` to `0` if you want repeatable clean readings.

Keep the five-substance structure and existing substance IDs when making simple edits. Several loops, tube letters, hole assignments and feedback strings assume five substances. Changing a volume or drop count may also require updating hardcoded instructions and checks elsewhere in the file.

Commit changes to `master` to trigger the existing GitHub Pages deployment. Check that the Pages deployment succeeds before testing the live website.

## Model limitations and teaching notes

- **Illustrative chemistry:** pH values, colours and contamination effects are programmed examples. The app does not calculate concentration, dilution, acid–base reactions or temperature effects.
- **Meter display:** the current meter screen and recorded readings show two decimal places, while the input is configured in 0.1 steps and marking allows ±0.1. The quiz explanation currently says “1 decimal place”; this wording does not match the screen. Discuss the distinction between displayed resolution and measurement accuracy rather than using decimal places as proof of precision.
- **Calibration:** the comparison table mentions calibration, but students do not carry out a calibration procedure in this simulation.
- **Colour access:** colour matching remains a central task. Offer teacher support or an alternative description-based task where colour-vision differences or display settings affect access.
- **Input access:** the practical interactions require mouse or touch dragging; there is no full keyboard-only alternative.
- **Safety modelling:** the app enforces goggles, but does not check a real lab coat or replace instructions for handling chemicals and waste.
- **Browser coverage:** the public GitHub Pages version has been checked in Comet. Test your actual classroom browsers and iPads before relying on them; real-device iPad testing has not been completed as part of this project.

## Troubleshooting

| Issue | What to try |
| --- | --- |
| The old website refuses to connect | Use [the GitHub Pages website](https://leowongteacher.github.io/ph-lab-simulator/), not the earlier `pplx.app` address |
| Apparatus will not move | Put the character's goggles on first; wait for any active filling, dripping or rinsing animation to finish |
| A drop does not register | Position the tip, not just the body, over the target and release |
| A tube's colour cannot be recorded | Complete filling, indicator addition and shaking, then place the tube's centre inside the white tile |
| Paper cannot be placed | Put the spot plate on the tile first, and use the forceps to pick up paper from its box |
| Meter result is rejected | Rinse the probe, wait for **Stable**, and submit while it remains in the correct beaker |
| Steps or results seem missing | Scroll below the bench on a narrower screen |
| The page is too wide | Use a viewport at least 768px wide; try landscape orientation on a tablet |
| Quiz is not visible | Successfully record all five substances in each of the three experiments, without refreshing |
| Work disappeared | Progress is not saved between page loads; capture evidence before refreshing or closing |

When reporting an issue, include the browser, device, experiment, last action and a screenshot. Avoid including student-identifying information in a public GitHub issue.
