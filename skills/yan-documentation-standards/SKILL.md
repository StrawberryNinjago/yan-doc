---
name: yan-documentation-standards
description: Use when drafting, revising or reviewing presentations, requirements, design documents, procedures or handoffs for Yan, or applying Yan’s agreed documentation style to team work.
---

# Yan’s Agreed Documentation Style and Standards

## TL;DR

Produce reader-first, concrete drafts that reuse agreed decisions. Use these defaults alongside task-specific skills; current user directions and project requirements take precedence.

## Establish the starting point

1. Read the supplied sources, project context and approved examples. For a slide or section within a larger artifact, read the surrounding material too. Identify the audience, intended end outcome, decision or action, and delivery scope. Ask only about missing information that would materially change the result.
2. **Narrative first:** establish what preceding material has explained, the single takeaway this unit must deliver, and the next question it prepares. Choose the supporting logic—cause and consequence, comparison or delivery steps—before choosing headings, wording or layout. Keep this working plan internal unless the user asks for it.
3. Reuse existing material and approved structures. Give adjacent units distinct jobs: a rationale explains **why support addresses friction**; a workflow shows **where it fits**. Keep both when those questions need separate answers; merge duplicated explanations while preserving the problem-to-support connection. Preserve each unit’s role—current-state baseline, proposed approach or results—when moving it. When the planning unit or format is unsettled, show one representative item before expanding the full document, backlog or slide set.
4. For discussion-only requests, propose the sequence and content without editing files. After approval, re-read the current artifact, preserve intervening user edits and implement the agreed direction without reopening settled choices.
5. Produce a complete baseline for the agreed unit, then run the first-reader check below before presenting it. Resolve narrative and meaning before polishing layout; preserve accepted content during layout-only changes.

## Frame the content

- **Outcome to delivery:** start with the intended end outcome, then explain concrete deliverables: what will exist, who uses it and why it helps. Keep unspecified audiences and scope explicitly open rather than adding them to an agreed delivery. Distinguish outcomes, enabling practices and outputs; map shared expectations to project-specific deliveries. A goal/delivery overview describes the end state; report current progress separately.
- **Problem before solution:** distinguish the underlying knowledge or process gap from an example incident. Use the user’s clarification; do not infer a root cause from a symptom alone.
- **Connected explanation:** keep context, action, cause and consequence together. In a process diagram, attach effort or delay to the work that incurs it. Explain why a dependency persists rather than scattering the same problem across separate gap, friction and impact sections.
- **Meaning before terminology:** explain what an unfamiliar component is and what it does in plain language. Put an acronym's full name beside the acronym, not in its role description. Distinguish a tool from its configuration file, guidance from enforcement, and a reusable capability from project-specific knowledge. Use familiar analogies with accurate counterparts.
- **Activity versus skill:** name workflow stages for the work, such as **Requirements refinement**, and name supporting skills explicitly, such as `/grilling`. In Yan’s documents, **grilling** refers only to that skill or a named variant, not to questioning or refinement in general. Preserve the actual skill names and distinguish their roles from the activity they support. Apply this distinction across headings, diagrams, captions, accessibility descriptions and speaker notes.
- **Concrete actions:** name the action, artifact and completion check. Replace “improve alignment” with scoped work items and a checked handoff.
- **Concrete examples:** show what the reader supplies, receives or can do. Explain the useful contents of an output, not just its title: for example, a design describes interfaces, data flow and open decisions. Use general examples to introduce reusable concepts; use project details when explaining their application.
- **Meaning before format:** choose labels that match the subject: inputs and outputs for a transformation, independent actions for a connector, representative requirements or patterns for a standards profile. Group peers by meaning: tool names, usage conditions, actions and outputs belong to distinct groups. Consistency means equal clarity, not identical rows or list markers for unlike content. Describe only the execution or enforcement the source supports.
- **Established practices:** explain gaps in inputs, coverage or consistency rather than presenting a new tool as a replacement for sound engineering practice.
- **Human ownership:** name who makes decisions, verifies results and authorizes progression. When this is the central message, make it a prominent takeaway rather than a footnote. Tools support those responsibilities; a workflow arrow does not establish automatic execution or approval.
- **Modest positioning:** attribute existing goals and frameworks correctly. Name personal deliveries directly, with accurate scope and status, rather than inflated contribution claims. For internal sharing, distinguish team adoption from lessons useful to other teams.
- **Evidence:** distinguish observations, hypotheses, plans and results; label estimates. When reporting progress, use short factual status labels such as “In progress” or “Untested.” When no measured benefit is claimed, keep measurement caveats in notes rather than adding defensive disclaimers. Keep decision-critical limitations visible.

## Choose the form

| Artifact | Starting pattern |
| --- | --- |
| Comparison | Use the fewest columns that answer distinct reader questions. Combine definition and benefit into a role when they overlap. For workflow reviews, use **Step / Friction or blocker / Framework support**. Each support cell pairs the tool or artifact with one concise explanation of how it addresses that row’s friction. |
| Definitions | For comparing components, use **Component / Role / Concrete example**: name and expanded acronym; what it is and does; a recognizable use or supplied standards. For explaining one concept, a short section may be clearer. |
| Design or requirements | Purpose, scope, decisions, constraints and observable acceptance criteria. Preserve necessary technical depth and unresolved decisions. |
| Procedure | Actor, prerequisites, action and expected result; include source-backed failure handling. |
| Handoff | Scope, acceptance criteria, constraints and unresolved questions. Include **Before coding**: the receiving agent confirms planned changes, exclusions and verification. |
| Roadmap | Name the delivery steps and concrete outputs; put tools in supporting labels. Match the following detail sections to those steps. Separate the intended approach from current practice and implementation status; dates and milestones belong to a progress-reporting purpose. |
| Presentation | One clear question per slide, a direct title and a concise takeaway. Prefer short, parallel bullets and fragments. For a main point plus explanation, use a bold headline on its own line with supporting bullets below. Label outputs explicitly and group their contents underneath. Separate competing definitions, rationale and flow; reuse the project's visual conventions. |
| Applied workflow step | **Input → engineer-led work with relevant tools → concrete output → review and handoff.** Explain how the support addresses a specific friction, not merely which command ran. Several skills may support one activity; their listing does not imply a mandatory sequence. Keep useful existing practices visible, and distinguish observed behavior from proposed refinements. |
| Section transition | Two visible text elements: **title = next topic; subtitle = concrete project or case**. Put evaluation criteria on an evaluation slide or alongside the relevant examples and evidence; the divider’s job is orientation. |

**Slide-table cells:** role and example cells are bullet lists, with one point per visual line (`<br>•` in Markdown tables; `<ul>/<li>` in HTML). Put input and output labels on separate lines, with each output's contents underneath. For a standards profile, each example bullet starts with a requirement, pattern or standards category named in the source.

### Workflow and capability diagrams

- **Stage mapping:** use a diagram when the question is how pieces connect or where tools are used. Each stage has an action heading and one list of supplied capability names. Skills and integrations share that list; category colors distinguish them. Review/approval stages retain their roles and required checks instead. For a capability map, put tool actions and usage qualifiers in speaker notes or a separate definition/example, rather than adding explanatory rows beneath names. An artifact-handoff diagram instead labels the outputs passed between stages.
- **Shared guidance:** put cross-cutting standards beside the workflow heading or in a clearly shared support layer. Use the existing header when another strip would repeat the component definition or resemble an extra delivery step. Preserve the distinction between setup, per-task tools and standards governing the work.
- **Shared inputs:** for context-dependent workflows, show the source, reviewed context artifact and supported stages in the main diagram. Use a shared input layer above or beside the delivery path, with connectors or explicit stage mapping. This makes context preparation and reuse visible without turning them into another delivery stage.
- **Color semantics:** reuse the established category palette across in-scope definitions, tables, diagrams and examples. Apply matching colors to category names and their named instances; keep actions, outputs and usage qualifiers neutral. Preserve approved panel fills and emphasize capability labels with contrast and weight. Text must identify the role without relying on color alone.
- **Extensibility:** use `…` only for genuinely open-ended capability/example lists, once after the last actual entry of the whole list, including mixed capability categories. Review responsibilities, required checks and approval gates do not inherit ellipses for visual symmetry. For example, **Analyze:** `/inspect`, `/compare`, `…`; **Approve:** reviewer sign-off. Different list lengths need different marker positions, not a forced common bottom row.

### Visual hierarchy and fit

For designed pages and slides, keep a clear font-size hierarchy: **title > goal/takeaway > body/table text > supporting notes**. In action examples, put supporting prerequisites in an italic note immediately below the actions, smaller than the action text when styling is available. Put background context that distracts from the main question in a footer or speaker notes. Decision-critical limitations remain visible. Check the rendered hierarchy and fit, not only declared sizes.

Use approved neighboring slides as the typography baseline: carry forward body, stage-heading and note sizes rather than enlarging a new diagram to fill spare space. For “a bit smaller,” make a modest reduction to the requested content roles, preserving the established title size, colors and layout. For height or crowding problems, reduce excess padding, box heights and gaps before shrinking text; reposition connectors with their nodes. Preserve space for labels and navigation controls.

## Review before presenting

Before showing a draft, revise it until these checks pass; keep the checklist internal unless asked:

- Does this unit follow logically from the preceding material, deliver one takeaway and prepare the next question? Can a first-time reader understand its examples without the prior conversation?
- Can the reader connect each deliverable to its intended outcome and each improvement to the friction it addresses?
- Are ownership, scope, decisions and evidence preserved, with no invented requirements?
- Are bullets concise while retaining enough meaning to understand what the reader provides, receives or can do?
- Does each visible element advance that takeaway in a logical sequence? Have duplicate overviews, repeated labels, generic benefits and unnecessary columns been removed or moved to where they belong?
- Do grouping, placement, arrows, colors and list markers express the intended roles and relationships? Inspect each repeated column by meaning, including whether a list is an extensible example or a review/approval requirement.
- Has the rendered artifact been checked against approved neighboring slides for typography and visual weight, as well as wrapping, clipping, connector placement and navigation overlap? Fitting within the viewport is not enough.

Semantic review and rendered layout verification are separate completion gates; both must pass. A slide fitting on screen does not prove that its grouping or visual cues make sense.

## Retain learning

When Yan approves a general preference, incorporate it into this standard. Keep business facts, project decisions, theme colors and one-off edits in project context. Use an approved example of the relevant artifact type as a reference, not a template for every task. A future session must load the skill; do not promise persistence merely because a prior chat contained the preference.
