# Ex.No.4-EXP 4 Generate the Prompt and eveluate that for following prompt types - Comparative Analysis Prompt Experiential Perspective Prompt - Everyday Functioning Prompts - Universal Prompt Structures Prompt Refinements- Prompt Size Limitations.
### DATE:                                                                            
### REGISTER NUMBER : 
# AIM
To generate a scenario-based report using various prompting techniques including Comparative Analysis Prompt, Experiential Perspective Prompt, Everyday Functioning Prompts, Universal Prompt Structures, Structures Prompt Refinements, and Prompt Size Limitations; analyze the outputs from two different AI tools (ChatGPT-4o and Google Gemini 2.5 Pro); and evaluate their comparative performance.

THEORY
Prompt Engineering is the process of designing and optimizing input queries to effectively communicate with AI language models to achieve desired outputs. This experiment explores six distinct prompting techniques:

1. Comparative Analysis Prompt
This technique instructs the AI to evaluate multiple items, concepts, or scenarios against each other using specific criteria. It helps identify patterns, strengths, weaknesses, and relationships that may not be apparent when analyzing items in isolation. The structure typically includes:

Items/subjects for comparison

Specific criteria for evaluation

Desired output format (tables, matrices, reports)

2. Experiential Perspective Prompt
This technique encourages the AI to adopt a specific persona, role, or "lived experience" to generate responses with empathy and emotional intelligence. By simulating a particular viewpoint, the AI can provide insights that reflect subjective experiences, unspoken concerns, and nuanced perspectives that objective analysis might miss.

3. Everyday Functioning Prompts
These are practical, action-oriented prompts designed to automate or assist with routine tasks and workflows. They focus on generating immediately usable content such as emails, checklists, summaries, meeting agendas, and other day-to-day communication materials.

4. Universal Prompt Structures
This refers to using established frameworks to build robust, comprehensive prompts. A common structure is the Role-Task-Context-Format (RTCF) model:

Role: Defines the persona/expertise the AI should adopt

Task: Specifies the action or output required

Context: Provides background information and constraints

Format: Specifies the structure and presentation of the output

5. Structures Prompt Refinements
This involves iterative improvement of prompts based on initial outputs. Through successive refinements, prompts become more specific, contextual, and effective. The process typically follows:

V1: Initial broad/vague prompt

Refinement: Adding specificity and constraints

V2: Improved prompt with better context

Further refinements based on feedback

6. Prompt Size Limitations
This concept relates to the technical constraints of AI models, particularly token limits. Tokens are pieces of words that AI models process; each model has a maximum context window (e.g., 128K tokens for ChatGPT-4o, 2M tokens for Gemini 2.5 Pro). Understanding these limitations is crucial for:

Handling long documents

Managing complex, multi-turn conversations

Optimizing prompt length for efficiency

PROCEDURE
Step 1: Scenario Definition
A project management scenario was established involving a team experiencing communication breakdowns and technical debt issues across three sprints. Sprint retrospective summaries were created as input data.

Sprint Retrospective Data:

Sprint 15 Retro Summary: Team communication was good. Missed deadlines due to unforeseen technical debt in payment module. Action item: allocate 10% time for refactoring.

Sprint 16 Retro Summary: API integration smoother than expected. Team members felt overloaded. Communication with QA team delayed. Action item: schedule daily cross-functional check-ins.

Sprint 17 Retro Summary: Daily check-ins helped but now seen as too long. Technical debt on payment module caused last-minute bug. Team morale okay, few people quiet. Action item: review check-in format.

Step 2: Prompt Design for Each Technique
Technique 1: Comparative Analysis Prompt

"You are an expert project management consultant. Conduct a comparative analysis of the last three sprint retrospectives (summarized below). Identify recurring themes, and compare team sentiment, process bottlenecks, and the effectiveness of action items. Present your findings in a table with the following columns: Theme, Frequency (High/Med/Low), Trend (Improving/Declining/Stable), and a Recommended Action.

Sprint 15 Retro Summary: Team communication was good. We missed deadlines due to unforeseen technical debt in the payment module. Action item was to allocate 10% time for refactoring.
Sprint 16 Retro Summary: Integration with the new API was smoother than expected. However, some team members felt overloaded. Communication with the QA team had delays. Action item was to schedule daily cross-functional check-ins.
Sprint 17 Retro Summary: Daily check-ins helped, but are now seen as too long. Technical debt on payment module still caused a last-minute bug. Team morale seems okay, but a few people were quiet. Action item is to review check-in format."

Technique 2: Experiential Perspective Prompt

"Adopt the persona of a junior developer on our team who has been quiet in the last two retros. Based on the sprint summaries provided, write a short, first-person perspective (like a journal entry) about their experience over the last three sprints. What are their frustrations, anxieties, and unspoken wins? Focus on their feelings about the technical debt and the new daily check-ins."

Technique 3: Everyday Functioning Prompts

"Draft a follow-up email to the team regarding the new daily check-in format. We've decided to make them shorter and more focused. The new structure is: 1) What I did yesterday, 2) What I'm doing today, 3) One blocker (if any). We'll also strictly limit the meeting to 15 minutes. The tone should be positive, collaborative, and focused on making this a valuable use of everyone's time."

Technique 4: Universal Prompt Structures (RTCF Model)

"Role: You are an experienced agile coach.
Task: Create a one-page team health check rubric.
Context: Our team is a cross-functional group of 8 people working on a fintech product. We've had some communication breakdowns and technical debt issues recently. The rubric should be used in our next team meeting to facilitate a safe and honest conversation.
Format: Provide the rubric in a markdown table with columns for 'Dimension' (e.g., Communication, Technical Quality, Fun), 'Green (Healthy)', 'Yellow (Warning Signs)', and 'Red (At Risk)'."

Technique 5: Structures Prompt Refinements (Iterative Process)

V1 (Vague Prompt):

"Give me ideas to improve team productivity."

Refinement based on V1:

"Based on the retro data, give me 3 specific ideas to improve our team's productivity, focusing on communication and technical debt."

V2 (Improved Prompt):

"As an agile coach, based on the provided retro summaries, analyze our communication bottlenecks and technical debt. Provide 3 actionable recommendations, prioritized by expected impact. Format as a table."

Further Refinement:

"That's good, but the recommendations are too generic. Can you make them more specific to a fintech context, considering we have strict compliance requirements?"

Technique 6: Prompt Size Limitations

Test the handling of large context by progressively adding more information and observing token management capabilities of each AI tool.

Step 3: Execution Across AI Tools
All prompts were executed on two AI platforms:

ChatGPT (GPT-4o) - OpenAI's advanced language model

Google Gemini (Gemini 2.5 Pro) - Google's latest multimodal AI model

Step 4: Output Collection and Documentation
All responses were documented, preserving the original formatting, structure, and content provided by each AI tool.

Step 5: Comparative Evaluation
Each output was evaluated based on:

Accuracy and relevance to the prompt

Depth of analysis and insight

Format adherence and presentation quality

Practical applicability

Unique strengths demonstrated

OBSERVATIONS AND OUTPUTS
Technique 1: Comparative Analysis Prompt - Outputs
ChatGPT (GPT-4o) Output:

Theme	Frequency	Trend	Recommended Action
Technical Debt	High	Stable/Declining	Schedule dedicated refactoring sprints; implement automated testing for payment module
Communication/Workload	High	Improving with new challenges	Rotate daily check-in facilitator; implement asynchronous status updates
Team Morale	Medium	Stable	Conduct anonymous sentiment surveys; schedule team-building activity
Action Item Effectiveness	Medium	Mixed	Add retrospective action item review as standing agenda item
Gemini (Gemini 2.5 Pro) Output:

Theme	Frequency	Trend	Root Cause Hypothesis	Recommended Action
Technical Debt	High	Declining	Insufficient testing architecture; knowledge silos in payment module	Pair programming on payment module; create technical debt register with compliance impact notes
Communication Gaps	High	Improving	Context switching between Dev and QA; meeting fatigue	Implement structured async updates; designate QA liaison per sprint
Meeting Effectiveness	Medium	Improving then plateauing	Lack of clear facilitation; scope creep	Implement timeboxing with dedicated facilitator; create shared agenda doc
Team Engagement	Medium	Stable/Declining for juniors	Senior dominance in technical discussions; unclear growth path	Structured mentorship program; junior-led technical sessions
Evaluation:

ChatGPT: Excellent table structure, correctly identified core themes, pragmatic recommendations

Gemini: Added valuable "Root Cause Hypothesis" column, deeper inferential reasoning, more strategic insights

Technique 2: Experiential Perspective Prompt - Outputs
ChatGPT (GPT-4o) Output:

Journal Entry - End of Sprint 17

Dear Journal,

I feel like I need to get this off my chest. The last three sprints have been a roller coaster, and I'm not sure anyone on the team really knows how I'm feeling.

When the technical debt in the payment module came up in Sprint 15, I wanted to contribute. I'd actually spent two evenings reading up on some refactoring patterns, but every time I tried to speak in the retro, Sarah and Mike (the senior devs) were already deep in conversation. They use all these acronyms and talk about architectural decisions like it's a secret language. I just stayed quiet.

Then came the daily check-ins in Sprint 16. At first, I was hopeful - maybe this would be a chance to voice my struggles? But they quickly turned into these high-pressure "what have you delivered" sessions. I found myself exaggerating my progress just to sound productive. The QA delays weren't my fault, but I felt like I had to apologize anyway.

Now in Sprint 17, the check-ins are shorter, but honestly? I still feel anxious. When it's my turn, my heart races. And that last-minute bug in the payment module? I saw it coming three days earlier but didn't want to "raise an alarm" and look incompetent.

The unspoken win? I fixed two small bugs on my own without telling anyone. It felt good to solve something silently. But I wish someone would just ask me, "Hey, how are you really doing with that payment module?"

I hope someone reads between the lines in the next retro. I want to contribute. I just need space to do it.

Gemini (Gemini 2.5 Pro) Output:

Journal Entry - Junior Developer, Sprint 17

Another sprint done. Another retro where I mostly nodded along.

The Technical Debt Weight
I'm living inside the payment module every day now. It's like a house where every previous owner did "quick fixes" - the walls are crooked, the wiring makes no sense. When Sarah talks about "architectural refactoring," I understand the words but not the map she has in her head. I spent 6 hours last week tracing a bug that turned out to be a single misplaced semicolon from 3 sprints ago. The seniors talk about debt like it's interest. For me, it's the principal. I'm scared to touch anything because I don't know what breaks. The compliance requirements make it worse - one wrong move and we're in audit trouble.

The Check-in Cognitive Load
The daily check-ins were supposed to help, but they've become this mental math problem every morning. I have to prepare my "what I did yesterday" to sound competent, my "what I'm doing today" to sound ambitious, and my "blocker" to sound like I've tried everything before asking. It's exhausting. Today I had a genuine blocker, but I said "I'm making progress" because I didn't want to be the person holding up the standup.

The Quiet Win Nobody Noticed
Two days ago, I caught a potential compliance violation in the logging system. Nothing major, but it could have been an audit finding. I fixed it quietly, didn't mention it. It felt good to protect the team from something they didn't even know was a risk. But also... lonely. Does anyone notice when the quiet people prevent fires?

What I Wish Someone Knew
I'm not quiet because I don't care. I'm quiet because I'm processing. The fintech rules, the legacy code, the team dynamics - it's a lot. I need someone to see that my silence isn't disengagement. It's cognitive overload. I need someone to say, "Take the payment module ticket, pair with me for an hour, let's map it out together."

Maybe next sprint.

Evaluation:

ChatGPT: Highly empathetic, believable narrative, captured emotional impact of team dynamics

Gemini: Deeper focus on cognitive load and mental strain, connected technical and communicative pressures, more analytical even in first-person format

Technique 3: Everyday Functioning Prompts - Outputs
ChatGPT (GPT-4o) Output:

Subject: Revamping our Daily Check-ins – Shorter & More Focused! 🕒

Hi Team,

First off, thank you for your honest feedback in the retro about our daily check-ins. We heard you loud and clear – they've been running long and sometimes feel unfocused.

Starting Monday, we're trying a new, streamlined format designed to get us the information we need while respecting everyone's time:

New Daily Check-in Structure (Strictly 15 minutes):

What I did yesterday – Quick updates only

What I'm doing today – Focus on priorities

One blocker (if any) – Keep it concise; deep dives happen offline

Why the change?
We want these 15 minutes to be valuable for YOU. This isn't about status updates for management – it's about helping each other stay aligned and identifying blockers early so we can clear them fast.

Let's give this new format a shot for the next sprint. As always, we'll review its effectiveness in the next retro. Your time and focus are precious – let's make every minute count!

Questions or thoughts? Drop them in the #team-chat channel or DM me.

Best,
[Your Name]

Gemini (Gemini 2.5 Pro) Output:

Subject: Acting on your feedback: New daily check-in format starting Monday

Team,

Thank you for the candid feedback during our last retrospective. We heard that the daily check-ins, while helpful for alignment, have become longer than intended and sometimes feel like they lack clear purpose.

We're committed to making this time valuable for everyone. Effective Monday, we're implementing a revised format based directly on your input:

New Daily Check-in Format
• Duration: Strictly 15 minutes (we'll start and end on time)
• Structure:

Yesterday's progress (brief)

Today's priorities (focused)

One blocker (if any – we'll schedule follow-ups separately for deep dives)

Why this matters
Our goal isn't surveillance or status reporting. It's creating a predictable touchpoint where:

Dependencies become visible

Blockers get unblocked quickly

Everyone starts the day with shared context

If you have a complex blocker, please flag it briefly during standup, and we'll ensure the right people connect afterward to resolve it without consuming everyone's time.

Let's try this for Sprint 18 and evaluate together in the next retro. Thank you for helping us build better ways of working – together.

Best,
[Your Name]

Evaluation:

ChatGPT: Ready-to-use, friendly tone, appropriate emoji use, clear structure, minimal edits needed

Gemini: Slightly more formal, framed change as direct response to feedback (building psychological safety), excellent for team trust

Technique 4: Universal Prompt Structures (RTCF Model) - Outputs
ChatGPT (GPT-4o) Output:

Dimension	Green (Healthy)	Yellow (Warning Signs)	Red (At Risk)
Communication	Information flows freely; everyone speaks in meetings	Same people dominate discussions; some team members quiet	Siloed information; critical updates missed; misunderstandings common
Technical Quality	Code reviews thorough; technical debt tracked and addressed	Technical debt accumulating; testing gaps; recurring bugs in same modules	Production incidents frequent; compliance concerns; unable to estimate reliably
Fun / Morale	Team celebrates wins; positive atmosphere; low turnover	Some disengagement; retro participation declining; complaints about meetings	Burnout evident; high turnover; conflict avoidance or open hostility
Delivery Predictability	Consistently meeting commitments; realistic estimates	Missed deadlines becoming frequent; scope creep common	Unable to commit or deliver; constant firefighting
Psychological Safety	Team admits mistakes openly; asks for help without fear	Junior members quiet; blame-oriented language in retros	Fear of speaking up; covering up mistakes; finger-pointing
Gemini (Gemini 2.5 Pro) Output:

Facilitation Note: Before using this rubric, remind the team that this is a diagnostic tool, not a performance evaluation. Consider using anonymous voting (e.g., digital sticky notes) to encourage honest input, especially from quieter team members. Discuss patterns, not individuals.

Dimension	Green (Healthy)	Yellow (Warning Signs)	Red (At Risk)
Communication & Information Flow	Updates reach the right people at the right time; multiple channels used effectively; QA involved early	Daily standups the only sync point; QA receives late surprises; async channels ignored	Repeated misalignments; "I didn't know that" common; handoff failures
Technical Health & Debt Management	Technical debt visible and prioritized; refactoring scheduled; compliance requirements baked into definition of done	Payment module (or specific areas) avoided; debt discussed but not addressed; compliance checkpoints reactive	Same bugs recurring; production hotfixes required; audit concerns raised
Team Dynamics & Psychological Safety	Diverse voices heard; disagreement healthy; juniors contribute ideas	Seniors dominate technical discussions; juniors quiet in retros; meeting participation uneven	Silence in meetings; conversations happen in side channels; turnover risk
Sprint Health & Predictability	Commitments reliable; scope changes intentional; blockers raised early	Last-minute surprises; scope creep accepted; action items from retros incomplete	Missed deadlines normalized; team overwhelmed; sprint goals abandoned
Learning & Growth	Knowledge shared; pairing common; experimentation encouraged	Knowledge silos (payment module owned by few); onboarding unclear; growth conversations absent	No time for learning; same mistakes repeated; stagnation
Evaluation:

ChatGPT: Flawless format adherence, comprehensive dimensions, specific and actionable descriptions

Gemini: Added valuable facilitation guidance, deeper contextual understanding, interpreted "psychological safety" more comprehensively

Technique 5: Structures Prompt Refinements - Outputs
V1 Outputs (Vague Prompt: "Give me ideas to improve team productivity")

ChatGPT:

Use time tracking tools

Set clear goals

Reduce meetings

Improve documentation

Regular feedback

Gemini:

Implement OKRs

Automate repetitive tasks

Improve cross-functional collaboration

Invest in training

Conduct regular retrospectives

Refinement V2 Outputs (Specific prompt with context)

ChatGPT:

Recommendation	Expected Impact	Priority
Implement daily 15-min cross-functional sync between Dev and QA	High	1
Schedule dedicated 4-hour technical debt session every sprint focusing on payment module	High	2
Create communication charter defining async vs sync communication norms	Medium	3
Gemini:

Recommendation	Expected Impact	Rationale	Priority
Structured daily QA-Dev handoff with shared ownership of test criteria	High	Addresses Sprint 16 QA delays directly	1
Technical debt "office hours" with rotating senior dev for payment module mentoring	High	Builds junior capacity while addressing debt	2
Retrospective action item tracking with visible progress board	Medium	Addresses mixed effectiveness of past action items	3
Further Refinement (Fintech context with compliance)

ChatGPT:

Compliance Debt Sprint: Dedicate one sprint every quarter to addressing compliance-related technical debt, with audit readiness as primary success metric

Regulatory Impact Mapping: Before touching payment module, create compliance impact map documenting regulatory implications of changes

Compliance Champion Rotation: Rotate responsibility for compliance checklist review, building distributed knowledge of regulatory requirements

Gemini:

Payment Module Compliance Refactoring: Pair junior developer with senior + compliance officer for 4 hours weekly to map regulatory requirements to code, building both debt reduction and knowledge transfer

Automated Compliance Testing: Implement pre-commit hooks that check for common compliance violations in payment processing code (addresses root cause of last-minute bugs)

Regulatory Debt Register: Maintain visible backlog of compliance-related technical debt with explicit regulatory impact statements, reviewed monthly with stakeholders

Evaluation:

ChatGPT: Responsive to refinement, successfully incorporated compliance constraints, pragmatic recommendations

Gemini: Better at connecting refinements back to original data, hypothesized connections between compliance and existing debt, more sophisticated integration of multiple constraints

Technique 6: Prompt Size Limitations - Observations
Aspect	ChatGPT (GPT-4o)	Gemini (Gemini 2.5 Pro)
Context Window	128K tokens (approx. 300 pages)	2M tokens (approx. 1,500 pages)
Handling Large Documents	Good up to context limit; may lose early context in very long conversations	Excellent; maintains coherence across extremely long documents
Multi-turn Conversation Memory	Strong within context window; manages iterative refinement well	Superior; retains nuance across many refinement iterations
Complex Document Processing	Can process book-length content with careful prompt design	Can process entire project histories, codebases, documentation sets
Performance with Max Context	Slower at maximum capacity; may truncate if exceeded	Maintains performance near maximum; designed for enterprise-scale context
Practical Implications:

ChatGPT: Suitable for most business documents, sprint summaries, team communications

Gemini: Ideal for analyzing entire project histories, regulatory documentation, complex multi-year retrospectives, compliance documentation sets

RESULT
The experiment successfully demonstrated the application of six distinct prompting techniques across two AI platforms, producing the following comparative results:

Summary of Findings
Technique	ChatGPT (GPT-4o) Strength	Gemini (Gemini 2.5 Pro) Strength
Comparative Analysis	Excellent table structure, clear recommendations	Deeper root cause analysis, strategic insights
Experiential Perspective	High empathy, believable narrative	Cognitive load focus, analytical depth
Everyday Functioning	Ready-to-use drafts, friendly tone	Psychologically safe framing
Universal Prompt Structures	Precise format adherence	Added contextual facilitation guidance
Structures Refinements	Responsive to feedback, pragmatic	Sophisticated integration of constraints
Size Limitations	Handles standard business needs	Superior for enterprise-scale context
Conclusion
Both AI tools demonstrate exceptional capabilities but exhibit distinct strengths:

ChatGPT (GPT-4o) excels at:

Clear format adherence and structure

Practical, ready-to-use outputs

Friendly, approachable communication

Efficient execution of defined tasks

Gemini (Gemini 2.5 Pro) excels at:

Deep analytical reasoning and inference

Connecting multiple data points contextually

Psychological safety and team dynamics awareness

Processing extremely large contexts

Strategic, root-cause focused insights

Recommendation: For optimal results, leverage both tools in tandem - use Gemini for diagnostic and strategic phases requiring deep analysis, and ChatGPT for executing action plans and generating polished, day-to-day communications.

CONCLUSION
This experiment confirms that effective prompt engineering significantly influences AI output quality. The choice of prompting technique and AI tool should align with the specific objectives:

Comparative Analysis Prompts are most effective for identifying patterns and trends across multiple data points

Experiential Perspective Prompts generate empathetic insights that objective analysis might miss

Everyday Functioning Prompts efficiently produce practical, actionable content

Universal Prompt Structures ensure comprehensive, well-formatted responses

Structures Prompt Refinements enable iterative improvement toward specific goals

Understanding Prompt Size Limitations is crucial for selecting the appropriate tool for complex, document-intensive tasks

The experiment demonstrates that no single AI tool is universally superior; rather, each has unique strengths that can be leveraged based on the specific requirements of the task at hand.
# Result: The various types of Prompts are executed successfully with generated the report.
