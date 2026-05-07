Here is the **complete list** of Summary Tasks, Activities, and Milestones for your MS Project file.

---

## Summary Tasks (6 total)

| # | Summary Task Name |
|---|-------------------|
| 1 | Project Initiation & Planning |
| 2 | Game Design |
| 3 | Game Development |
| 4 | Computer Vision Module |
| 5 | Integration & Prototype |
| 6 | Testing & Feedback |
| 7 | Final Improvements & Launch |

---

## Activities (3+ per Summary Task)

### Summary Task 1: Project Initiation & Planning (April 1–15, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Kickoff meeting with sponsor | 2 days | - |
| Define game requirements & scope | 5 days | 1 |
| Setup GitHub & university cloud | 3 days | 2 |

### Summary Task 2: Game Design (April 16 – May 25, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Design puzzle clues & map locations | 10 days | 3 |
| Create wireframes & UI mockups | 8 days | 3 |
| Design database schema for locations | 5 days | 4 |

### Summary Task 3: Game Development (May 26 – July 20, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Build navigation & map screen | 12 days | 4,5 |
| Implement quest & clue system | 15 days | 7 |
| User profile & progress saving | 8 days | 8 |

### Summary Task 4: Computer Vision Module (May 26 – July 10, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Collect reference photos of campus spots | 10 days | 3 |
| Implement SSIM image comparison | 12 days | 3 |
| Test CV accuracy with sample images | 6 days | 11 |

### Summary Task 5: Integration & Prototype (July 11 – August 1, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Integrate CV with game engine | 8 days | 9,12 |
| Internal debugging & fixes | 6 days | 14 |
| **MILESTONE: Prototype ready** | 0 days | 15 |

### Summary Task 6: Testing & Feedback (August 2 – September 1, 2026)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Recruit & train 10 student ambassadors | 5 days | 16 |
| Run first test & collect bug reports | 10 days | 18 |
| Analyze feedback & prioritize fixes | 5 days | 19 |
| **MILESTONE: First test completed** | 0 days | 20 |

### Summary Task 7: Final Improvements & Launch (September 2 – January 31, 2027)

| Activity | Duration | Predecessor |
|----------|----------|-------------|
| Implement high-priority fixes | 15 days | 21 |
| Add training videos & help section | 10 days | 22 |
| Prepare launch event & marketing | 12 days | 22 |
| Deploy to university cloud | 5 days | 23 |
| Final sign-off from vice presidency | 3 days | 25 |
| **MILESTONE: Project completion** | 0 days | 26 |

---

## Milestones (3 total)

| Milestone | Date | Description |
|-----------|------|-------------|
| **M1: Prototype ready** | August 1, 2026 | First playable version with basic CV working |
| **M2: First test completed** | September 1, 2026 | Student ambassadors finished testing, feedback collected |
| **M3: Project completion** | January 31, 2027 | Final product delivered, vice president signed off |

---

## Dependencies Explained

| Dependency | Type | Why |
|------------|------|-----|
| Game Design → Game Development | FS | You need designs before coding |
| Game Design → CV Module | FS | You need location list before collecting photos |
| Game Dev + CV → Integration | FS | Both must be ready before integration |
| Prototype → Testing | FS | Need something to test |
| Testing → Final Improvements | FS | Need feedback before fixing |
| Final Improvements → Launch | FS | Fixes done before deployment |

---

## Visual Summary Table (for your report)

```
Timeline: April 1, 2026 ———————————————————————————— January 31, 2027

Summary 1: Setup         [██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░]
Summary 2: Design        [░░███░░░░░░░░░░░░░░░░░░░░░░░░░░░]
Summary 3: Game Dev      [░░░░████████░░░░░░░░░░░░░░░░░░░░]
Summary 4: CV Module     [░░░░██████░░░░░░░░░░░░░░░░░░░░░░]
Summary 5: Integration   [░░░░░░░░██░░░░░░░░░░░░░░░░░░░░░░]
Summary 6: Testing       [░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░]
Summary 7: Final+Launch  [░░░░░░░░░░░░████████████████████]

Milestones:              ▲           ▲                    ▲
                         Aug 1       Sep 1               Jan 31
                    (Prototype)   (Test done)        (Delivery)
```

---

Do you want me to also provide this in a **copy-paste format for MS Project** (tab-delimited text you can import directly)?