# MVP user stories — Haptic Vision

These proposed stories translate the September 24 partner discussion and the product scope in Q1–Q3 into testable requirements. They describe intended behaviour, not functionality already implemented. Partner acceptance is pending. The software prototype will generate and display a lightweight 3D representation; physical tactile output and robotic hardware integration remain outside our team's scope. Accessible controls and a text equivalent support software testing, but do not replace the eventual tactile experience.

## US1 — Choose and control the capture source

As a blind or low-vision computer user, I want to choose which window or screen is captured and start, pause, or stop capture in order to control what content the system processes.

Acceptance criteria:
- Given capture has not started, no screen frames are processed until I choose a source and grant the required permission.
- Given permission is granted, I can start capture from a browser window or a non-browser application on the documented supported operating system.
- When I pause or stop, no new frames enter processing; the interface announces the state, and stopping releases the capture stream.
- If permission is denied or the source closes, the system announces the problem and provides a keyboard-accessible way to choose another source.

## US2 — Understand the interface's spatial layout

As a blind or low-vision computer user, I want the captured interface converted into a structured 3D representation in order to understand where important regions and controls are located.

Acceptance criteria:
- For each reference screen in the partner-reviewed evaluation set, the agreed key regions appear in the generated scene with their relative left/right and above/below relationships preserved.
- Each represented region has a stable identifier while it remains recognisable, source bounds, a type or an explicit unknown type, and a label where available.
- A keyboard-accessible element list exposes the same labels and spatial relationships as the scene, without requiring users to interpret the visual canvas.
- Content that cannot be interpreted is marked as unknown rather than assigned an invented description; the rest of the scene remains usable.

## US3 — Keep the representation up to date

As a blind or low-vision computer user, I want the representation to update when the source changes in order to explore the current interface rather than an outdated screen.

Acceptance criteria:
- When I scroll or navigate in the selected source, the scene updates automatically and removes regions that are no longer visible.
- Each scene records its source-frame timestamp; late analysis results cannot overwrite a newer scene.
- Under overload, processing keeps the most recent pending frame instead of building an unbounded queue. An accessible status identifies processing delays or stale output.
- Our provisional target is a visible update within two seconds for at least 18 of 20 scripted screen changes on a documented reference machine and fixture set. The partner must review this target; it is not a measured result or a guarantee for arbitrary content.

## US4 — Adjust depth, scale, and emphasis

As a blind or low-vision computer user, I want to adjust the representation's depth, scale, and emphasis in order to make important information easier for me to distinguish.

Acceptance criteria:
- Keyboard-operable controls let me change depth and scale within labelled limits, with numeric values available to a screen reader.
- I can select a represented region and increase its emphasis without changing its source location or the ordering of surrounding regions.
- Changes update the current scene without restarting capture and remain applied when subsequent frames arrive during the session.
- Reset restores the documented defaults. Invalid values are rejected with an accessible explanation.

## US5 — Activate a represented control

As a blind or low-vision computer user, I want to activate a control through its representation in order to perform the corresponding action in the original interface.

Acceptance criteria:
- On a controlled demonstration page, selecting a recognised button through either the scene or its keyboard-accessible list identifies the corresponding source control.
- An explicit activation triggers that control exactly once and the resulting source change appears in the next scene update.
- The interaction adapter checks the current source identity, window geometry, and scene freshness before acting. If the source moved, changed, or cannot be matched confidently, it rejects the action and requests a refresh.
- Inspection alone never triggers an action. Unsupported controls are announced as unavailable.

This is a bounded interaction demonstration, subject to partner confirmation. General control of arbitrary desktop applications, text entry, dragging, and hardware touch input are not promised for the MVP.

## US6 — Complete the workflow without a mouse

As a blind or low-vision computer user, I want accessible navigation and feedback throughout the application in order to use the capture and exploration workflow independently.

Acceptance criteria:
- I can choose a source, start or stop capture, explore the element list, adjust settings, and activate a supported demo control using only the keyboard, with no focus traps.
- Every interactive control has an accessible name, visible focus indicator, and exposed state/value.
- A documented screen-reader and operating-system combination announces capture state, processing failures, and selected-element changes without repeatedly announcing every incoming frame.
- Scene updates preserve focus on a surviving element; if it disappears, focus moves to a predictable location and its removal is announced.

## Review and validation

US1–US4 and US6 form the proposed capture-to-representation workflow. US5 adds the limited return interaction described in Q1; its priority and scope require explicit partner review. We will validate these stories against annotated interface fixtures, keyboard/screen-reader walkthroughs, and a partner demonstration. Fixture selection, supported OS, reference hardware, latency target, vector schema, and input permissions must be agreed before implementation acceptance.

**Partner review status:** No approval or sent-review evidence is included yet. Before D1 submission, the team must share this artifact with Alex through its existing liaison and add a link to the actual communication or approval evidence. The September 24 discussion informed these stories but does not constitute approval of this specific story set.
