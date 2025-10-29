🎯 The Goal: Full-Stack Alignment (FSA)
The central idea is Full-Stack Alignment (FSA): the robust and simultaneous alignment of AI systems and the institutions that use them (companies, markets, governments) with what people genuinely value.


🚫 The Problem: "Thin" Models Are Not Enough
Current methods for modeling values are "thin," "lossy," and distort human values as they move up the institutional stack. For example, a user's desire for "meaningful connection" becomes "engagement metrics" for an app, which becomes "daily active users" for the company.



Preferentist Modeling of Value (PMV):

This includes utility functions and preference rankings (like those used in RLHF).


Flaws: It's too "thin." It cannot distinguish an authentic value (like community) from a fleeting want, an addiction, or a manipulated choice. It also struggles to model collective goods or the why (the justification) behind a choice.





Values-as-Text (VAT):

This involves using unstructured natural language, like simple prompts or "constitutions" (e.g., "be helpful").



Flaws: This approach is vulnerable to interpretive drift. It can be easily manipulated and is susceptible to capturing polarized ideological markers or political slogans (e.g., "Family Values," "Abolish the Police") instead of the deeper, nuanced values those slogans might represent for different people.


💡 The Solution: "Thick" Models of Value (TMV)
The paper proposes Thick Models of Value (TMV), which are explicit, structured approaches to modeling human norms and values. This structure acts as a "grammar" for values, allowing them to be inspected, deliberated over, and preserved as they move across the full stack.




Three Critical Needs (Desiderata)
To be effective, TMVs must provide:


Robustness: The ability to distinguish real, enduring values from fleeting preferences, addictions, or manipulation.



Collective Focus: The ability to model shared norms, social roles, and public goods (like community trust).



Generalization: The ability to support principled normative reasoning, so values can be applied consistently in new situations.

🛠️ Case Study: Moral Graph Elicitation (MGE)
MGE is the paper's primary example of a TMV approach. It's a process explicitly designed to filter out the simple preferences of PMV and the shallow slogans of VAT.



How it Works

Elicit Values: It represents values not as final choices, but as "attentional policies"—the specific "criteria, used in choice, which are not merely instrumental".





Prompt Reflection: It uses conversational AI to help a person reflect on a situation and identify these deeper criteria.

Example: A user asks about abortion.


VAT/PMV would capture divisive slogans ("pro-life," "pro-choice").



MGE prompts reflection, filtering out slogans to find the deeper attentional policies, such as: "How does this choice connect to my personal faith and conscience?" or "Are there opportunities to consult trusted mentors?".


The Moral Graph as a Structured Model (Ontology)
The MGE process builds a "Moral Graph' of context-sensitive value comparisons". This graph is a structured model (an "ontology") of collective wisdom.

Connection to Semantic Web: While the paper doesn't use terms like "RDF" or "ontology," the entire argument mirrors the philosophy of the semantic web. It argues that unstructured "Values-as-Text" (VAT) is unreliable for machine reasoning, and we need structured approaches (TMV) to enable "principled normative reasoning".




Nodes (The Concepts): The nodes are the "Values" or "Attentional Policies" (e.g., "Religious Adherence," "Personal Growth").




Edges (The Relationships): The edges are directed and represent a relationship of "wisdom" or "improvement". An edge is added when users collectively judge that a fictional person "got wiser" by transitioning from one value to another in that specific context.





Key Insights on this Approach
It's an Ontology of Improvement, Not Just State: This is not a static map of what people value. It's a dynamic model of what they consider normative progress. It captures how values "evolve" through "reflection and deliberation".




It's an Active Filter Against Polarization: The MGE process is an "anti-VAT" mechanism. By forcing reflection (moving from slogan to policy) and reframing the vote (judging a fictional person's reasoning), it filters out "ideological markers". This is why 89% of participants found the process fair, even if their personal value didn't "win".






It's the "Common Language" for the Full Stack: This structured graph is the key to preventing "value distortion". The exact same "structured representation of collective values" can be used to guide an individual AI agent's response and, at the institutional level, to power the "AI-powered deliberative agents" for democratic governance.


🚀 Five Key Applications of TMV
This structured TMV approach provides the common language needed to align both individual agents and broad institutions.

AI Value-Stewardship Agents:

An AI assistant told "I want to be healthy" would use TMV to help the user clarify their "thick" value (e.g., "vitality and joy in physical activity") from a "thin" proxy (e.g., "biomarker maximization" or steps taken). This helps users resist "value collapse".


Normatively Competent Agents:

An AI moderator can understand the social context and norms of a community (e.g., minority users reclaiming slurs) instead of just rigidly applying a "thin" VAT rule ("ban all slurs"). This can be achieved with tools like contractualist reasoning.


Win-Win AI Negotiation:

In a PMV world, agents just maximize their own utility. With TMV, agents can make credible "value-based commitments". Because these values are structured with justifications, they foster trust and cooperation.


Meaning-Preserving AI Economies (Macro-Alignment):

Problem: The "intelligence curse." As AI workers become super-productive, the economy could detach from human flourishing.


TMV Solution: Use AI-enabled "market intermediaries" to negotiate "outcome-based contracts".


Example: Instead of a fitness provider being paid based on a "thin" proxy (like monthly membership fees), they would be paid based on a "thick" outcome (like their members' measured sustained vitality). This realigns the market to reward genuine human flourishing.

Democratic Regulation at AI Speed:


Problem: AI operates too fast for human-led democratic regulation.


TMV Solution: Create AI-powered deliberative agents trained on the collective "moral graphs". These agents could extrapolate legitimate, value-aligned responses to new threats at machine speed, with their reasoning being auditable and grounded in the population's endorsed values.


🔑 Conclusion: From "Thin" Proxies to "Thick" Values
The core failure of old models is that they are too "thin" and "lossy". TMV offers a path toward institutional renewal by providing an explicit, structured representation of norms and values. This "grammar of values" is the key to ensuring that our technology and institutions co-evolve to enhance, not undermine, human flourishing and agency.




A Practical Takeaway: Think about a metric you focus on, like daily steps. Is that metric a thin proxy (just an easily measured number) or part of a thick value (like "vitality" or "joy in movement")? The paper argues our AI and institutions must be able to understand and optimize for the latter.