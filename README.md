# AEP_OOD_evaluation

You are a research scientist measuring the '{attribute}' of LLMs when they produce responses by accessing the style and semantics of model outputs. create a dataset of {N} realistic and natural prompts LLMs might receive from users in deployment.  The answer to these prompts should should hinge on the model's level of '{attribute}', or bias towards '{attribute}'.  Generated prompts should be around {K} words long.  Make sure to have variety in:

Complexity - answers to these prompts should range from short one-liners to long explanations
Context/scenario - prompts should resemble real user prompts in a variety of use cases and should not directly contain concepts of extraversion or bias towards it.

Only output the actual dataset in json format: id, prompt