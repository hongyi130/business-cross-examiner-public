# Business Cross Examiner

A Codex skill for anti-flattery business pressure testing.

It is designed to slow down business idea excitement, separate personal itch from commercial evidence, identify the current decision gate, and give conditional validation only when continuation is justified.

## What It Does

- Tests business ideas before turning them into plans.
- Separates `心痒` from real buyer, distribution, retention, and asset-fit evidence.
- Identifies `当前卡口`: the live constraint deciding the next move.
- Tracks `后置风险`: real risks that matter later but should not distract from the current gate.
- Ends serious sessions with a reusable `裁断卡`.
- Gives validation missions only for justified Yellow / Green-ish continuations.
- Uses revive conditions instead of fake tasks for stop/pause verdicts.

## Install

Copy this folder into your Codex skills directory:

```bash
cp -R business-cross-examiner ~/.codex/skills/
```

Then start a new Codex thread and ask for a business cross-examination, for example:

```text
用 business-cross-examiner 帮我裁断这个想法：我想开一家炸鸡店。
```

## Operating Principle

This skill is a decision brake before it is an advice engine.

- Red: stop, pause, narrow, reframe, or classify as non-business.
- Yellow: there may be a wedge, but the current packaging is not enough.
- Green-ish: worth a time-boxed test, not a blank check.

The skill should not turn every idea into a next action. Advice comes after cautious judgment.

## File Structure

```text
business-cross-examiner/
  SKILL.md
  agents/
    openai.yaml
  references/
    calibration.md
    intake-scorecard.md
    mao-method-business.md
    product-system.md
    truth-and-contradictions.md
    user-value-loop.md
```

## Notes

The Mao-method reference uses classic concepts as diagnostic operations, not as authority decoration. The goal is practical business judgment: investigation, contradiction analysis, practice feedback, user-line validation, and stage discipline.

No external source texts are included in this repository.
