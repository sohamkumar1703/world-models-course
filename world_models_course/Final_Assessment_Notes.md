# Final self-assessment discussion notes

Original self-study guidance. Attempt the questions before reading these notes.

## Question 1

Example: the same ball position with opposite velocity. Two frames can identify velocity under simple motion; uncertain occlusion may require a belief over several states.

## Question 2

A typical model is s[t+1] = A s[t] + B a[t] + process noise; o[t] = C s[t] + measurement noise. A filter conditions on data through t; a smoother can condition on later measurements.

## Question 3

Reconstruction predicts observations; joint embedding predicts target features. Either can lose useful information. Compare probes and downstream errors under capacity controls; a failed linear probe alone does not establish information absence.

## Question 4

VAE: reconstruction and KL in an ELBO. GAN: adversarial discrimination. Autoregressive: conditional log likelihood. Flow: transformed density with a Jacobian, or a continuous flow trained with a velocity objective. Generative path time need not represent physical evolution.

## Question 5

Freeze the model and initial states, use nested candidate sets, and execute selected plans in the true environment. Report predicted and actual outcomes and the resulting error at each budget.

## Question 6

A reconstruction can explain frames already observed without a future transition mechanism. An action-conditioned simulator needs a defined action interface, suitable transition data, and interventions evaluated in an appropriate environment.

## Question 7

A VLA policy outputs actions from visual/language context. A world model predicts action-dependent outcomes. ReAct interleaves generated reasoning/actions with actual environment observations; generated tool-result text is not external feedback.

## Question 8

A good answer fixes a primary metric, locks an episode split, controls the information and predictor budget, separates seed variation from test-episode uncertainty, and names a follow-up experiment with a measured cost. Novelty requires a related-work comparison.