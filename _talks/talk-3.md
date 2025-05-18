---
title: "Learning from Simulated Patient Trajectories: A Sequential Decision-Making Agent for Heart Transplantation"
collection: talks
type: "Invited Talk"
permalink: /talks/talk-3
venue: "INFORMS Annual Meeting 2025"
date: 2025-10-26
location: "Atlanta, GA, USA"
---

Decisions about managing patients on the heart transplant waitlist are currently made by committees of doctors who consider multiple factors, but the process remains largely ad-hoc. With the growing volume of longitudinal patient, donor, and organ data collected by the United Network for Organ Sharing (UNOS) since 2018, there is increasing interest in analytical approaches to support clinical decision-making at the time of organ availability.

We introduce an agentic decision-making framework based on model-based reinforcement learning (MBRL) for optimizing long-horizon, sequential decisions in heart transplantation. Our approach leverages time-to-event models for waitlist mortality, transplant mortality, and donor offer arrival to simulate full patient trajectories. These predictive models serve as environment dynamics, enabling the agent to learn policies that make timely, personalized decisions to maximize patient outcomes. 

By capturing temporal dependencies and clinical trade-offs across the transplant process, our framework supports decision-making beyond static risk models or myopic heuristics. The learned policy identifies key predictors aligned with known clinical risk factors while surfacing novel insights, offering a foundation for urgency assessment and policy refinement in heart transplant care. The proposed agent supports realistic counterfactual reasoning, allowing us to evaluate what might happen under alternative action sequences for individual patients. It also captures the temporal dependencies, uncertainty, and trade-offs inherent in the transplant process—such as urgency, donor-recipient matching, and long-term outcomes—through full patient trajectory simulation. This work illustrates the potential of agentic AI systems to support transparent, consistent, and patient-centered clinical decision-making in high-stakes settings.
