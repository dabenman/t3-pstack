# pstack machine sheet (T3). Copy to ~/.config/t3-pstack/machines.md ($XDG_CONFIG_HOME/t3-pstack/machines.md when that is set). Without it, every PR owner runs on the root's machine.
# One line per machine a root may place a PR owner on, in preference order: a tie in load goes to the earlier line.
# Line: `<machine>: environmentId=<id>; capabilities=<capability>, <capability>; max owners=<n>`. Write `capabilities=none` for a machine with none.
# `environmentId` is the T3 environment `t3_environment_links` lists, and the value `delegate_task` takes as `target.environmentId`.
DESKTOP-5TMFHNH: environmentId=4ef0d6cd-9065-450b-8939-e8d8f808c012; capabilities=windows-sandbox; max owners=3
VST-LAB04: environmentId=9f8b12b5-a079-4255-991b-a4888a2d04a6; capabilities=windows-sandbox, five-app-machine; max owners=3
DESKTOP-DTO8RD6: environmentId=48905b4a-d14c-49f8-a563-94e937388b43; capabilities=windows-sandbox; max owners=3
