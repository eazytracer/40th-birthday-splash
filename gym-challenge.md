# The B-Side Gym Challenge 🎴

Eric's 40th · Saturday Jul 25 · The B-Side, Council Bluffs

A Pokémon-themed scavenger hunt that runs *during* the concert. Guests are
**Trainers**. Friends & family are **Gym Leaders**. Eric is the **Champion**.
Collect gym badges → earn booster packs → best card of the night wins the box.

Designed for a loud room with limited talking: every challenge is a *do-a-thing*,
not a *have-a-conversation*, and the whole thing nudges people toward meeting
others, sharing dreams, and supporting the local scene.

---

## How tracking works (and why it can't be hacked)

The instinct is to have the website track badges — but a static public page can't
be the source of truth for real prizes (anyone can share/fake a code, and nobody
wants to type in a dark, loud bar). So we do what Pokémon did: **the badge is a
physical thing the Gym Leader controls.**

**Three pieces:**

1. **Trainer Card** *(the scorecard)* — a printed card with 8 empty badge slots.
   Handed out at Friday dinner and at Saturday's door. This is the only thing that
   counts at the prize table.
2. **A distinct stamp per Gym Leader** *(the badge)* — each leader gets their own
   rubber stamp (or a unique holo sticker). They witness the challenge, they stamp
   the slot. You can't fake a stamp you don't hold, and the leader saw you earn it.
   Cheap, reusable, one-handed, works in the dark.
3. **The website** *(the Pokédex / rulebook)* — explains the quest, lists the 8
   gyms and where to find each leader, holds the "follow these bands" links and the
   donation link, and reminds people when to raise their flashlight. All static, no
   security needed.

**Optional nicety:** a personal digital checklist on the site (tap a badge you've
earned, saved in your browser via localStorage). It gates *nothing* — it's just a
souvenir/reference for the guest — so there's nothing to hack. The prize table only
ever counts stamps. Recommend building this *only if* it's fun; the card is the
real system.

---

## The 8 Gyms

Kanto has exactly 8 badges — no padding required. Each challenge is thematic to the
badge's type by pun or wording.

### 1. Boulder Badge — Rock — *"Support the Scene"*
**Leader:** Brock · info/merch table
Our local rock scene needs a solid foundation. Follow **all** of them on social —
[the kids' bands], **The B-Side**, and **School of Rock Omaha** — and show a Gym
Leader your follows.
> *"You can't rock without something solid underneath."*

### 2. Cascade Badge — Water — *"Quench"*
**Leader:** Misty · the bartender
Make a splash — grab any drink from the bar. **Water counts**, so every trainer can
play, drinker or not. Cheers with your bartender.
> *"Stay hydrated, trainer."*

### 3. Soul Badge — Poison — *"Pick Your Poison"*
**Leader:** Koga · roaming the floor
Find a trainer you **haven't met**, clink glasses, and learn one thing about them.
Two new souls, one toast. Both of you can claim the badge.
> *"Pick your poison — and someone new to share it with."*

### 4. Thunder Badge — Electric — *"Light It Up"*
**Leader:** Lt. Surge · stage-side (or the band gives the signal)
When **iPod Shuffle** plays *"Where Is My Mind,"* raise your phone flashlight and
light up the room. Get caught glowing.
> *"Give the birthday boy a few thousand volts."*

### 5. Rainbow Badge — Grass — *"Grow the Next Gen"*
**Leader:** Erika · Future Rockers table
Help grow the next generation of rockers — donate **$5** to the **Future Rockers of
Omaha Foundation**. Online donation, cash, or a raffle-ticket purchase all count.
> *"Plant a seed, grow a rockstar."*

### 6. Marsh Badge — Psychic — *"Board of Dreams"*
**Leader:** Sabrina · Board of Dreams
Sabrina sees what's ahead. Write down a **dream** — for this year, or the next 40 —
and pin it to the Board of Dreams. Read one someone else left.
> *"She already knows what you wrote."*

### 7. Volcano Badge — Fire — *"Bring the Heat"*
**Leader:** Blaine · the open-jam host
Feel the burn — put in a **song request** or **hop on stage** during the open jam,
in person with the jam host. Amateurs welcome; that's the whole point.
> *"The stage is lava. Get on it anyway."*

### 8. Earth Badge — Ground — *"The Ground Shakes"*  ⭐ final gym
**Leader:** Giovanni · **Eric himself**, the Champion
Nothing moves the earth like a packed dance floor. Round up a crew and get a
**group photo** on the floor with the birthday boy.
> *"The final gym. Come get grounded."*

---

## Rewards ladder

Redeem at the **Pokémon Center** (prize table) — one trusted person counts stamps.

| Badges | Prize |
|--------|-------|
| **3** | 1 modern booster pack |
| **6** | A 2nd booster pack |
| **All 8** | Premium high-value pack (Prismatic Evolutions / Ascended Heroes tier) |
| **Best single card pulled by 1 AM** | 👑 Sealed box — Champion's prize, Eric's choice of set |

*(Set details deliberately left off the public page.)*

---

## Physical kit / shopping list

- [ ] **Trainer Cards** — printed, business-card or postcard size, 8 labeled slots
      + a name line. Print ~1.5× your headcount (people lose them).
- [ ] **8 distinct stamps** (or 8 distinct holo sticker rolls) — one per Gym Leader.
      Distinct designs let the prize table spot a forged card.
- [ ] **Ink pads** for the stamps.
- [ ] **Booster packs** — enough for the 3- and 6-badge tiers × expected finishers.
- [ ] **~10 premium packs** for all-8 finishers.
- [ ] **1 sealed box** — the grand prize.
- [ ] **Board of Dreams** — corkboard/pegboard + pins + slips of paper + a pen on a
      string. (Psychic gym.)
- [ ] **8 laminated "Gym" signs** — badge art + type + the one-line challenge, so a
      leader can point instead of shout.
- [ ] **Lanyards / hats** so Gym Leaders are visible in a crowd.

## Gym Leader briefing (hand each leader a card)

> You are **[Leader / gym]**. When a trainer completes **[challenge]**, stamp the
> **[badge]** slot on their Trainer Card with your stamp. One stamp per card. If
> they've already got it, send them to the next gym. Keep it fast — the band's
> playing.

## Logistics notes

- **Hand out cards early** (Friday dinner + Saturday door) so people have all night.
- **Roaming vs. stationed:** Koga (meet-someone) roams; the rest are anchored to a
  spot (bar, tables, stage, dance floor) so trainers can find them.
- **The flashlight badge** is time-boxed to one song — have Lt. Surge ready and maybe
  have the band shout it out so nobody misses it.
- **Inclusivity:** Water badge accepts water; donation badge accepts a $5 raffle
  ticket; performance badge accepts a song *request*. Nobody's locked out of all 8.
- **Prize table hours:** open the Pokémon Center from ~9 PM so early finishers can
  redeem, and do the "best pull" judging near last call.

---

## Website plan (index.html)

Add a **"Gym Challenge"** section, styled with the existing sunset palette (the
rainbow sun-disc stripes already give you 8 badge colors). It should hold:

1. A short **how-it-works** blurb: pick up a Trainer Card, earn stamps from Gym
   Leaders, redeem for packs.
2. The **8 gyms** as a grid of colored badges — name, type, challenge, where to find
   the leader.
3. Live **links** inline: the bands/venue/School of Rock socials (Rock badge) and
   the Future Rockers donation link (Grass badge).
4. The **rewards ladder**.
5. *(Optional)* a personal **localStorage badge tracker** — clearly labeled *"just
   for you — real badges come from Gym Leaders."*

Open items before building the web section:
- Exact **social handles/links** for the bands, The B-Side, School of Rock Omaha.
- The **Future Rockers donation URL**.
- Confirm the **8 leader assignments** (who's playing Brock, Misty, etc.).
