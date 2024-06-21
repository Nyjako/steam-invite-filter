# steam-invite-filter

> [!NOTE]
> This program is a work in progress and is not yet functional.

## Overview

steam-invite-filter is a Rust-based program designed to automatically scan, decline, and block unwanted Steam friend invites based on customizable criteria.

## Features

<!-- - Scan incoming Steam friend invites.
- Automatically decline invites that meet specified criteria.
- Optionally block users based on defined rules. -->
**None for now**

## Planned Features

- **Scanning Friend Invites**
  - Continuously monitor incoming Steam friend invites.

- **Decline Unwanted Invites**
  - Automatically decline invites based on:
    - Account level
    - Hours played in the last two weeks (flagging accounts with impossibly high playtime as potential bots)
    - Profile privacy settings
    - Number of friends
    - Inventory contents
    - SteamRep checks
    - Recently played games (declining invites from users who have not played the same games recently)

- **Optionally Block Users**
  - Provide an option to automatically block users who send unwanted invites.

- **Decline Group Invites**
  - Automatically decline group invites because they are just anoying.

- **Decline Trade Offers**
  - Automatically decline empty trade offers.

## Development

If you want to contribute or experiment with the code, you can clone the repository and build it locally:
```bash
git clone https://github.com/yourusername/steam-invite-filter.git
cd steam-invite-filter
cargo build
```

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests.