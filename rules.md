# Quonauts 4 — Rules

## Table of contents

* [**1. Meta rules**](#meta)
    * [**1.1. Precedence**](#precedence)
    * [**1.2. Disallowed by default**](#disallow-by-default)
    * [**1.3. Rule violations**](#rule-violations)
        * [**1.3.1. Errors**](#errors)
        * [**1.3.2. Rule violation polls**](#rule-violation-polls)
        * [**1.3.3. Punitive action**](#punitive-action)
    * [**1.4. Bots**](#bots)
    * [**1.5. Style conventions**](#style)
        * [**1.5.1. Content**](#style-content)
        * [**1.5.2. Headers and tags**](#style-headers-tags)
        * [**1.5.3. Lists**](#style-lists)
        * [**1.5.4. Formatting**](#style-formatting)
        * [**1.5.5. Real-world time**](#time)
    * [**1.6. Glossary**](#glossary)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general-channel)
    * [**2.2. #polls**](#polls-channel)
    * [**2.3. #proposals**](#proposals-channel)
    * [**2.4. #rules**](#rules-channel)
* [**3. Roles**](#roles)
    * [**3.1. Rule offender**](#rule-offender-role)
* [**4. Activity**](#activity)
* [**5. Quantities**](#quantities)
    * [**5.1. Sharing**](#quantity-sharing)
* [**6. Pingable**](#pingable)
* [**7. Polls**](#polls)
* [**8. Proposals**](#proposals)
    * [**8.1. Proposal content**](#proposal-content)
    * [**8.2. Voting on proposals**](#proposal-voting)
    * [**8.3. Closing proposals**](#proposal-closing)
    * [**8.4. Passing and failing proposals**](#proposal-pass-fail)
    * [**8.5. Proposal modification**](#proposal-modification)
* [**9. Setting**](#setting)
* [**10. Cabals**](#cabals)
* [**11. Agents**](#agents)
    * [**11.1. Agent Operations**](#agents-operations)
        * [**11.1.1. Stealing**](#stealing)
        * [**11.1.2. Mining**](#mining)
* [**12. Sectors**](#sectors)
    * [**12.1. Visible**](#visible)
* [**13. Chunks**](#chunks)
* [**14. Randomly generated chunks**](#spawning)
* [**15. Warp drive**](#warp-drive)

## <a name='meta'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

1. If one clause has a more limited scope than another, then the clause with the more limited scope takes precedence.
2. If one clause is negative while the other is positive, then the negative clause takes precedence.
3. The clause which appears last in the rules takes precedence.

### <a name='disallow-by-default'/> Disallowed by default

Unless explicitly stated in the rules, all game actions are forbidden.

### <a name='rule-violations'/> Rule violations

A rule violation is a game action that is not permitted by the rules.

A rule violation is "resolved" by reversing the immediate effects of that rule violation (not including any indirect effects permitted in reaction to the rule violation) to the extent that it is possible.

#### <a name='errors'/> Errors

An error is a rule violation made by a player either mistakenly or through ignorance. If this player is resolve the error, they may do so.

If a player resolves an error within 24 hours of making that error, any rule violation poll for that error immediately fails. A rule violation poll may not begin after a player resolves an error; however, existing rule violation polls may continue if the error remained unresolved for 24 hours.

#### <a name='rule-violation-polls'/> Rule violation polls

If any player (hereby "the accusing player") believes that another player (hereby "the accused player") has violated the rules, then the accusing player may conduct a majority poll (called a "rule violation poll") to determine whether the accused player has violated the rules.

In conducting a rule violation poll, the accusing player must describe which sections or clauses of the rules were violated and what illegal game action was taken by the accused player. Players should vote in favor of this poll if, and only if, they agree that the accused player violated the rules as described.

Any vote in such a poll cast by the accused player is not counted.

A rule violation poll must be available for voting for at least 24 hours before any action may be taken as a result.

For any potential rule violation, only one rule violation poll may be conducted.

A rule violation poll may not be started more than 7 days after the potential rule violation.

If a rule violation poll passes, then the accused player is now convicted of violating the rules as described in the poll and the rule violation must be resolved, if it has not already.

#### <a name='punitive-action'/> Punitive action

If a player (hereby "the convicted player") is convicted, then another player may conduct a majority poll (called a "puninitive action poll") to determine whether punitive action should be taken.

Players should vote in favour of this poll if, and only if, they believe the convicted player violated the rules knowingly and with malicious intent.

Any vote in such a poll cast by the convicted player is not counted.

If a punitive action poll passes, then the convicted player gains one strike.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots;" the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning.

#### <a name='style-content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='style-headers-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='style-lists'/> Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='style-formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

#### <a name='time'/> Real-world time

Rules may refer to real-world timestamps, such as saying an event will happen at a certain time or  that different things happen depending on the weekday.

When this is done, the rule should preferably be explicit about what timezone it is referring to. However, if no such timezone is mentioned, it is assumed to be UTC.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and any subsections of that section. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic which is governed by this rules document.
* **Game Action**: A game action is any message or reaction in a game channel or any other manipulation of game channels or quantities which are part of the game.
* **Game State**: A specific arrangement of all game rules, proposals, polls, votes and quantities.
* **Game Channel**: A game channel is any text or voice channel listed in the GAME CHANNELS channel category of the Discord server.
* **Player**: Any participant of the game.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules which is contained under one header, not including any subsections.
* **Subsection**: A section of the rules which is contained under another section.
* **Clause**: A single statement in the rules

## <a name='channels'/> Channels

The game rules govern only messages and reactions in the GAME CHANNELS category of the Discord server.

Each subsection of this rule section corresponds to a game channel; as these subsections are created, removed, or reordered, game channels must be created/renamed/reordered accordingly.

### <a name='general-channel'/> #general

Players may converse freely in the <#593807344979148800> channel.

### <a name='polls-channel'/> #polls

The <#593807379360120877> channel is governed by [**7. Polls**](#polls).

### <a name='proposals-channel'/> #proposals

The <#593807201194344455> channel is governed by [**8. Proposals**](#proposals).

### <a name='rules-channel'/> #rules

The <#593807244030771211> channel contains this rules document.

## <a name='roles'/> Roles

The game rules govern roles that have effect within the game.

### <a name='rule-offender-role'/> Rule offender

If a player has a nonzero number of strikes, then they are given the "rule offender" role. If a player's number of strikes reaches zero, the "rule offender" role is removed.

Players with the "rule offender" role may not make any game action; i.e. they may not participate in the game.

After 24 hours with the "rule offender" role, a player's number of strikes decreases by one.

## <a name='activity'/> Activity

All players that have taken some game action in the preceding 72 hours are active players. All other players are inactive players.

## <a name='quantities'/> Quantities

A quantity is a named property with a numerical value for each player.

By default any unique quantity added to the game:

• applies to all players. 
• is instatiated at zero. 
• must always be an integer. 
• must never have a negative value. 
• cannot be traded or exchanged.

Existing quantities: 

• Agents: Total agents. 
• Point: A generic unit of score, which may be any nonnegative integer or decimal number. Can be shared freely between players in the same sector or in the same cabal.
• Strike: The number of rule violations that a player has committed without punishment.
• X: Player's X position. This quantity can also be negative.
• Y: Player's Y position. This quantity can also be negative.
• Omni: A material found in the depths of space.

When a proposal establishing a new quantity is passed, this rule section should be amended by inserting the new quantity into the above list, maintaining alphabetical order, along with a brief description. Similarly, if a quantity is renamed or removed, the above list should be modified accordingly.

### <a name='quantity-sharing'/> Sharing

Sharing is the act of subtracting from your quantity and adding that same amount to another player's quantity. Only shareable quantities may be shared. Sharing does not require the consent of the person being shared to. You can only share by non-negative amounts.

## <a name='pingable'/> Pingable

At any time, players may opt-in to a "Pingable" role that can be pinged by members of the server. Any member may ping the "Pingable" role, and thus everyone who has opted in to pings, as long as the last mass ping (@Pingable, @here or @everyone) was at least 1 week (168 hours) ago.

## <a name='polls'/> Polls

A poll is a means of gathering the opinions of players on an issue. Players may conduct a poll by providing any necessary detail and posing a question in the <#593807379360120877> game channel.

Players may vote in favor of a poll by reacting to the poll with 👍.

Players may vote against a poll by reacting to the poll with 👎.

Players may use any reaction they wish to respond to a poll. The player conducting the poll may interpret other reactions to the poll as they see fit, except in formal polls, where reactions may only have meaning as specified in the rules.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

## <a name='proposals'/> Proposals

Players may submit proposals by posting their proposal to the <#593807201194344455> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Unless otherwise stated in the game rules, deleted proposals retain their number.

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it.

### <a name='proposal-content'/> Proposal content

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified. Text quoted between the outermost [start] and [end] symbols (brackets required; code tags optional) is to be interpreted literally. [start] and [end] symbols can be nested.

If a proposal describes the creation of a new rule section, it must specify its title, its location in relation to an existing one, and its content.

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

A proposal may state that it depends on other proposals. If a proposal's dependencies fail, then the proposal dependent on them also fails.

A proposals may amend an existing proposal. If a proposal A amends an existing proposal B, then the amendment has no effect if B fails. If A and B both pass, then the result of proposal B is undone or modified according to proposal A. The content of proposal B, however, does not change.

A proposal may also state incompatible proposals, in which case the later proposal will fail if any proposal it is incompatible proposal on is passed.

### <a name='proposal-voting'/> Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote for or against a proposal. Players may also explicitly abstain from voting.

A player may change their vote on an open proposal at any time.

### <a name='proposal-closing'/> Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:
 * The proposal is at least 48 hours (2 days) old.
 * All active players have cast a vote on the proposal.
 * A majority of active players have voted in favor of the proposal.
 * A majority of active players have voted against the proposal.

The player that authored a proposal may fail or delete it at any time.

When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability; after this, that player gains 1 point.

When a proposal is passed, any proposals that amend it may be closed 24 hours earlier than would be otherwise allowed.

### <a name='proposal-pass-fail'/> Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails. 

When a proposal passes, its author gains 2 points.

Unless otherwise specified in the given proposal, proposals never apply retroactively; i.e., they do not affect proposals, polls, or game actions posted, begun, or carried out before their passing.

### <a name='proposal-modification'/> Proposal modification

A player may edit a proposal they have submitted if that proposal is open for voting and has no votes cast by players other than its author.

## <a name='setting'/> Setting

"In the year 2341 humanity attempted what had never been attempted before; the experimental orbital hyperjump platform known as "Armstrong Station" was to send an intrepid band of adventurers far across the Milky Way in the blink of an eye, heralding a new era of intersolar exploration. Instead, the entire station moved irregularly and irrevocably through space-time, leaving its inhabitants stranded far from home. With no immediate hope of rescue and too few resources to go around, it falls to those aboard to explore the surrounding solar systems, without knowing whether they might hope to return to Earth, or make a life for themselves in this new Wild West of the Stars."

## <a name='cabals'/> Cabals

A cabal is a group which consists of a number of one or more players. Any player may form a cabal by publically announcing its existence and the name of the cabal. The continued existence of a cabal must remain public knowledge. Each cabal has exactly one czar. This is always initially the player who forms a cabal is. A cabal's czar is responsible for defining the rules that govern its own membership, leadership, governance and disbandment. To become part of a cabal, a player must be appointed by the czar of the cabal. Members of a cabal may leave at any time. If the czar of a cabal with more than 1 player wishes to leave, they must choose a new member of the cabal to be czar. If the last player leaves a cabal, the cabal is disbanded and no longer exists. At any time, the czar of a cabal may force another member to leave.

## <a name='agents'/> Agents

Each player has a number of agents.
Each new player begins the game with 3 agents.

### <a name='agents-operations'/> Agent Operations

Agents may perform operations which are actions that change the game state. Each agent may perform an operation only if they have not done so in 24 hours. Available agent operations are only those that are explicitly allowed by the game rules.

#### <a name='stealing'/> Stealing

As an agent action, a player may steal 1 point from another player in the same sector as them.

#### <a name='mining'/> Mining

As an agent action, a player may mine a chunk that is in the same sector as them. This does the following:
Reduces the size of the chunk by 1
Gives 1 of the chunk's quantity to the player
If the chunk is now at size 0, it is destroyed

## <a name='sectors'/> Sectors

A "sector" is any unique integer combination of X and Y, written as "sector <x>, <y>”. The set of all sectors is "space."

### <a name='visible'/> Visible

Visible sectors are a type of sector. Every sector within 20 spaces of a player (with equal movement rules to "Warp Drive") is a visible sector.

## <a name='chunks'/> Chunks

A chunk is a physical incarnation of a certain quantity in the world. Each chunk has 4 variables, X, Y, type and size.

For example, a 10-gold chunk at (-1, 4) is a chunk of size 10, made out of gold, at sector (-1, 4).

When a rule or proposal says to "generate" a chunk, one is created in a random visible sector of the given type and of a random size in the given range. For example, "generate a points chunk of size 5-10".

## <a name='spawning'/> Randomly generated chunks

The following types of chunk generate on a regular basis. Any player may generate one of these chunks as long as it has been at least X time since one of that type was last generated.

Omni - 24 hours, size 5-10

## <a name='warp-drive'/> Warp drive

A player may at any time spend n points to receive a Warp Core (where n is the day of the month/3 rounded up). A Warp Core is a quantity which may be spent to traverse space. At any time, a player may spend one Warp Core, which allows them to modify their sector position as they desire up to four spaces (the amount of spaces being x + y, and effectively changing their X and Y quantities). Also, upon using a warp core, a player may spend 1 point to move 8 spaces instead, known as “Overdriving”.

