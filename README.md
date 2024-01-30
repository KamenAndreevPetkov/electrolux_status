# electrolux_status
This is my local copy of the already installed code of Home Assistant HACS integration for Electrolux devices.
Apparently, the original author got threatened by Electrolux with legal actions - similar to https://www.youtube.com/watch?v=ayG7o74kdbc, I guess.
While the original creator did not share any details, it seems very similar in all spaects.

The text below is taken over from original developer - it was used as description in Home Assistant.

# ⚠️ Important Notice: API Changes and Library Discontinuation

Attention: The APIs provided by Electrolux have undergone significant changes, and the library "pyelectroluxconnect" that this project previously relied on has been discontinued.

I am currently working on a migration plan to adapt to the new APIs. Please be aware that the current state may be affected, and I recommend users to regularly monitor this repository for updates.

If you are interested in contributing to the project and assisting with the integration of the new APIs, your contributions are more than welcome! Feel free to fork the repository, make changes, and submit a pull request.

Thank you for your understanding and support.

# Details

This is an integration to Home Assistant to communicate with the Electrolux Connectivity Platform (ECP), Electrolux owned brands, like: Electrolux, AEG, Frigidaire, Husqvarna.

Tested with Electrolux and AEG washer-dryer, but probably could be used with some internet connected ovens, diswashers, fridges, airconditioners.
Supported and tested devices

- ELECTROLUX EDH803BEWA - UltimateCare 800
- ELECTROLUX EW9H283BY - PerfectCare 900
- ELECTROLUX EWF1041ZDWA - UltimateCare 900 AutoDose
- ELECTROLUX EEM69410W - MaxiFlex 700
- ELECTROLUX EOD6P77WZ - SteamBake 600
- ELECTROLUX KODDP77WX - SteamBake 600
- ELECTROLUX EHE6799SA - 609L UltimateTaste 900
- ELECTROLUX EW9H869E9 - PerfectCare 900 Dryer
- ELECTROLUX EW9H188SPC - PerfectCare 900 Dryer
- ELECTROLUX EW8F8669Q8 - PerfectCare 800 Washer
- ELECTROLUX EW9F149SP - PerfectCare 900 Washer
- ELECTROLUX KEGB9300W - Dishwasher
- ELECTROLUX EEG69410W - Dishwasher
- AEG L6FBG841CA - 6000 Series Autodose
- AEG L7FENQ96 - 7000 Series ProSteam Autodose
- AEG L7FBE941Q - 7000 Series Prosense Autodose
- AEG L8FEC96QS - 8000 Series Ökomix Autodose
- AEG L9WBA61BC - 9000 Series ÖKOKombi DualSense SensiDry
- AEG BPE558370M - SteamBake 6000

# Prerequisites

All devices need configured and Alias set (otherwise the home assistant integration raises the authentication error) into following applications (depends on device type and region):

- My Electrolux Care/My AEG Care (EMEA region)
- Electrolux Kitchen/AEG Kitchen (EMEA region)
- Electrolux Life (APAC region)
- Electrolux Home+ (LATAM region)
- Electrolux Oven/Frigidaire 2.0 (NA region)

# Installation

    Click install.
    In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Electrolux status".
    Insert the Electrolux Care Application credentials

# Thanks

This integration uses the following Python Library:

    https://pypi.org/project/pyelectroluxconnect/

# Disclaimer

This Home Assistant integration was not made by Electrolux. It is not official, not developed, and not supported by Electrolux.
