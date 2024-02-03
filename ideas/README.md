# Ideas

## Intro

Welcome to the Google Summer of Code ideas repository!
Here you can propose new ideas to participate to this fantastic event 
and contribute to the nix/nixOS/nixpkgs community ecosystem!

Below you will find all instructions to propose your ideas, so don't be shy
to contribute!

Summerily yours,
the repo maintainers.

## Submission fields explanation

### ID
The ID is composed by the current year and an incremental 4 digit integer
assigned by one of the repo maintainers and will also be the directory name
that will contain all the artifacts for that idea.

### Title
The title should be clear, concise and inspirative.

It should also be prefixed by a categorey chosen among:
    * nix
    * nixpkgs
    * nixos
Depending on which area of the ecosystem more closely fits your idea.

### Author
Just the author's github handle.

### Proposed Menthor
If you're in contact with a member of the nix community who's interested in
helping you as your direct menthor, you can mention the github handle here so
that the repo maintainers wil be added to the conversation in the PR.

### Effort
This is the "size" of the effort level of the idea. It should be one of:
    * SMALL
    * MEDIUM
    * LARGE

### Difficulty
This is how "hard" it is at a technical level to implement the idea. It can be:
    * EASY
    * MEDIUM
    * HARD
### Overview/Abstract
This is a short description of the idea. Try to stay within the limit of 400
characters. Think of this as your "elevator pitch".
### Description
Here you can add all the nitty gritty details of the idea. Feel free to add
anything that you think is relevant for the staff to understand and evaluate
your idea.
### Linkography
Just the link to the relevant documentation and/or description you wrote
above.

## Idea Template

This would be a PR aimed at creating a README.md file with the content below
in the directory [ideas/2024/0000](./ideas/2024/0000).

### Metadata

**ID**: [2024/0000](./ideas/2024/0000)

**Title**: [nixpkgs] My idea to nixify the world!

**Author**: @your-github-handle-here

**Proposed Menthor**: [optional] @your-menthor-github-handle-here

**Effort**: SMALL/MEDIUM/LARGE

**Difficulty**: EASY/MEDIUM/HARD

**Overview/Abstract**: Description in less than 400 characters (5 lines, 80 chars).

### Description

Detailed description of the project.

### Linkography

* [Link1](https://localhost/THIS IS CLEARLY A BROKEN LINK): Link1 explanation
* [Link2](https://localhost/THIS IS CLEARLY A BROKEN LINK): Link2 explanation
* [Link3](https://localhost/THIS IS CLEARLY A BROKEN LINK): Link3 explanation

## Idea Example

This is an example of a real idea that was submitted https://github.com/NixOS/GSoC2024/pull/3

### Metadata

**ID**: [2024/0001](./ideas/2024/0001)

**Title**: [nixpkgs] nixpkgs library networking functions

**Author**: FREE

**Proposed Menthor**: @Janik-Haag

**Effort**: SMALL

**Difficulty**: MEDIUM

**Overview/Abstract**: Add a set of built-in networking functions to
`nixpkgs.lib` to improve contributors UX.

### Description

Many things in NixOS use the Internet Protocol and other network related
technologies, thus a lot of modules and service have to deal with them.
Currently this is mostly done just passing strings as arguments, but it would
be a lot more convenient to have things like `lib.types.ipv6`, `lib.types.ipv4`
and other functions to for example convert between cidr notation and the bit
representation of netmasks. This would not just be useful for NixOS it self but
also for its users since a lot of folks use it to power network appliances and
build infrastructure on top of it.

**Skills required/preferred**:
Some prior networking knowledge would be useful but not required.
Prior knowledge of the nix programming language is not required.
Anyone new-comer wanting to pick this up should easily be able to complete a
nix tutorial like [a tour of Nix](https://nixcloud.io/tour/?id=introduction/nix)
in one or two afternoons and be good to go.

**Prior efforts**:
There was some prior efforts in
[nixpkgs#258250](https://github.com/NixOS/nixpkgs/pull/258250) but it is stuck
for a few months now and also only adds function for legacy ip, it's also quite
bare bones and we might want some more advanced things like a function to check
if a ip matches a given subnet.

### Linkography

* [A tour of Nix](https://nixcloud.io/tour/?id=introduction/nix)
* [nixpkgs#258250](https://github.com/NixOS/nixpkgs/pull/258250)