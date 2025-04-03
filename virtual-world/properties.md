---
title: 'Properties & Spaces'
description: 'Property types, ownership, and management in the Hubzz virtual world'
---

import { Note, Tab, Tabs } from 'mintlify';

# Properties & Spaces

Within each zone in Hubzz, there are various types of properties and spaces that serve different purposes. This page explains how properties work, their various types, and how they can be managed.

## Building System & Space Types

Each zone sits on a 64×64 grid. Structures are made using stackable building blocks that create different types of functional spaces:

<Tabs>
  <Tab title="Space Types">
    *   **Event Venues (Green):** Specialized spaces for hosting events with streaming/AV modules. See [Event Venues](/event-system/venues).
    *   **Public Areas (Purple):** Open access for community engagement; potential billboard rentals.
    *   **Private Properties (Orange):** User-owned, sellable, customizable spaces.
    *   **Flex Spaces (Blue):** Zone-owner controlled, non-tradable spaces for exclusive/token-gated access.
  </Tab>
  <Tab title="Building Constraints">
    To ensure usability and performance:
    *   **Block Budget Formula**: Total Blocks = Floor Tiles × Height (Subject to Zone's Volumetric Allowance: Central 50k, Mid 40k, Outer 30k)
    *   **Minimum Height**: 2 blocks (for avatar navigation).
    *   **Minimum Floor Area**: 32 tiles (~8 users).
    *   **Minimum Width**: 3 tiles between walls.
    *   **Floor/Height Ratio**: Floor Tiles ≥ 8 × Height.
    *   **Capacity Calculation**: 1 user per 4 floor tiles.
    
    <Note>Wall height affects billboard potential vs. horizontal space.</Note>
  </Tab>
  <Tab title="Zone Capacity (Approximate)">
    Based on avg. 3 block height:
    *   **Central Zones**: ~4,167 users
    *   **Mid Zones**: ~3,333 users
    *   **Outer Zones**: ~2,500 users
  </Tab>
</Tabs>

## Property Types & Ownership

### Private Properties

Private properties (orange blocks) are user-owned, tradable spaces within zones:

*   **Ownership**: Can be purchased from zone owners (initially via Key Randomizer) and traded on the [Player Marketplace](/experience/dashboard#player-marketplace).
*   **Types**: Virtual Homes, Apartments, Condos, Townhomes, Commercial Spaces.
*   **Customization**: Owners can personalize their spaces within platform guidelines using [Furni](/experience/assets#digital-collectibles).
*   **Benefits**:
    *   Personalization and expression
    *   Potential value appreciation
    *   Rental income potential
    *   Community status signal

### Flex Spaces

Flex spaces (blue blocks) are special properties that function differently:

*   **Control**: Owned *exclusively* by the Zone Owner; cannot be traded/sold.
*   **Use Cases**: Ideal for exclusive/token-gated areas, in-world brand stores, community showcases.
*   **Booking**: Reserved via Hubzz event system (no ticketing needed).

### Public Areas

Public areas (purple blocks) are open-access spaces for community engagement:

*   **Access**: Open to all users.
*   **Purpose**: Community interaction, social gatherings, exploration. May host [Surprise Drops](/tokenomics/rewards).
*   **Monetization**: Potential billboard rentals for zone owners.

## Property Distribution & Management

### Key/Location Reveal Randomizer

*   **Mechanism**: Zone Admins can sell property "keys"; location revealed *after* purchase.
*   **Benefits**: Gamifies acquisition, ensures fairness, boosts secondary market value for desirable spots.

### On-Chain Property Management

*   **Ownership**: All properties recorded on-chain (NFTs) for transparency and true ownership.
*   **Revenue**: Zone Admins can implement Property Owner Association (POA) fees (optional recurring fees for property owners in their zone). Event revenue splits for events held in private properties can also be managed via smart contracts. 