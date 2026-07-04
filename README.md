# Business Cross Examiner

A Codex skill for anti-flattery business pressure testing.

It is designed to slow down business idea excitement, separate personal itch from commercial evidence, identify the current decision gate, and give conditional validation only when continuation is justified.

## 中文简介

`business-cross-examiner` 是一个用于商业想法裁断的 Codex skill。

它不是默认给建议的商业顾问，而是一个“反谄媚”的商业审讯器：先判断这个想法值不值得继续，再决定是否需要验证动作。它会帮助你区分：

- 这是 `心痒`，还是有真实商业理由？
- 当前真正卡住下一步的是不是 `当前卡口`？
- 哪些风险只是 `后置风险`，现在不该分散注意力？
- 这个想法应该停止、暂停、缩窄、调查，还是进入一个小验证？

适合用来测试副业、AI 产品、付费社群、自媒体商业化、线下店、技能产品、咨询服务、内容产品和早期创业想法。

## 示例用法

```text
用 business-cross-examiner 帮我裁断这个想法：我想开一家炸鸡店。
```

```text
帮我做一次商业反问：我想把这个 AI skill 做成付费社群。
```

```text
这个项目现在的当前卡口是什么？哪些只是后置风险？
```

## What It Does

- Tests business ideas before turning them into plans.
- Separates `心痒` from real buyer, distribution, retention, and asset-fit evidence.
- Identifies `当前卡口`: the live constraint deciding the next move.
- Tracks `后置风险`: real risks that matter later but should not distract from the current gate.
- Ends serious sessions with a reusable `裁断卡`.
- Gives validation missions only for justified Yellow / Green-ish continuations.
- Uses revive conditions instead of fake tasks for stop/pause verdicts.

## 输出形态

严肃裁断通常会输出：

- 裁断一句话
- 事实分层
- 当前卡口
- 后置风险
- 心痒 vs 生意理由
- 谨慎选择
- 最小验证动作，只有在值得继续时才给
- 杀死指标或 revive condition
- 可复用的 `裁断卡`

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
