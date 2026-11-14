# pstack model configuration (T3). One line per role. Delete a line to fall back to the skill default.
# `inherit-parent` or `auto` as a value: the role runs on the parent chat's model (`delegate_task` omits `target`). Alias entries in a panel list still count toward its fan-out.
# budget: large (xhigh)
feature, refactoring: magpie-codex/group/pstack-t3
bug-fix: magpie-codex/group/pstack-t2
perf-issue: magpie-codex/group/pstack-t2
hillclimb: magpie-codex/group/pstack-t2
judgment and prose: magpie-codex/group/pstack-t3
hardest tasks: magpie-codex/group/pstack-t1
how explorer: magpie-codex/group/pstack-t3
how explainer: magpie-codex/group/pstack-t3
why investigators: magpie-codex/group/pstack-t3
why synthesizer: magpie-codex/group/pstack-t3
reflect tooling: magpie-codex/group/pstack-t3
reflect judgment, divergent, synthesizer: magpie-codex/group/pstack-t3
arena runners: magpie-codex/group/claude-t3, magpie-codex/group/gpt-t3, magpie-codex/group/deepseek-pool
arena cross-judge pool: magpie-codex/group/claude-t1, magpie-codex/group/gpt-t1
swarm workers: magpie-codex/group/pstack-t3
architect runners: magpie-codex/group/claude-t3, magpie-codex/group/gpt-t3, magpie-codex/group/deepseek-pool
interrogate reviewers: magpie-codex/group/claude-t1, magpie-codex/group/gpt-t1
session hook: on
