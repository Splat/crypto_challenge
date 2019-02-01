# crypto_challenge
Repository for the Philly BSides yearly crypto challenges. 

## 2
![2019](2019_crypto.jpeg "2019")

Robo BennieF is back this year with his robot pirate army. He looks over the bow, as a white whale breaches the surface and with a blast of sea water, launches a book into the air. He wipes the liquid from his sensors to find a watterlogged copy of 20,000 Leagues grasped between his servos.
`aHR0cHM6Ly93d3cuZ3V0ZW5iZXJnLm9yZy9maWxlcy8xNjQvMTY0LWgvMTY0LWguaHRt`

1a. He glances over the soaking cover, it reads, "Twenty Thousand Leagues Under 0xAAA Sea by Jules Verne" `checksum: 8fc42c6ddf9966db3b09e84365034357`
2b. Opening the book, he finds an inscription: "Major André, ptIchVIIpa26l5w11 -RoboBenedict" What a treacherous message. 
`checksum: b2fdab230a2c39f3595a947861863cb7`

3c. With the previous clue deciphered, at the bottom of the page, he notices another note "Give me liberfy ir give me death" in the footer.  What a peculiar thing to write?
`checksum: 01b6e20344b68835c5ed1ddedf20d531`

4d. Quickly flipping through the pages, he discovers a note in the margin of a page: "Turn to the penultimate chapter and read about the 4 directions, where 17 bots ventured, through 24 islands for 46 nights and 47 days to find 66 barrels filled with robo-joint grease #71 in the resting place of Captain N." 
`checksum: dd76967b79afecfefcc8e2d9452b380f`

5e. Frustrated by these nonsensical messages, RoboBen shakes the book. It becomes unbound and he discovers the text `4d3c1a2b` inscribed into the spine.

### Final Flag
echo "FLAG_JAWN" | openssl ALGO_JAWN -a -A -k 5e -iv 00010203040506070809a0b0c0d0e0f -d

## 1
