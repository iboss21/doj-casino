# W.I.P [ qb-casino ] W.I.P

### included
- Casino IPL
- Luckywheel
- Slot Machines
- Inside Track
- Bank only
- Casino Ui
- Target info (at bottom)

### Coming Soon
- Chip Casino
- Blackjack
- Roulette

## Casino Entrance
preview:
https://streamable.com/jem98k

## Casino Luckywheel
preview:
https://streamable.com/ucv48w

## Casino Slot Machines
preview:
https://streamable.com/5xwkki

## Casino Inside Track
preview:
https://streamable.com/m5eykj

## Casino Blackjack
preview:
(coming soon)

## Casino Roulette
preview:
(coming soon)

## Casino Ui
- nh-context preview:

![General](https://i.imgur.com/hDbTfbt.png)

- textUi preview:

![General](https://i.imgur.com/ywWq9sT.png)


- casinoUi preview:

![General](https://i.imgur.com/9fPvYyv.png)

## qb-target info
```
-- Lucky wheel
exports['qb-target']:AddCircleZone("LuckyWheel", vector3(949.391, 44.72, 71.638), 2.0, {
    name="LuckyWheel",
    heading=160,
    debugPoly=false,
    useZ=true,
    }, {
        options = {
            {
                event = "luckywheel:client:startWheel",
                icon = "fas fa-sync-alt",
                label = "Try Your Luck",
            },
        },
    distance = 2.0 
})

-- Horse Bets
exports['qb-target']:AddCircleZone("Betting", vector3(956.121,70.185,70.433), 1.0, {
    name="Betting",
    heading=160,
    debugPoly=false,
    useZ=true,
}, {
    options = {
        {
            event = "QBCore:client:openInsideTrack",
            icon = "fas fa-coins",
            label = "Start Betting",
        },
    },
    distance = 3.0 
})

-- Casino Shop
exports['qb-target']:AddTargetModel(`U_F_M_CasinoCash_01`, {
	options = {
        { 
            event = "doj:casinoChipMenu",
            icon = "fas fa-exchange-alt",
            label = "Exchange Casino Chips", 
        },
        {
            event = "qb-casino:client:openCasinoChips",
            icon = "fas fa-coins",
            label = "Purchase Casino Chips", 
        },
        {
            event = "qb-casino:client:openCasinoMembersips", 
            icon = "fas fa-id-card",
            label = "Purchase Casino Memberships", 
        },
	},
	distance = 3.0 
})
```


