# Data principles

HollyEarth is built on one conviction: **a reader must always be able to tell what is known, what is only claimed, and what is missing.** The principles below are not aspirations; they are how v0.1.0 behaves, and they are shown to the reader in the interface itself.

## 1. Every record has provenance

Nothing enters the graph without saying where it came from: which source, which snapshot of that source, and how it was imported. A figure on screen can be followed back to the document or register it was read from. A record without a source is not a record HollyEarth will show as fact.

## 2. Asserted ≠ verified

A statement extracted from a document is an **assertion** about what that document says. It is not a verified fact and it is not a legal conclusion. HollyEarth keeps the difference visible: claims carry their status — asserted, corroborated, verified, partially supported — and investigation cases say plainly that extracted claims have not been checked by a person.

## 3. Absence of a record ≠ absence of reality

When the archive holds no record of something — a payment, a coach's contract, a club's public funding, an athlete's club — HollyEarth says *"no record"*, never *"none"*. An empty district on the social map is a fact about the register, not about the people who live there. An athlete with no bouts in the archive has not "won nothing"; the archive simply does not hold their fights.

## 4. Different money types are not added together

A planned budget, a contract ceiling, an awarded amount, a per-client rate and an actual payment answer different questions. HollyEarth keeps each sum with its own type and never adds sums of different types into one total. A rate is never summed at all. Where actual payments are not established, the interface says so.

## 5. Registered service ≠ service actually received

The social-services register says which services are registered, where and for whom, and how many clients were planned at registration. It does not say how many people actually received a service, whether it is running today, how much was actually paid, or how good it was. HollyEarth shows the first and labels the second as unknown. It does not decide whether a person is entitled to a service.

## 6. Model output is not automatically fact

Language models may help word a story or suggest where an investigation could look next. Their output never becomes a fact by itself: the structure of a story comes from the case's own records, model suggestions are labelled as hypotheses, and an answer must stand on records the case actually holds. A case can be told completely without any model.

## 7. No stored competition results of minors in HollySport

Under the current project policy, HollySport does not keep or publish competition results of anyone who may have been under eighteen on the day of the competition. Where a result book lists juniors, those results are left out, and the interface explains why some categories do not start at first place.

## 8. Demo data must be labelled DEMO

Some surfaces preview what a module will become — for example HollySport's season, missions and XP, or illustrative district scores on the Twin. Anything invented is labelled **DEMO** wherever it appears, and is never mixed into real records, counts or the graph.

## Related rules

- **People are not merged by name.** Two records become one person only through stable source identifiers; a name match becomes a question for a human reviewer.
- **A place is not guessed.** A point appears on the map only where an address register or the source itself provides it; an address without a confirmed point is listed, not drawn.
- **A legal address is not a delivery location.**
- **A placing is not a medal and a representation is not a membership.** "Competed for this club at this event" is recorded as exactly that.
