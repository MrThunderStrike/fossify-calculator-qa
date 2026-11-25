# UI Test Checklist - Fossify Calculator

**Document type:** Retrospective reconstruction of an accepted training checklist  
**Original design:** Practice #63 (2026-11-21)  
**Historical execution:** Practices #64-67 (2026-11-21)  
**Reconstructed:** 2026-11-25  
**Application:** Fossify Calculator  
**Environment:** OnePlus 13R, Android 16  
**Application version note:** Version 1.4.0 (10) was verified on the physical device before reinstall; it was not independently rechecked after reinstall.  
**Requirements:** Simulated training requirements, not official Fossify acceptance criteria  
**Execution source:** Previously reviewed screenshots, learner observations, and QA project history. No new tests were performed for this document.

## Checklist and historical results

| ID | UI check | Reconstructed expected result (training criterion) | Historical actual observation | Recorded status | Evidence / qualification |
|---|---|---|---|---|---|
| UI-01 | Layout and controls | Calculator controls, including digits 0-9 and operators, are visible without obvious clipping or overlap in portrait view. | Numeric buttons and operators were visible; no clipping or overlap was observed. | Passed | Portrait screenshot from Practice #64. |
| UI-02 | Labels and symbols | Labels on visible calculator controls can be read. | Control labels and arithmetic symbols were readable in the reviewed portrait screenshot. | Passed | Same portrait screenshot from Practice #64; limited to observed display. |
| UI-03 | Readability at brightness extremes | Digits remain readable at minimum and maximum device brightness. | Learner reported readable digits at both settings. | Passed (user-reported) | No independent brightness values or setting-state screenshots were captured. |
| UI-04 | Light and Dark themes | Calculator UI is readable in the observed Light and Dark theme appearances. | Reviewed Light and Dark theme screenshots showed readable controls. | Passed | Dark-theme portrait and Light-theme portrait screenshots. Theme-toggle steps were not independently verified. |
| UI-05 | Portrait orientation | Calculator UI is usable and visible in portrait orientation. | Portrait layout was visible and controls were readable. | Passed | Portrait screenshots. Landscape support was observed separately but was not mandatory under the simulated requirement. |
| UI-06 | Numeric input display | Entered numeric input is displayed and remains visible in the tested interface. | `123` was shown in a landscape screenshot, with calculator rows visible and no confirmed bottom-row clipping. | Passed | Landscape screenshot showing `123`; the tap sequence is based on prior user execution, not independently proven by the image alone. |

## Summary

- **Design:** 6/6 training UI checklist items accepted in Practice #63.
- **Historical execution:** 6/6 selected UI checks recorded as Passed in Practices #64-67 on the physical Android 16 device.
- **Confirmed real application defects in this UI scope:** None.
- **Additional exploration:** Landscape UI was observed. An initial clipping concern was not reproduced. Landscape support was not a mandatory simulated requirement.
- **Traceability:** Historical UI screenshots are organized in `evidence/ui/` (4 JPG files). Screenshot filenames and individual test-step traceability should be checked against the local originals before external publication.

## Limits of this record

This is a retrospective reconstruction from an accepted practice log, **not** a verbatim copy of the original checklist or a new execution report. The Expected Results above are concise reconstructions of the training checks, not official product requirements. UI-03 relies on the learner's observation; screenshots do not independently prove brightness settings, theme-switching actions, numeric keypress sequences, or all device actions. These UI checks were **not** entered or executed as a Qase Test Run. Passing the six checks does not establish full UI accessibility, compatibility, or complete product quality.
