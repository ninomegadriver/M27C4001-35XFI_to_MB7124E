# M27C4001-35XFI to MB7124E Adapter

I know that it sounds really strange to use a 512kb eeprom as a 512bytes bipolar PROM, however I came across this unusual issue while repairing a Robocop arcade PCB.


The bipolar prom MB7124E was missing on the ROM board at 12A and was causing the game not to run correctly. Althought I could still find some of these chips to sell on ebay, the costs to ship to here, Brazil, was not charming at all. Also, building a programmer only to burn one of these made me feel very lazy.


One big issue on trying to replace this prom with another solution was the very fast access time, the MB7124E have an access time of just 35ns. Hopefully I was able to find a matching M27C4001 with the same access time ("35XFI" variant) for a reasonable price arround here.


Ok, so I burn the small 512 bytes rom into a huge 512kb eeprom, made a simple adapter et voila: game is up and running again!

