### Hi, I'm Krish

Final-year Engineering Physics student at IIT Roorkee. I build LLM agents, and I care most about the evals and infrastructure that show whether they actually work. I've had 14 PRs merged into [Gemini CLI](https://github.com/google-gemini/gemini-cli/pulls?q=is%3Apr+is%3Amerged+author%3Akrishdef7) and [Kubeflow](https://github.com/kubeflow/trainer/pulls?q=is%3Apr+is%3Amerged+author%3Akrishdef7).

#### Projects

| | |
|---|---|
| [**CampusRide**](https://github.com/krishdef7/CampusRide) | LLM ride-booking agent, real-time PostGIS matching and demand forecasting. 99.4% on a 500-case held-out agent eval with 0 safety violations under prompt injection; p95 16.8 ms at ~196 req/s; forecast MAE 27.6% below seasonal-naive. |
| [**ML Sentinel**](https://github.com/krishdef7/ml-sentinel) | Is input drift a good alarm for model degradation? Across 147 cross-state deployments (5.27M rows), KS drift fired on 102 of 103 healthy ones, while ATC caught 35 of 44 degraded ones with no false alarms. |
| [**gemini-cli-eval-toolkit**](https://github.com/krishdef7/gemini-cli-eval-toolkit) | Coverage inventory, gap analysis and eval generation for Gemini CLI's hook lifecycle, built from the regressions I fixed upstream. |
| [**Voice-Orchestrator-Prototype**](https://github.com/krishdef7/Voice-Orchestrator-Prototype) | Streaming orchestration for Gemini CLI voice mode on the Live API: barge-in, cancellable tool calls, consistent transcripts. |
| [**kubeflow-llm-trainer-prototype**](https://github.com/krishdef7/kubeflow-llm-trainer-prototype) | Pluggable fine-tuning backends (TorchTune, TRL, Unsloth) for Kubeflow Trainer. |
| [**Inverse-Photonic-Design**](https://github.com/krishdef7/Inverse-Photonic-Design) | cVAE, normalizing-flow and diffusion models for thin-film inverse design. Generative sampling plus L-BFGS refinement reaches MSE 1.15e-05 vs 3.14e-05 for Differential Evolution, 44x faster. |
| [**Radiotherapy beam selection**](https://github.com/krishdef7/Deep-Reinforcement-Learning-for-Personalized-Radiotherapy-Beam-Orientation-Optimization) | DQN that picks beam angles from CT anatomy. PTV coverage 0.687 to 0.806 over equiangular plans on 100 held-out patients. |
| [**Satellite-Property-Valuation**](https://github.com/krishdef7/Satellite-Property-Valuation) | House prices from tabular data plus satellite imagery. RMSE $111,294, 6.6% better than the tabular baseline. |

#### Merged upstream

**Gemini CLI**
[#24847](https://github.com/google-gemini/gemini-cli/pull/24847) MCP: treat GET 404 as 405 in the streamable HTTP transport ·
[#24784](https://github.com/google-gemini/gemini-cli/pull/24784) propagate BeforeModel model overrides end to end ·
[#22326](https://github.com/google-gemini/gemini-cli/pull/22326) fix crash on partial `llm_request` in BeforeModel hooks ·
[#22139](https://github.com/google-gemini/gemini-cli/pull/22139) stop SessionEnd firing twice in non-interactive mode ·
[#21541](https://github.com/google-gemini/gemini-cli/pull/21541) policy engine EBUSY fallback and TOML parse recovery ·
[#21383](https://github.com/google-gemini/gemini-cli/pull/21383) fix BeforeAgent/AfterAgent inconsistencies ·
[#21239](https://github.com/google-gemini/gemini-cli/pull/21239) escape `@` on paste ·
[#20419](https://github.com/google-gemini/gemini-cli/pull/20419) flush the transcript for pure tool-call responses

**Kubeflow**
[trainer#3339](https://github.com/kubeflow/trainer/pull/3339) move `enableHTTP2` into the Configuration object ·
[trainer#3338](https://github.com/kubeflow/trainer/pull/3338) register the TrainJobStatus server with health/ready checks ·
[trainer#3324](https://github.com/kubeflow/trainer/pull/3324) `terminationGracePeriodSeconds` in PodSpecPatch ·
[trainer#3302](https://github.com/kubeflow/trainer/pull/3302) validate LoRA multi-node and immutable trainer args ·
[trainer#3301](https://github.com/kubeflow/trainer/pull/3301) fix the Fashion-MNIST example ·
[sdk#328](https://github.com/kubeflow/sdk/pull/328) handle falsy values in `get_args_from_peft_config`

<sub>Python · TypeScript · Go · PyTorch · LangGraph · FastAPI · PostgreSQL/PostGIS · Kubernetes</sub>
