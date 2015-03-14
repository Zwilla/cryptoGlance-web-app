
    [ v2.0.2.753-nightly ]

    FEATURES
    ========
    - Added manual update check in Settings page

    ALGORITHMS
    ==========
    - [+Algorithm] Blake-256
    - [+Algorithm] Groestl
    - [+Algorithm] Jackpot
    - [+Algorithm] Lyra2RE
    - [+Algorithm] Neos-Blake
    - [+Algorithm] NeoScrypt
    - [+Algorithm] WHIRL
    - [+Algorithm] X17

    COINS
    =====
    - [+COIN] Burstcoin

    HOTFIXES
    ========
    - Fixed issue with pools not loading
    - Added round duration to CKPool
    - Fixed incorrect BTC Guild pool hashrate
    - Fixed incorrect BTC Guild worker count
    - Fixed issue with Bitcoin Affiliate Network saving an empty name/label

    KNOWN ISSUES
    ========
    - Miner Failover may report incorrect active pool
    - Wallets can take a long time to load
    - Sometimes Update does not work

---

    [ v2.0.2.742-nightly ]

    FEATURES
    ========
    - Added New Zealand Dollar as a Fiat option in wallets
    - Added current FIAT price of a coin

    COINS
    =====
    - [+COIN] DogeCoin Dark

    POOLS
    =====
    - [+POOL] BitcoinCZ aka Slush
    - [+POOL] AntPool
    - [+POOL] BitMinter

    HOTFIXES
    ========
    - Removed useless BTC column when looking at a BTC wallet

---

    [ v2.0.2.731-nightly ]

    POOLS
    =====
    - [+POOL] NiceHash/WestHash

    HOTFIXES
    ========
    - MPOS network hash x1000h too high
    - Updated cgminer Reject warning priority

---

    [ v2.0.2.693-nightly ]

    POOLS
    =====
    - [+POOL] P2Pool

---

    [ v2.0.2 ]

    FEATURES
    ========
    - If rejected shares are greater than accepted shares, rig status appears red (requires attention)

    HOTFIXES
    ========
    - Windows App Update alert - This is a critical update for windows users who have external access enabled (eg web browser)
    - Fixed issue where Active Pool was sometimes displaying as "--"
    - Fixed login screen alerts on first login + login failure

---

    [ v2.0.1 ]

    HOTFIXES
    ========
    - Fixed issue with rig settings when upgrading v1 to v2
    - Added more data to the Eligius pool panel

---

    [ v2.0 ]

    FEATURES
    ========
    - Total Hashrates are now categorized by Rig Algorithms used
    - Enable/Disable Total Hashrate via Tools dropdown
    - New ability to edit Rigs and Pools
    - Re-amped Rig summary and device details (percentages, etc)
    - New Rig Details - Cleaner interface
    - Ability to drag+drop pool priority for a rig
    - Auto-Restart on BITMAIN asic failure (chain contains "x" instead of "0")
    - Rig devices have two more types of details showing:
    BITMAIN Asic fan speed (fan 1, fan 2, fan 3, etc)
    BITMAIN Asic temperatures (temperature 1, temperature 2, temperature 3, etc)
    - Rigs have a new option for Algorithm
    - Rigs Algorithm is auto-set when using sgMiner v5+
    - Ability to reset rig stats
    - Ability to reset rig stats on pool change
    - New FIAT conversions for most coins (Thanks to FunkyC: https://bitcoinindex.es/)
    - New debug command to see raw miner data: CTRL + D

    POOLS
    =====
    - [+POOL] Bitcoin Affiliate Network (http://mining.bitcoinaffiliatenetwork.com)
    - [+POOL] CkPool
    - [+POOL] Eligius
    - [+POOL] MagicPool
    - [+POOL] Multipool.Us
    - [+POOL] NOMP

    COINS
    =====
    - [+COIN] NeosCoin
    - [+COIN] ReddCoin
    - [+COIN] XPY - PayCoin | Note: Using ZenCloud or PayBase address may display balance of 0

    HOTFIXES
    ========
    - Rewrote all Wallet handling + UI Updates
    - If rig update time > 3 seconds, Rig summary would take an extended amount of time to appear
    - Updated Rigs Pool page. Usability was greatly improved. Added ability to enable/disable/add/edit/remove pools.
    - Device settings attempt to save. Mainly a GPU feature as frequencies for asics are almost impossible to do remotely.
    - If no frequency is found for a device, it displays "Unknown" and is not changeable.
    - Fixed issue with API calls when connection to a pool fails.
    - Bumped up code timeout to 2 minutes. This addresses API calls from pools and wallets
    - Updated Toast messages to make notices easier to read
    - Settings Page - clicking App Updates red/green button does not work
    - Changelog ICON changed
    - Navigation dropdowns would close while using elements inside it.
    - [POOL] MPOS network hashrate was incorrect. API returns deca instead of hecto

---

    [ v1.1.0 ]

    FEATURES
    ========
    - New Auto-Updater functionality! Keep on top of the latest features and fixes that we add.
    - New "Release", "Beta", "Nightly" options for the cG version stability you choose
    - Configurable Hardware Error warnings
    - Added more update time interval options
    - For first-time/fresh-install users, more alerts appear to help with setup
    - [+POOL] Eclipse MC (https://eclipsemc.com)
    - [+POOL] SimpleCoin
    - [+COIN] ContinuumCoin (CTM) (http://continuumcoin.com)

    HOTFIXES
    ========
    - Hardware Errors preference/value not set on first load
    - Fixed hashrate inconsistency with API
    - Resolved user_data folder not being found in certain cases
    - Improved session performance
    - Decimal place rounding for cgminer accepted/rejected
    - Active navbar link display states
    - Github repo URL in Update Available alert was incorrect

---

/*end CHANGELOG.md*