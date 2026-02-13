# Excalidraw Product Feedback Dataset

> **Workshop Material** — This document contains synthesized customer feedback and product analytics for Excalidraw, an open-source virtual whiteboard. Use this data with GitHub Copilot to practice PM workflows.

---

## Customer Feedback (Qualitative)

### Usability & UX

**FB-001** | NPS: 6 | Segment: Free User | Role: Product Designer
"The color picker is buried three clicks deep. Every time I want to change a shape's color, I lose my flow. I end up just using the defaults, which makes all my diagrams look the same."

**FB-002** | NPS: 7 | Segment: Team Plan | Role: Engineering Manager
"I love the hand-drawn aesthetic, but the text editing experience is painful. You can't select a word by double-clicking, there's no find-and-replace, and the font size selector is tiny. I end up writing text in a separate editor and pasting it in."

**FB-003** | NPS: 4 | Segment: Free User | Role: UX Researcher
"The zoom controls are unintuitive. I keep accidentally zooming when I'm trying to scroll, and there's no easy way to zoom to fit the entire canvas. I've watched three colleagues struggle with the same thing in user testing sessions."

**FB-004** | NPS: 8 | Segment: Team Plan | Role: Product Manager
"The toolbar is getting cluttered. There are so many shape options now that finding the right tool takes longer than drawing the shape. Would love customizable toolbars or favorites."

**FB-005** | NPS: 5 | Segment: Free User | Role: Software Engineer
"Copy-pasting between Excalidraw tabs doesn't work consistently. Sometimes it pastes the shapes, sometimes it pastes as an image, and sometimes it just doesn't paste at all. Very frustrating."

**FB-006** | NPS: 9 | Segment: Team Plan | Role: Design Lead
"I wish there was a way to lock elements in place. When I'm building a complex diagram, I keep accidentally moving background elements while trying to select foreground ones."

**FB-007** | NPS: 3 | Segment: Free User | Role: Student
"The eraser tool is basically useless. It only erases entire shapes instead of letting me erase parts of a freehand drawing. Every other whiteboard tool lets you do partial erases."

**FB-008** | NPS: 7 | Segment: Team Plan | Role: Technical Writer
"Arrow snapping is great when it works, but it frequently snaps to the wrong anchor point. I spend more time fighting the snapping behavior than it would take to just manually position arrows."

### Data Loss & Persistence

**FB-009** | NPS: 2 | Segment: Free User | Role: Engineering Manager
"I accidentally closed my browser tab and lost 45 minutes of diagramming work. There's no auto-save, no recovery, nothing. I had to redo the entire architecture diagram from memory."

**FB-010** | NPS: 4 | Segment: Team Plan | Role: Solutions Architect
"The local storage save is unreliable. I've had it silently fail at least three times in the past month. Each time I lost 20-30 minutes of work. There's no visual indicator that saving has failed."

**FB-011** | NPS: 6 | Segment: Free User | Role: Product Manager
"I accidentally hit Ctrl+Z one too many times and undid a huge chunk of work. There should be a confirmation for large undo operations, or at least a history panel where I can jump to specific states."

**FB-012** | NPS: 5 | Segment: Team Plan | Role: VP of Engineering
"We had an incident where a team member's browser crashed during a collaborative session and it corrupted the shared state. Everyone's changes from the last 10 minutes were lost. No conflict resolution, no backup, nothing."

**FB-013** | NPS: 3 | Segment: Free User | Role: Freelance Designer
"Export to PNG cuts off elements that are near the edge of the canvas. I've sent clients diagrams with missing labels because the export boundary doesn't match what I see on screen."

### Collaboration

**FB-014** | NPS: 5 | Segment: Team Plan | Role: Product Lead
"We use Excalidraw for sprint planning, but there's no way to add sticky notes or vote on ideas. We end up screenshotting the board and pasting it into Miro just to run a dot-vote."

**FB-015** | NPS: 6 | Segment: Team Plan | Role: Scrum Master
"Real-time collaboration is laggy with more than 4 people. We've had sessions with 8-10 people and it becomes unusable — cursors jumping, shapes flickering, and edits overwriting each other."

**FB-016** | NPS: 7 | Segment: Team Plan | Role: Engineering Manager
"There's no commenting or annotation feature. During design reviews, we have to use a separate tool (Slack, Google Docs) to leave feedback on specific parts of a diagram. It breaks the workflow completely."

**FB-017** | NPS: 4 | Segment: Team Plan | Role: Product Designer
"I can see other people's cursors but I can't see what they've selected or what they're currently editing. In a collaborative session, this leads to constant conflicts where two people edit the same element."

**FB-018** | NPS: 8 | Segment: Team Plan | Role: Director of Product
"We need permissions. Right now anyone with the link can edit everything. I want to be able to share a board as view-only, or let certain people edit only their section."

### Performance

**FB-019** | NPS: 5 | Segment: Free User | Role: Solutions Architect
"The app becomes extremely sluggish with more than ~200 elements on the canvas. I'm building enterprise architecture diagrams that easily hit 500+ elements. At that point, every action has a visible delay."

**FB-020** | NPS: 6 | Segment: Team Plan | Role: Software Engineer
"Scrolling performance degrades badly when there are many freehand drawings on the canvas. It feels like the renderer is recalculating every stroke on every frame."

**FB-021** | NPS: 4 | Segment: Free User | Role: Data Engineer
"Opening a complex shared board takes 8-12 seconds. Users see a blank canvas for several seconds before elements start rendering in. First-time visitors think the board is empty and leave."

### Feature Requests

**FB-022** | NPS: 8 | Segment: Team Plan | Role: Product Manager
"We desperately need a template library. Every sprint planning session, someone rebuilds the same kanban board layout from scratch. It's a waste of 10 minutes every two weeks."

**FB-023** | NPS: 7 | Segment: Free User | Role: UX Designer
"I want to create reusable component libraries — like a set of UI wireframe primitives I can drag onto the canvas. Right now I maintain a separate 'parts' file and copy-paste from it."

**FB-024** | NPS: 9 | Segment: Team Plan | Role: CTO
"Integration with our development tools would be a game-changer. Imagine embedding Excalidraw diagrams in GitHub issues or Notion pages that stay editable and in-sync."

**FB-025** | NPS: 6 | Segment: Free User | Role: Technical PM
"Dark mode. Please. I work late and the bright white canvas is blinding. Every other tool I use has dark mode — VS Code, Slack, Notion, even my terminal."

**FB-026** | NPS: 7 | Segment: Team Plan | Role: Design Systems Lead
"We need a way to define and apply consistent styles across elements — like a design token system. Our team diagrams look inconsistent because everyone picks slightly different colors and font sizes."

**FB-027** | NPS: 5 | Segment: Free User | Role: Product Manager
"Presentation mode would be amazing. I build my project roadmap in Excalidraw but then have to screenshot it into PowerPoint for stakeholder reviews. If I could present directly from Excalidraw, that'd save 30 minutes every week."

**FB-028** | NPS: 8 | Segment: Team Plan | Role: Engineering Manager
"Version history with visual diffs. When my team collaborates on architecture diagrams, I want to see what changed between yesterday and today without doing a manual comparison."

### Mobile & Cross-Platform

**FB-029** | NPS: 4 | Segment: Free User | Role: Product Designer
"The mobile experience is basically broken. Touch targets are too small, there's no gesture support for common actions, and the toolbar takes up half the screen. I've stopped even trying to use it on iPad."

**FB-030** | NPS: 6 | Segment: Team Plan | Role: Field Engineer
"I need offline support. I frequently work from planes and client sites with spotty WiFi. The app just shows a loading spinner when it can't reach the server."

**FB-031** | NPS: 5 | Segment: Free User | Role: Student
"The app doesn't work well with stylus input. There's no pressure sensitivity, palm rejection is nonexistent, and the freehand tool treats my Apple Pencil the same as a finger."

### Miscellaneous

**FB-032** | NPS: 7 | Segment: Team Plan | Role: Accessibility Lead
"Excalidraw has zero keyboard navigation support. I have a team member with RSI who relies on keyboard shortcuts, and they literally cannot use the tool. No tab ordering, no aria labels, no screen reader support."

**FB-033** | NPS: 6 | Segment: Free User | Role: Data Scientist
"I want to import data and auto-generate diagrams. Feed in a CSV of dependencies and get a dependency graph. Feed in a JSON schema and get an ER diagram. The manual drawing is the bottleneck."

**FB-034** | NPS: 8 | Segment: Team Plan | Role: VP of Product
"Search. I have a massive board with 50+ diagrams organized in sections. There's no way to search for text within the board. I spend minutes scrolling around trying to find the right section."

**FB-035** | NPS: 3 | Segment: Free User | Role: Project Manager
"The grid/alignment tools are inconsistent. Sometimes 'snap to grid' works, sometimes it doesn't. The distribute and align buttons occasionally produce wildly wrong results when elements are grouped."

---

## Product Analytics Data

### Feature Usage (Last 30 Days)

| Feature | Daily Active Users | Avg. Session Uses | % of Total Users |
|---------|-------------------|-------------------|-----------------|
| Rectangle Tool | 145,200 | 8.3 | 89% |
| Arrow Tool | 138,400 | 6.7 | 85% |
| Text Tool | 132,100 | 5.2 | 81% |
| Freehand Draw | 67,800 | 3.1 | 42% |
| Ellipse Tool | 54,300 | 2.4 | 33% |
| Diamond Tool | 31,200 | 1.8 | 19% |
| Line Tool | 28,900 | 2.1 | 18% |
| Image Insert | 24,600 | 1.4 | 15% |
| Color Picker | 98,700 | 4.6 | 61% |
| Export (PNG) | 43,200 | 1.2 | 27% |
| Export (SVG) | 12,400 | 1.1 | 8% |
| Undo (Ctrl+Z) | 156,300 | 14.2 | 96% |
| Copy/Paste | 112,500 | 7.8 | 69% |
| Collaboration (Live) | 34,800 | 1.0 | 21% |
| Library Panel | 18,200 | 2.3 | 11% |

### User Flow: Color Change Workflow

| Step | Action | Avg. Time | Drop-off Rate |
|------|--------|-----------|---------------|
| 1 | Select element | 1.2s | 0% |
| 2 | Open properties panel | 2.8s | 12% |
| 3 | Click color swatch | 1.4s | 8% |
| 4 | Browse/select color | 4.1s | 15% |
| 5 | Confirm and close | 0.8s | 3% |
| **Total** | | **10.3s** | **38% abandon** |

### Session Metrics

| Metric | Value |
|--------|-------|
| Avg. session duration | 18.4 min |
| Median session duration | 11.2 min |
| Avg. elements per canvas | 47.3 |
| Median elements per canvas | 28 |
| P95 elements per canvas | 312 |
| Sessions with >200 elements | 4.2% |
| Avg. undo actions per session | 14.2 |
| Sessions with data loss reports | 0.3% |
| Canvas load time (P50) | 1.8s |
| Canvas load time (P95) | 8.4s |
| Canvas load time (P99) | 14.2s |

### Collaboration Metrics

| Metric | Value |
|--------|-------|
| % sessions that are collaborative | 21% |
| Avg. participants per collab session | 3.2 |
| Median participants per collab session | 2 |
| Sessions with 5+ participants | 6.8% |
| Avg. edit conflicts per collab session | 2.4 |
| Conflict resolution success rate | 78% |
| Avg. latency (2 participants) | 120ms |
| Avg. latency (5+ participants) | 890ms |
| Collab sessions with reported lag | 34% |

### Retention & Satisfaction

| Cohort | Day 1 | Day 7 | Day 30 | Day 90 |
|--------|-------|-------|--------|--------|
| Free Users | 100% | 42% | 18% | 8% |
| Team Plan | 100% | 78% | 62% | 51% |

| NPS Segment | Score | % of Responses |
|-------------|-------|---------------|
| Promoters (9-10) | — | 31% |
| Passives (7-8) | — | 38% |
| Detractors (0-6) | — | 31% |
| **Overall NPS** | **+0** | — |

### Error & Performance Logs (Last 7 Days)

| Error Type | Count | Affected Users |
|------------|-------|---------------|
| LocalStorage write failure | 1,247 | 892 |
| Canvas render timeout (>5s) | 3,891 | 2,104 |
| WebSocket disconnect (collab) | 8,432 | 3,217 |
| Export boundary miscalculation | 612 | 489 |
| Undo stack corruption | 89 | 73 |
| Touch event handler crash (mobile) | 2,341 | 1,876 |
| Memory exceeded (>500 elements) | 445 | 312 |

### Support Tickets by Category (Last 30 Days)

| Category | Tickets | % of Total | Avg. Resolution Time |
|----------|---------|-----------|---------------------|
| Data loss / recovery | 342 | 22% | 4.2 hrs |
| Performance / lag | 289 | 19% | 2.1 hrs |
| Collaboration issues | 234 | 15% | 3.8 hrs |
| Export problems | 178 | 12% | 1.4 hrs |
| UX / usability | 156 | 10% | 1.1 hrs |
| Mobile bugs | 143 | 9% | 5.6 hrs |
| Feature requests | 112 | 7% | N/A |
| Other | 87 | 6% | 2.3 hrs |

---

*This dataset is synthetic and created for workshop purposes. All names, companies, and metrics are fictional.*
