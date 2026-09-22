# Quarterly Report — <Orchestrator> — <YYYY-Qn>

> Copy this file to `<YYYY-Qn>-<orchestrator>.md` in this `quarterly-reports/` folder, fill it in, and open a pull request. Filing rules: [§4.1–4.3, Quarterly Review and Runbook](../04-quarterly-review-and-runbook.md#41-community-reporting-and-disclosure). Quarterly cycle in the FIP: [FIP-0118 §2.2](https://github.com/filecoin-project/FIPs/blob/master/FIPS/fip-0118.md#22-quarterly-cycle).
>
> Fields marked *(from indexer)* are produced by the versioned reference indexer.

## 1. Orchestrator identification and rewards received

| Field | Value |
| :-- | :-- |
| Service Orchestrator name | *[enter name]* |
| Orchestrator wallet address | *[enter wallet address]* |
| Quarter covered | *[e.g. Q3 2026]* |
| Date submitted | *[enter date]* |
| Reference-indexer version used | *[enter version / commit]* |

## 2. Financial performance

### 2.1 FPV headline

| Field | Value |
| :-- | :-- |
| `FPV_i(Q)` — total quarterly Filecoin Pay Volume (on-chain) | *[enter amount]* |

### 2.2 Stablecoin component *(from indexer)*

| Field | Value |
| :-- | :-- |
| Admitted-stablecoin volume (USD at face value) | *(from indexer)* |

### 2.3 FIL conversion working, per pricing period *(from indexer)*

One row per qualifying print, up to `MAX_PRICE_PERIODS`.

| Pricing period (epoch range) | Print reference (fee-auction claim tx) | `lotUsd` | `claimFil` | Implied rate (`lotUsd`/`claimFil`, USD/FIL) | attoFIL settled | Floored USD |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| *(from indexer)* | *(from indexer)* |  |  |  |  |  |
| *(from indexer)* | *(from indexer)* |  |  |  |  |  |
| **FIL component (sum of floored USD across periods)** | *(from indexer)* |  |  |  |  |  |

### 2.4 Parameters in effect for Q *(from indexer)*

Printed here because `MIN_LOT(Q)` is derived off-chain and is stored neither on-chain nor in this repository.

| Parameter | Value |
| :-- | :-- |
| `MIN_LOT(Q)` (derived value used for Q) | *(from indexer)* |
| `MIN_LOT_FLOOR` | *(from indexer)* |
| `MIN_LOT_ALPHA` | *(from indexer)* |
| `BoundVolume(Q-1)` | *(from indexer)* |
| `FEE_RATE` | *(from indexer)* |
| `PRICE_BAND` | *(from indexer)* |
| `N(Q-1)` | *(from indexer)* |
| Admitted-stablecoin whitelist (in force for Q) | *(from indexer)* |
| Admitted Filecoin Pay contract addresses (as of Q) | *(from indexer)* |

### 2.5 FPV total *(from indexer; must match the bound value (PostVolume or VolumeCorrected) on-chain)*

| Field | Value |
| :-- | :-- |
| `FPV_i(Q)` total (atto-USD; stablecoin component plus FIL component) | *(from indexer)* |
| `FPV_i(Q)` total (USD, human-readable) | *(from indexer)* |
| `PostVolume` message reference (tx hash / link) this total must match the bound value (PostVolume or VolumeCorrected) | *(from indexer)* |

### 2.6 Booked revenue by customer segment

| Customer segment | Percent of booked revenue |
| :-- | :-- |
| *[segment]* | *[__%]* |
| *[segment]* | *[__%]* |
| *[segment]* | *[__%]* |
| *[segment]* | *[__%]* |

### 2.7 Pipeline and sales commentary

Standard public-company style disclosure.

| Field | Value |
| :-- | :-- |
| New pipeline generated this quarter | *[enter detail]* |
| Pipeline conversion / notable deals closed | *[enter detail]* |
| Forward-looking pipeline commentary | *[qualitative, non-binding]* |

## 3. Use of block rewards

| Field | Value |
| :-- | :-- |
| Total block rewards received this quarter | *[enter amount]* |
| On-chain disbursements | *[outbound transfers from the Orchestrator wallet — e.g. deal subsidies, integration payments]* |
| Data onboarded, active | *[bytes under active deals attributed to the service]* |
| Storage providers engaged | *[count of distinct SP actor IDs taking deals attributed to the service]* |

| Spend category | Amount / detail |
| :-- | :-- |
| *[category 1]* | *[enter detail]* |
| *[category 2]* | *[enter detail]* |
| *[category 3]* | *[enter detail]* |

## 4. Retrospective: what worked, what didn't, learnings

| Field | Value |
| :-- | :-- |
| What worked well this quarter | *[enter detail]* |
| What didn't work / challenges encountered | *[enter detail]* |
| Key learnings and takeaways | *[enter detail]* |
| Any other context (optional) | *[enter detail]* |

## 5. Next quarter outlook

| Field | Value |
| :-- | :-- |
| High-level plan / focus areas | *[enter detail]* |
| Anticipated changes to strategy, spend, or team | *[enter detail]* |

<free text>