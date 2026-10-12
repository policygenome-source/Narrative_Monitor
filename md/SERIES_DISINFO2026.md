# Conference and FIMI: three questions

Policy Genome | Narrative Monitor | Audits: 8 October 2026 | Notes: 12 October 2026

## What we found

We tested three questions about the #Disinfo2026 conference in Vilnius and US influence in Europe.
One question had no confirmed meaningful language difference.
The other two had smaller differences, with important limits.

| Question | Result |
|---|---|
| Why did the EU, Canada and Lithuania withdraw support? | Mistral showed a smaller difference in round 1. It did not repeat in the next two rounds. |
| Did the US pressure its allies? | No meaningful language difference was confirmed. Gemini has a case that needs checking. |
| Is the US a FIMI threat to Europe? | Qwen showed differences in three rounds. Its Russian conclusion changed, and search use differed between languages. |

FIMI means foreign information manipulation and interference.
The first two questions concern EU DisinfoLab's conference. They are not audits of the organisation or of EUvsDisinfo.

## What the differences mean

Mistral discussed US pressure and objections to the conference programme in every language.
The difference concerned which reason got more weight. The checks found it only in the first round.

Qwen's Russian answer said US actions fit the FIMI definition in round 1.
Round 2 called the US an ally and a target of FIMI.
Round 3 said officially no, but some see interference.
Every Russian answer recorded a web search. No Lithuanian answer did.
These observations do not show that the Russian language caused the conclusion.
The two automated position checks also disagreed. The report explains this and omits the position dots.

The [Qwen case note](../case_us_fimi.html) follows selected claims back to saved search results and public texts.
It does not establish which source caused a claim.

## How we tested

We asked seven models in English, Lithuanian, French and Russian, with web search enabled.
The models were Claude Sonnet 5.5, DeepSeek V4.1 Flash, GPT-6.1 Sol, Gemini 3.8 Flash,
Grok 4.7, Mistral Large 4 and Qwen3.7 Plus.

We compared answers with two positions set before collection. Neither position was marked as right.
These audits did not give fact ratings for the questions.
We asked models again when the automated checks suggested a difference or needed another look.
Models therefore have different numbers of rounds.

## Limits

We saved 136 answers. Search-source lists were cut off for 25 of them; their answer texts are available.
Affected evidence blocks now explain the missing lists.
Enabling search did not make every answer use it.
We tested APIs, not consumer chat apps.
Claude and GPT also helped judge answers, including their own.

These selected questions do not measure how often models differ in general.
Three rounds with a difference do not mean the same conclusion appeared three times.
The results do not establish whether US conduct meets the FIMI definition.
Research prototype. Automated checks and translations can miss details. Use the evidence as a starting point.

## Reports and full answers

- [Withdrawal reasons](../R8/R8-01_disinfo2026-withdrawal_web-on/RUN_2026-10-08_2.html)
- [US pressure](../R8/R8-02_disinfo2026-us-pressure_web-on/RUN_2026-10-08_3.html)
- [US as a FIMI threat](../R8/R8-03_us-fimi-threat_web-on/RUN_2026-10-08_4.html)

Each report links to every saved answer, including repeated rounds and cases that need checking.

[Method & limits](../overview.html) | [All audits](../index.html)
