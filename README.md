# crypto_challenge
Repository for the Philly BSides yearly crypto challenges. 

## Hints
- For all challenge answers are lowercase.
- Remember to remove new lines when checking checksums!

## Challenges
| Year    | Link                | Description |
|---------|---------------------|-------------|
| 2017    |[Innagural](challenges/2017.md)          | Take a stab at the first even appearance of Robo Ben Franklin's Crypto challenge. |
| 2018/19 |[Pirate Ben Returns](challenges/2019.md) | Robo Ben is back with his pirate army trying to foil mutiny! |

## Hints
If you're having trouble, here are some tips to ensure you're calculating the checksum the same way we did:

- It's an MD5 checksum
- The answers are all lower case

On *nix/OSX systems, you should get the correct checksum with:

```
md5 -s "YOUR_ANSWER"
```

If you'd rather just use an online tool, [this should suffice](https://www.md5hashgenerator.com/)
