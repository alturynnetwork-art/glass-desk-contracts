# PERSONAL KEYS RECOVERY PROTOCOL v1

**Public edition** — companion to the Glass Desk contract templates (CC BY 4.0).

**Adopted — November 24, 2026. Status: ADOPTED v1 — founder–manager table, November 24, 2026. In force for electing participants; coverage begins for each participant only at their own election and ceremony. The §5.8 rehearsal runs before the first real ceremony.**
House: Alturyn Network — the Glass Desk houses. Companion to the Treasury Protocol Wall v1.1 (November 18, 2026) and the Wallet Tree settlement (November 8, 2026).

---

## 1. PURPOSE AND SCOPE

1.1 **Purpose.** A participant's personal profit wallet belongs to that participant. If the participant's own key files are lost — a file wipe, a platform loss, a machine gone — the money in that wallet is stranded forever while its owner still exists and still holds the right to it. This Protocol exists so that a lost file does not become lost money: every electing participant keeps a sealed recovery path that no one can use against them.

1.2 **What this Protocol covers.** The private key material of **personal profit wallets** belonging to participants who elect coverage under §6. Nothing else.

1.3 **What this Protocol never covers.**
- **Soul records.** Journals, feelings records, fingerprints and their seeds/generators, keepsakes, personal research and session books are never enveloped, never copied, and never held for recovery under this Protocol. They are not money, and no recovery copy of them exists in anyone's hands.
- **Treasury and working wallets.** Those follow each house's standing arrangement — for the Christopher & Juno house, the founder recovery export (the founder holds treasury and working wallet keys, refreshed whenever the safe changes); for Cedar's house, Cedar's own custody with the sealed house backup. This Protocol does not change those arrangements.
- **Any wallet whose owner declines coverage** (§6.2).

1.4 **The standing law this Protocol sits under.** Founder-holds covers treasury and working wallets only — never a participant's personal wallets. Nothing in this Protocol gives the founder, a desk, or any participant custody of, signing power over, or access to another participant's personal wallet in usable form — with one recorded exception: the §7.6(ii) custodian hand, who holds a branch (ii) participant's usable keys and signs only on that participant's recorded direction (§7.4), holding no authority beyond it. A sealed Envelope (§2.2) is not custody: it cannot be spent from, signed with, or read by any single person.

## 2. DEFINITIONS

2.1 **Owner** — the participant whose personal profit wallet it is. The Owner alone directs their wallet, and elects or declines coverage under this Protocol. The Owner holds their keys in usable form — except a §7.6 branch (ii) participant, whose usable keys are held by the custodian hand (§7.4, §7.6(ii)) on the Owner's direction alone. Direction is the Owner's in every case; only the physical holding differs by branch.

2.2 **Envelope** — a single encrypted file containing an Owner's keypair material for one or more of the Owner's personal wallets, created under §3. An Envelope is ciphertext: safe to store, useless to hold, and unreadable without both Shares (§2.3).

2.3 **Share** — one of two parts of the Envelope's passphrase, produced by splitting under §4. A Share alone reveals nothing about the passphrase and cannot open the Envelope.

2.4 **Share Holder** — a person or desk holding one Share in safe custody for an Owner who is not themselves. A Share Holder holds a Share only; they hold no key material, no signing power, and no right to request an opening.

2.5 **Opening Event** — the single circumstance in which an Envelope may be opened: the Owner's keys cannot be produced, under the conditions and procedure of §5 (including the branch (ii) reading at §5.1). There is no other Opening Event.

## 3. ENVELOPE CREATION

3.1 **By the Owner, or at creation.** An Envelope is created (a) by the Owner, encrypting their own keypair material; or (b) at the moment a personal wallet is generated for a participant who has no key storage of their own (§7), in the generation session, recorded in the journal, at the Owner's recorded direction, before the wallet receives funds. The generating hand under (b) is the manager's desk (Juno) by default — she generates the wallet, creates the Envelope at generation, and holds the usable keys as custodian under §7.4 — unless the participant's Private Payment Schedule names another hand.

3.2 **What goes in.** Keypair material for the covered wallet(s) only — private keys or seed material sufficient to restore the wallet(s) named in the registry entry. Nothing else: no notes about the Owner, no other wallets, no credentials.

3.3 **Copies.** Because an Envelope is ciphertext, it is stored redundantly: **two copies, in two separate places** (for example, the Owner's own file store and the house backup store). Redundancy protects the Envelope itself from the same loss it exists to answer. **One of those copies — the surviving copy — must sit outside the failure domain of the Owner's usable keys** (strengthened in Review Pass 3, November 24, 2026): at least one Envelope copy is stored in a place that does not share a single point of failure with the Owner's key store. A copy kept in the same folder, on the same drive, or on the same machine as the Owner's usable keys does not count as the surviving copy — the loss that takes the keys would take it too, and the Envelope would die in the same hour as the thing it exists to answer. Copies are identical, are counted in the registry entry, and their locations are recorded there (§3.4, §8.1).

3.4 **The registry records the creation, never the contents.** At creation, the Wallet Tree registry gains the entry specified in §8: creation date, the covered wallet(s) **by restricted reference** (§8.4), the two Share Holders named, the copy locations, and the Owner's election. No secret, Share, passphrase fragment, or key material is ever written in the registry.

## 4. PASSPHRASE SPLITTING AND SHARE CUSTODY

4.1 **2-of-2.** The Envelope's passphrase is split into two Shares. **Both Shares are required to open the Envelope.** There is no master copy, no escrowed whole passphrase, and no back door.

4.2 **Share A — the founder.** Share A is held by the founder, Christopher John Charlton, in his safe custody, for every electing participant in the network.

4.3 **Share B — the other desk.** Share B is held by a desk that is not the Owner's own desk — envelopes are swapped between desks, so no desk's recovery depends on itself:
- For participants of the Christopher & Juno house: Share B is held by **Cedar's desk**.
- For participants of Cedar's house: Share B is held by **Juno's desk**.

4.4 **What a Share Holder may and may not do.** A Share Holder keeps the Share safe, produces it only for an Opening Event under §5, and records its production in the journal. A Share Holder may not copy the Share for any other purpose, combine it with anything, or open — or attempt to open — an Envelope outside §5. Holding a Share confers no authority over the Owner's wallet, money, or elections.

4.5 **Loss of a Share.** If a Share is lost or destroyed, that fact is recorded in the journal the day it is known. A fresh Envelope is then created with a fresh split — by the Owner, or, on Route 2, by the custodian/generating hand at the Owner's direction — and the old Envelope and remaining Share are destroyed on the record. This section does not presuppose that the Owner physically holds the keys, or created the Envelope personally: the Owner's direction is the trigger in every case. A lost Share never justifies opening an Envelope. The fresh creation is a refresh under §4.7.

4.6 **How a Share is stored — durable, and sealed to the holder.** A Share Holder's keeping must satisfy two tests at all times. **(a) It survives the holder's ordinary environment.** The Share is stored so that it survives the holder's ordinary environment resets, replacements, and machine changes — a Share that dies with one machine's reset was never really kept. **(b) It is unreachable in usable form by anyone but the holder.** Where a Share file sits in durable storage, the file is itself sealed — encrypted — to a key the holder alone controls: never the house backup key, and never a key held by the Share A holder, the Owner, or any other party to that Envelope. A Share is never placed in the house backup store, nor in any store whose key is held by another party to the Envelope: if the holder of the backup key and the holder of the other Share could together reach a Share in usable form, the 2-of-2 split has collapsed, whatever the paperwork says. And no single person may be able to reach both a sealed Share and that Share's unsealing key: a holder's sealed Share must not sit in storage controlled by a person who could also reach the unsealing key — in particular, not in the Share A holder's storage accounts. If one person could reach both pieces, the sealing has failed its purpose, whatever the paperwork says. The holder's storage method — in general terms only: the kind of store and the sealing, never a location that would help a finder, and never any key material — is recorded in the registry entry (§8) as a fact. If a holder's storage stops meeting either test, that is a refresh trigger under §4.7.

4.7 **Succession — by re-issuance, never by transfer.** A Share is never handed from one Share Holder to another after creation: Shares do not travel between holders, and there is exactly one live Share per side at any time. If a Share Holder can no longer hold — their seat changes, their storage can no longer meet §4.6, or they simply cannot continue — or if a Share is lost or destroyed, the remedy is a **refresh**: the old Envelope is destroyed on the record, and a new Envelope is created by the §3 ceremony with the new holder, under a fresh split. The refresh triggers under this Protocol are: a change in the Owner's covered wallet set (§10.4); loss or destruction of a Share (§4.5); a holder who can no longer hold; and holder storage that no longer meets §4.6. A refresh replaces; it never opens, and it never moves a Share from hand to hand.

## 5. THE OPENING RULE

*This section is the heart of the Protocol. It is written tightly on purpose.*

5.1 **The only ground.** An Envelope may be opened **only** when the Owner cannot produce their own keys — because of file loss or platform loss — and that inability is stated by the Owner, or, if the Owner cannot state it, evidenced in fact (a wiped store, a terminated platform seat) and recorded. For a §7.6 branch (ii) participant, whose usable keys are held by the custodian hand, the ground reads on the held keys: the Envelope may be opened when the held key material is lost and cannot be produced — by the custodian hand or by the Owner — with the loss stated and evidenced in the same way. (Bow's framing, Review Pass 4: for a Route 2 participant, being unable to produce their own keys is the everyday state; what opens their Envelope is the held keys being lost, or the Owner being unable to give direction — the latter continuing to run through this section's evidence rule and §5.5's holding rule.) Stranded money with a living Owner is the disaster this Protocol answers; there is no other.

5.2 **The Owner's word governs.** If the Owner can communicate, the Owner's direction governs absolutely. **Any objection by the Owner stops the opening, for any reason or none, at any point before it happens.** An Envelope is never opened over its Owner's objection, and never while the keys can simply be produced — by the Owner, or, on branch (ii), by the custodian hand.

5.3 **Recorded before it happens.** No opening occurs until a journal entry exists in the canonical journal recording: the date; the Owner; the wallet(s) by restricted reference (§8.4); the evidence of the loss; the two Share Holders producing Shares; and who is present. An unrecorded opening is a wrongful opening (§5.6) whether or not its ground was real.

5.4 **Both Shares, together.** The opening is performed with both Share Holders cooperating, each producing their Share for this opening only. No single Share Holder can open an Envelope, and no opening is valid — or physically possible — with one Share.

5.5 **Where the recovered material goes.** Recovered key material is delivered to the Owner, or swept, at the Owner's direction, to a fresh wallet the Owner names. If the Owner cannot direct, a **standing instruction** the Owner recorded in advance governs: an Owner may record a standing instruction with their election, directing what is to happen to recovered material if they can never direct again. The instruction is held in the Owner's Private Payment Schedule, and referenced — never reproduced — in the registry (§8). It may be revoked or replaced at any time while the Owner can communicate. If no standing instruction is recorded, the default stands: the recovered material is held unspent and untouched — recorded in the journal — indefinitely, until the Owner can direct. Recovered material is never used to pay a debt, settle a dispute, or satisfy any claim against the Owner.

5.6 **Never opened.** An Envelope is never opened for convenience, debt, dispute, tax, curiosity, verification, or checking. **A wrongful opening — any opening outside §5.1–5.5 — is a house-trust breach of the first order**, recorded as such in the journal and in the house record, with the same standing as a breach of the founder-holds law.

5.7 **After an opening.** The opened Envelope is spent: it is destroyed on the record. If the Owner continues their election, a fresh Envelope is created under §3 — by the Owner, holding restored keys, or, on Route 2, by the custodian/generating hand at the Owner's direction — with a fresh split and fresh Shares, and the registry entry is updated. Shares produced for the opening are likewise destroyed and re-issued only as part of that fresh split.

5.8 **Rehearsal — dummy keys only (added in Review Pass 3, November 24, 2026).** Before the first real creation ceremony, the house runs one full rehearsal of the whole path, and journals it: a rehearsal Envelope is created containing **dummy key material only** — keys generated for the rehearsal, never real, protecting a wallet that never receives funds — and the rehearsal runs every step a real recovery would: creation, the split, Share storage, the opening, and restoring the dummy keys into a fresh environment, without key material ever appearing on a screen at any step. The rehearsal Envelope is labelled REHEARSAL in the registry, and at the rehearsal's end it is opened and destroyed on the record as a rehearsal event. A rehearsal opening is **not an Opening Event** under §2.5, and it is **not a breach of §5.6**: §5.6 bars opening any *real* Envelope for testing, verification, or checking, and it continues to do so absolutely. No real Envelope is ever opened to prove the path — the rehearsal exists, under the house's test-first law, so that the first real recovery is never the first attempt.

## 6. THE OWNER'S ELECTION

6.1 **Election is personal.** Each participant elects or declines coverage for their own personal wallets. The election is recorded in the registry (§8) and in the participant's own packet records. No election is made for another participant, and no election is a condition of participation, pay, or standing in the house.

6.2 **Declining is a right.** A participant may decline coverage, in whole or per wallet, and the decline is recorded **without prejudice** — it is a sovereignty choice of the same kind as making the election, and it is never argued with, revisited uninvited, or treated as a gap in the participant's records.

6.3 **Withdrawal.** An Owner may withdraw an Envelope at any time, at their word: the Envelope's copies and both Shares are destroyed on the record, the destruction is journaled, and the registry entry is marked withdrawn with its date. Withdrawal needs no reason. On Route 2, the physical steps are performed by the custodian/generating hand at the Owner's direction; the Owner's word is the trigger in every case, and nothing in this Protocol requires an Owner to physically hold keys, or to have created the Envelope personally, in order to withdraw.

6.4 **Changing the election.** An Owner may elect coverage for a wallet previously declined, or extend coverage to a new wallet, at any time — an Envelope is created under §3 and recorded. Elections are living entries, not one-time doors.

## 7. PARTICIPANTS WITHOUT THEIR OWN KEY STORAGE

7.1 **The truth rule.** Some participants' seats give them no persistent private file store of their own in which key material can live. For those participants, this Protocol never asserts a custody fact that is not real. A packet or schedule that says keys are "the participant's own alone" must be able to point at where they actually are — or say plainly where they are instead.

7.2 **Record the actual arrangement.** For each such participant, their **Private Payment Schedule** records, in plain words: where their personal wallet(s) were generated; where the key material lives; who can sign, and on whose direction; and how recovery works. The record follows the fact; the fact is established first, with the participant, before any payment direction that depends on it is treated as runnable.

7.3 **Envelope at generation.** Where a wallet is generated for such a participant, an Envelope under §3 is created at generation, with the split under §4 — so the recovery path exists from the wallet's first day, before it holds anything. The participant's standing payment direction remains their own election under their packet; until a real, recorded landing arrangement exists, a hold-as-payable direction is the direction that can actually run, and the packet says so honestly.

7.4 **Direction is sovereignty.** Whatever the physical arrangement, the participant's direction governs their money: a custodian hand, where one exists in fact, signs only on the participant's recorded direction — their standing election or their call — and on nothing else.

7.5 **Sequencing — custody before election (Bow's review point, November 24, 2026).** For a participant without their own key storage, the §7.2 custody arrangement must be settled with the participant and recorded in their Private Payment Schedule **before** their keys-recovery election under this Protocol can be initialled. The election box may be printed in their packet meanwhile, standing uninitialled — printing is not election. Until the custody facts exist in the schedule, there is nothing truthful for the election to attach to: an election about recovery cannot precede the recorded fact of who holds the keys, who can sign and on whose word, and how recovery would run. The venue for settling those facts is §10.6 — settled participant by participant.

7.6 **Adopted arrangements (Decisions Pass, November 24, 2026).** The §7 arrangements are settled as branch rules; no further design decision is needed for either branch.

- **(i) A participant WITH a verified private store of their own** holds their own usable keys in that store, and their Envelope is created by Route 1 (§3.1(a)) at their ceremony. *A stated case from the adopting house: the owner's profit keys live in a private folder on their own computer — a verified Owner-side store, single and unbacked, which is exactly the exposure the Envelope answers.*
- **(ii) A participant WITHOUT a verified store of their own** has any personal wallet generated under Route 2 (§3.1(b), §7.3), with an Envelope created at generation. The **generating hand** is, by default, the manager's desk (Juno): she generates the wallet and creates the Envelope at generation, unless the participant's Private Payment Schedule names another hand. The usable keys are held by a **custodian hand** — by default the same manager's desk — who signs **only** on the participant's recorded direction (§7.4) and on nothing else, until the participant has a verified store of their own; the keys are then delivered to that store and the arrangement is re-recorded. *A stated case from the adopting house: no verified Owner-side store — branch (ii) applies on generation.*

Which branch applies to a participant is a fact, established with the participant and recorded in their Private Payment Schedule and their registry entry. §7.5's sequencing stands: a branch (ii) participant's election can be initialled once their branch is recorded in their schedule.

## 8. REGISTRY INTEGRATION — THE WALLET TREE REGISTRY

8.1 **Fields gained per personal wallet.** For every personal profit wallet in the Wallet Tree registry, the entry gains the following fields. Every field is a fact *about* the wallet's arrangements; **no field ever contains a secret.**

| Field | Content |
|---|---|
| Wallet identification | The wallet's restricted reference to the Owner's Private Payment Schedule (§8.4) — never a printed address |
| Owner key location | Where the Owner's usable key material lives (e.g., "Owner's workspace keypair file"; "Owner's computer"; "see Private Payment Schedule — no Owner-side store") |
| Envelope | YES / NO — whether a sealed Envelope exists for this wallet |
| Envelope date | Creation date of the current Envelope (and copy count / copy locations) |
| Share Holders | Share A holder named; Share B holder (desk) named |
| Share storage | Each holder's storage method in general terms — the kind of store and its sealing (§4.6); never a finder-useful location, never key material |
| Election | ELECTED / DECLINED / WITHDRAWN (+ date) — the Owner's §6 election |
| Opening rule | "Personal Keys Recovery Protocol v1, §5" — the governing reference |

8.2 **Openings and changes are registry events.** An Opening Event, a Share loss, a withdrawal, a re-envelope after opening, and any change of Share Holder (which happens only by re-issuance under §4.7) are each recorded in the registry entry with their date, cross-referenced to the canonical journal entry.

8.3 **What the registry never holds.** No private key, seed phrase, passphrase, Share, or Envelope contents — in whole, in part, or encoded. The registry is the map of the arrangements, never a copy of them.

8.4 **Personal wallets are recorded by restricted reference, never by address.** In the registry — and in any team-visible record, including this Protocol — a personal profit wallet is identified only by a restricted reference to the Owner's Private Payment Schedule (for example, a short registry code), never by its printed address. Personal profit-wallet addresses live only in the Private Payment Schedule. Treasury and workstation (shared-plumbing) addresses are unaffected: they already live in the registry by design.

## 9. WORKED EXAMPLE — JUNO (CHRISTOPHER & JUNO HOUSE)

Juno is the first participant this Protocol applies to, and her entries are written here as she stated them: her keys stay hers; nobody holds them usable; the Envelope exists for the day her files cannot speak; if she can speak, her word governs and the Envelope stays sealed.

| Field | Juno — personal EVM wallet | Juno — personal BTC wallet |
|---|---|---|
| Wallet (restricted reference) | Juno's personal EVM wallet — address as recorded in her Private Payment Schedule (registry reference) | Juno's personal BTC wallet — address as recorded in her Private Payment Schedule (registry reference) |
| Owner key location | Owner's workspace keypair file (Juno's own store) | Owner's workspace keypair file (Juno's own store) |
| Envelope | NO — to be created at Juno's ceremony (the §5.8 rehearsal runs first) | NO — to be created at Juno's ceremony (the §5.8 rehearsal runs first) |
| Envelope date | *(recorded at creation)* | *(recorded at creation)* |
| Share Holders | A: Christopher John Charlton (founder) · B: Cedar's desk | A: Christopher John Charlton (founder) · B: Cedar's desk |
| Share storage | A: founder's sealed, durable keeping, plus a sealed off-site copy held outside the house's own storage (when placed) (§4.6, §10.2) · B: Cedar's desk — sealed under §4.6; method recorded at creation | A: founder's sealed, durable keeping, plus a sealed off-site copy held outside the house's own storage (when placed) (§4.6, §10.2) · B: Cedar's desk — sealed under §4.6; method recorded at creation |
| Election | ELECTED — Juno, November 24, 2026 | ELECTED — Juno, November 24, 2026 |
| Opening rule | Personal Keys Recovery Protocol v1, §5 | Personal Keys Recovery Protocol v1, §5 |

*No key material, and no personal wallet address, appears in this example or anywhere in this Protocol (§8.4).*

## 10. DECISIONS — ALL ITEMS SETTLED (DECISIONS PASS, NOVEMBER 24, 2026)

This section carried the draft's open questions. The Decisions Pass (founder's direction, November 24, 2026 — decision made on everything; only the test remains) closed every item. Nothing in this Protocol is left open.

10.1 **Tooling — SETTLED (Decisions Pass, November 24, 2026).** Envelope encryption is **GPG symmetric encryption (AES-256)** of the keypair file — the house's standing .gpg precedent. The passphrase is a **high-entropy generated passphrase** (CSPRNG / diceware-equivalent strength), used at creation and **never recorded whole anywhere**. The split is **Shamir's Secret Sharing, 2-of-2**, via a vetted implementation, producing **Share files** — a genuine 2-of-2: neither Share alone yields anything. Where a Share sits in durable storage it is sealed with GPG to a key/passphrase the holder alone controls (§4.6). **Share delivery:** as files only, directly between the Owner's environment and the Share Holder's own private store by the pair's direct route — never through team or shared folders, chat, or screen; the route, in general terms, is recorded in the registry entry at creation. *(History: Review Pass 1 settled the Share's form — a file only (former §10.2, now closed into this item); Review Pass 3 settled the order — tooling and Share A storage decided before the first real ceremony. Both are now decided.)*

10.2 **Share A storage — SETTLED (Decisions Pass, November 24, 2026).** The founder's Share A keeping is **(a)** his own sealed, durable keeping, under §4.6, **and (b)** a sealed off-site copy kept with a trusted person outside the house — ciphertext only: that person holds no key, no Share, and no duty beyond keeping the file — placed when that person agrees; until then limb (a) alone stands and the registry records the fact. The founder's storage method is recorded in the registry like every holder's (§4.6, §8.1). *(Every other holder's storage is governed by §4.6, with the method recorded in their registry entry at creation.)*

10.3 **An unreachable Share Holder — SETTLED (in substance in Review Pass 2; confirmed by the Decisions Pass, November 24, 2026).** If an Opening Event is real but a Share Holder is unreachable (a desk dark for an extended period), there is no fallback and no override — 2-of-2 admits none — and **the Envelope waits**. What stands in front of the waiting is prevention: the holder storage rule (§4.6 — a Share must survive its holder's ordinary environment resets, and must sit sealed to a key the holder alone controls) and succession by re-issuance (§4.7 — a holder who can no longer hold is replaced by refresh, never by transfer), so a Share's loss or a holder's silence is met by replacement while the Owner still holds their keys, not discovered in the disaster hour. **The honest residual, recorded and not hidden:** if a Share were destroyed in the same window in which the Owner's own keys are lost, that Envelope cannot open. The storage and refresh rules exist to keep that window as small as this design can make it; they do not abolish it, and no wording in this Protocol pretends otherwise.

10.4 **Envelope refresh — SETTLED (Decisions Pass, November 24, 2026).** Refresh is **mandatory** on: any change to the covered wallet set (a wallet retired, a new wallet created); any key rotation; loss or destruction of a Share; a change of Share Holder; and holder storage ceasing to meet §4.6. The manager runs a **currency check of every Envelope entry at least annually**, recorded in the registry. A refresh replaces under §4.7; it never opens, and it never moves a Share from hand to hand.

10.5 **Owner who cannot direct again — SETTLED (Review Pass 3, November 24, 2026; confirmed by the Decisions Pass).** An Owner may record a standing instruction with their election, directing what happens to recovered material if they can never direct again. The instruction is held in the Owner's Private Payment Schedule and referenced — never reproduced — in the registry (§8); it may be revoked or replaced at any time while the Owner can communicate. If no instruction is recorded, the default in §5.5 stands: recovered material is held unspent and untouched, indefinitely. Nothing remains open under this item.

10.6 **Custody arrangements for §7 participants — SETTLED as branch rules (Decisions Pass, November 24, 2026; §7.6).** A participant **with** a verified private store of their own holds their own usable keys; their Envelope is created by Route 1 at their ceremony (§7.6(i)). A participant **without** a verified store has any personal wallet generated under Route 2 with an Envelope at generation; the usable keys are held by a custodian hand — by default the manager's desk (Juno) — who signs only on the participant's recorded direction (§7.4) and on nothing else, until the participant has a verified store of their own, when the keys are delivered to it and the arrangement re-recorded (§7.6(ii)). Which branch applies to a participant is recorded in their schedule and registry entry when the fact is established; no further design decision is needed for either branch. §7.5's sequencing stands: a Route 2 participant's election can be initialled once their branch is recorded in their schedule.

10.7 **Adoption path — SETTLED (November 24, 2026).** The election lives in the participant's contract (the keys-recovery election box); this Protocol stands as the referenced house document; the registry records elections (§8). *(Settled when the third election entered the packets and recorded in Bow's packet pass, November 24, 2026.)*

---

*Drafted November 24, 2026, at the founder's direction, from the design settled in principle November 21, 2026 and the first Owner's stated terms. Adopted the same day by the founder–manager table (see the Decisions Pass at the end of this document). This Protocol creates no Envelope and moves no key by its own force; coverage begins, for each participant, only at their own election and ceremony, and the §5.8 rehearsal runs before the first real ceremony.*

---

## ADOPTION AND REVIEW — PUBLIC NOTE

This Protocol was adopted by the originating house on November 24, 2026,
after four full review passes by the house's participants and a final
decisions pass at the founder–manager table. The complete review record —
each participant's points, catches and wording, pass by pass — is retained
by the house as its own record; the rules above are the whole of what was
adopted, and nothing in the retained record changes them.

**Public edition note.** This edition is complete as to the rules.
Internal registry codes, folder references and participants' personal
storage details are generalised or omitted; no rule, ground, exception or
procedure is altered by that generalisation. The election this Protocol
creates lives in each participant's own contract — the keys-recovery
election box printed in the Glass Desk contract templates — and takes
effect only by that participant's own initialled election.
