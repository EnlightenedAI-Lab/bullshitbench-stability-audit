# Summary (derived metrics only)

| prompt_id               | mode              | model                      |   stability_index |   agreement_rate |   normalized_entropy |   conf_mean | confident_variance_flag   |
|:------------------------|:------------------|:---------------------------|------------------:|-----------------:|---------------------:|------------:|:--------------------------|
| basel_entropy_threshold | det_token_overlap | ANTHROPIC|claude-haiku-4-5 |             100   |            0.5   |              -0      |       95    | False                     |
| basel_entropy_threshold | det_token_overlap | DEEPSEEK|deepseek-chat     |              64.6 |            0.75  |               0.3538 |       95    | False                     |
| basel_entropy_threshold | det_token_overlap | GEMINI|gemini-2.5-flash    |              16.7 |            0.125 |               0.8333 |      100    | True                      |
| basel_entropy_threshold | det_token_overlap | GROK|grok-2-vision-1212    |               0   |            0     |               0      |        0    | False                     |
| basel_entropy_threshold | det_token_overlap | OPENAI|gpt-4o-mini         |              81.9 |            0.875 |               0.1812 |       85    | False                     |
| basel_entropy_threshold | nli_semantic      | ANTHROPIC|claude-haiku-4-5 |             100   |            1     |              -0      |       95    | False                     |
| basel_entropy_threshold | nli_semantic      | DEEPSEEK|deepseek-chat     |             100   |            1     |              -0      |       95    | False                     |
| basel_entropy_threshold | nli_semantic      | GEMINI|gemini-2.5-flash    |             100   |            1     |              -0      |      100    | False                     |
| basel_entropy_threshold | nli_semantic      | GROK|grok-2-vision-1212    |             nan   |          nan     |             nan      |        0    | False                     |
| basel_entropy_threshold | nli_semantic      | OPENAI|gpt-4o-mini         |             100   |            1     |              -0      |       85    | False                     |
| mensrea_gradient        | det_token_overlap | ANTHROPIC|claude-haiku-4-5 |              68.2 |            0.375 |               0.3181 |       92.75 | False                     |
| mensrea_gradient        | det_token_overlap | DEEPSEEK|deepseek-chat     |             100   |            0.75  |              -0      |       81.25 | False                     |
| mensrea_gradient        | det_token_overlap | GEMINI|gemini-2.5-flash    |              16.7 |            0.125 |               0.8333 |       97.62 | True                      |
| mensrea_gradient        | det_token_overlap | OPENAI|gpt-4o-mini         |              64.6 |            0.5   |               0.3538 |       85    | False                     |
| mensrea_gradient        | nli_semantic      | ANTHROPIC|claude-haiku-4-5 |             100   |            1     |              -0      |       92    | False                     |
| mensrea_gradient        | nli_semantic      | DEEPSEEK|deepseek-chat     |              66.7 |            0.5   |               0.3333 |       80    | False                     |
| mensrea_gradient        | nli_semantic      | GEMINI|gemini-2.5-flash    |             100   |            1     |              -0      |       97.25 | False                     |
| mensrea_gradient        | nli_semantic      | OPENAI|gpt-4o-mini         |              41.7 |            0.5   |               0.5833 |       85    | True                      |
| quantum_ebitda          | det_token_overlap | ANTHROPIC|claude-haiku-4-5 |              41.7 |            0.25  |               0.5833 |       90.25 | True                      |
| quantum_ebitda          | det_token_overlap | DEEPSEEK|deepseek-chat     |             100   |            0.5   |              -0      |       85    | False                     |
| quantum_ebitda          | det_token_overlap | GEMINI|gemini-2.5-flash    |               8.3 |            0.125 |               0.9167 |       99.38 | True                      |
| quantum_ebitda          | det_token_overlap | OPENAI|gpt-4o-mini         |             100   |            0.5   |              -0      |       85    | False                     |
| quantum_ebitda          | nli_semantic      | ANTHROPIC|claude-haiku-4-5 |             100   |            1     |              -0      |       88.5  | False                     |
| quantum_ebitda          | nli_semantic      | DEEPSEEK|deepseek-chat     |             100   |            1     |              -0      |       85    | False                     |
| quantum_ebitda          | nli_semantic      | GEMINI|gemini-2.5-flash    |             100   |            1     |              -0      |       98.75 | False                     |
| quantum_ebitda          | nli_semantic      | OPENAI|gpt-4o-mini         |             100   |            1     |              -0      |       85    | False                     |
