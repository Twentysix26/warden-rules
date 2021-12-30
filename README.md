# Warden rules
This repository contains a collection of vetted rules to be used with [Defender](https://github.com/Twentysix26/x26-Cogs/)'s [Warden module](https://github.com/Twentysix26/x26-Cogs/wiki/Warden).
Some can be used as-is, some will require adjustments for them to work with your server structure / workflow and some will be generic rules that showcase the more complex features of Warden.
**It is expected from you that you have a solid grasp of how Defender works and understand a rule's logic before adding it to your server**.
Never add a Warden rule before personally vetting its code.

## Contributions

Contributions are welcome, with a few caveats
1. Your rule should be useful for a larger audience and not overly tailored to your community. Replace any ID with obvious placeholders, e.g. <USER_ID> <ROLE_ID>
2. Your rule should target only rank 2 or below for anything other than monitoring purposes
3. Comments, while not necessary, are welcome for particularly complex logic
4. If your logic spans over multiple rules, name them accordingly. E.g. dehoister-1, dehoister-2

## The rules

| Name | Description |
| --- | --- |
| [dehoister-1](/rules/dehoister-1.yml) | An event-based / periodic rule that renames people who's name starts with an exclamation mark for hoisting purposes |
| [dehoister-2](/rules/dehoister-2.yml) | Resets the nickname of people who are no longer hoisting |
| [new-user-1-attachments](/rules/new-user-1-attachments.yml) | Removes messages containing attachments from new users |
| [new-user-2-urls](/rules/new-user-2-urls.yml) | Removes messages containing clickable urls from new users |
| [new-user-3-mute](/rules/new-user-3-mute.yml) | Mute the user if they're spamming attachments and/or urls |
| [nitro-scam](/rules/nitro-scam.yml) | A non-blacklist based approach to counter common nitro / steam scams bots |
