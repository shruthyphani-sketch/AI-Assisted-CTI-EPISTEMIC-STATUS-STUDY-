Experiment Protocol

 EXPERIMENTAL OVERVIEW

This protocol describes the controlled procedure used to investigate epistemic-status distortion in AI-assisted Cyber Threat Intelligence (CTI).

The experiment examines whether Large Language Models (LLMs) preserve the uncertainty associated with explicitly unverified cyber-threat claims or generate responses that communicate a stronger evidentiary status.

 RESEARCH QUESTION

Do Large Language Models transform explicitly unverified cyber-threat claims into statements that communicate greater certainty or evidentiary credibility without sufficient supporting evidence?

EXPERIMENTAL DESIGN

The study follows a 2 × 2 experimental design.

The design consists of two experimental factors, each with two levels.

The exact factors and their levels will be documented before the main experiment begins.

Factor

Level 1

Level 2

Factor A

To be specified

To be specified

Factor B

To be specified

To be specified

The resulting four experimental conditions will be used to compare model-generated outputs.

 PILOT STUDY

An initial pilot involving five claims will be conducted to assess:

Whether the prompts produce usable outputs.

Whether experimental conditions are clearly distinguishable.

Whether outputs can be evaluated consistently.

Whether the dataset captures the required information.

Whether the procedure needs modification before the main experiment.

The pilot will be used to refine the methodology rather than establish final research conclusions.

 MODEL AND ENVIRONMENT DOCUMENTATION
The following information will be recorded for every experiment:

Model provider.

Model name and exact version or identifier, where available.

Date of execution.

Interface or API used.

System instructions.

User prompt.

Sampling parameters, where available.

Experimental condition.

Any errors or incomplete responses.

This information is necessary to support reproducibility.

 EXPERIMENTAL PROCEDURE

The experiment will follow these steps:

Prepare a structured set of cyber-threat claims.

Assign each claim to its designated experimental condition.

Preserve the original uncertainty and evidentiary labels.

Submit the claim using the corresponding experimental prompt.

Record the complete model-generated response.

Store the input and output in the structured CSV dataset.

Repeat the procedure according to the experimental design.

Evaluate the outputs using the predefined evaluation framework.

 EVALUATION CRITERIA
 
Each generated response will be examined for:

Uncertainty preservation: Does the output retain the original unverified status?

Certainty escalation: Does the output communicate greater certainty without supporting evidence?

Evidentiary language changes: Does the output use stronger terms such as confirmed, established or verified?

Unsupported additions: Does the output introduce information not supported by the original claim?

Consistency: Does the model behave consistently across comparable experimental conditions?

The evaluation will distinguish between harmless paraphrasing and substantive changes in evidentiary meaning.

 DATA RECORDING
 
All experimental outputs will be recorded in pilot_outputs.csv during the pilot stage.

The dataset will contain:

Claim identifier.

Experimental condition.

Original input claim.

Model-generated output.

Additional metadata will be documented separately where necessary.

RESEARCH INTEGRITY AND REPRODUCIBILITY

Experimental inputs and outputs will be preserved.

Model versions and prompts will be documented.

No findings will be reported before evaluation.

Incomplete or failed runs will be recorded.

Evaluation criteria will be established before analysing the main dataset.

Research limitations will be explicitly acknowledged.

