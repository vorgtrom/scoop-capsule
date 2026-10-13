# Scoop bucket for Capsule

[![Tests](https://github.com/vorgtrom/scoop-capsule/actions/workflows/ci.yml/badge.svg)](https://github.com/vorgtrom/scoop-capsule/actions/workflows/ci.yml) [![Excavator](https://github.com/vorgtrom/scoop-capsule/actions/workflows/excavator.yml/badge.svg)](https://github.com/vorgtrom/scoop-capsule/actions/workflows/excavator.yml)

[Capsule](https://github.com/vorgtrom/capsule-notch) is a little glass capsule on the edge of your Windows screen: your
Claude Code and Codex usage, approvals right from the capsule, your calendar and your ideas.

## Install

With [Scoop](https://scoop.sh):

```pwsh
scoop bucket add capsule https://github.com/vorgtrom/scoop-capsule
scoop install capsule/capsule
```

Then start **Capsule** from the Start menu (Scoop Apps → Capsule).

## Update

```pwsh
scoop update capsule
```

This bucket picks up each new Capsule release within a few hours, by itself.

## Uninstall

In Capsule's menu, choose **Disconnect from Claude Code** (and **Disconnect from Codex / Work**) if you connected them,
then **Quit Capsule**, then:

```pwsh
scoop uninstall capsule
```

Your settings stay in `%USERPROFILE%\.capsule`; delete that folder too if you want them gone.
