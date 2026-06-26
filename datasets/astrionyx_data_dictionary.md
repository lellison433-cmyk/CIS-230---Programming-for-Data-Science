# The Astrionyx Alien Population Dataset

The **Astrionyx Alien Population** dataset contains biological, environmental, and demographic information collected from aliens living on the fictional planet **Astrionyx**.

The dataset was created as part of a fictional planetary census to better understand the characteristics, abilities, occupations, and habitats of the alien population.

It is designed for learning:

- Data exploration
- Data visualization
- Data wrangling
- SQL
- Introductory machine learning

---

# Variables

## Alien ID

- **Variable:** `alien_id`
- **Type:** Categorical Identifier

Unique identifier assigned to each alien.

- Each value is unique.
- Used only to identify individual aliens.
- Should not be used as a predictor in data analysis or machine learning.

---

## Name

- **Variable:** `name`
- **Type:** Nominal Categorical

The alien's given name.

- Used for identification only.

---

## Species

- **Variable:** `species`
- **Type:** Nominal Categorical

The biological species of the alien.

Possible values:

- Luminar
- Crystalian
- Nebulon
- Gravitar
- Aquari

Different species have different biological characteristics.

---

## Region

- **Variable:** `region`
- **Type:** Nominal Categorical

The region of Astrionyx where the alien lives.

Possible values:

- Crystal Forest
- Floating Islands
- Lava Basin
- Ice Plains
- Northern Crater

Environmental conditions vary across regions and may influence other characteristics.

---

## Arrival Date

- **Variable:** `arrival_date`
- **Type:** Date/Time

The date the alien officially arrived in its current region during the planetary census period.

This variable can be used to:

- Analyze arrivals over time
- Create new features such as year or month
- Explore seasonal patterns
- Demonstrate working with date and time data in pandas

---

## Age

- **Variable:** `age_centuries`
- **Type:** Numerical

Age of the alien measured in centuries.

Example:

- `2.5 = 250 Earth years`

---

## Antenna Count

- **Variable:** `antenna_count`
- **Type:** Numerical (Discrete)

Number of antennae possessed by the alien.

Antennae are believed to assist with communication and environmental sensing.

---

## Crystal Energy Index

- **Variable:** `crystal_energy_index`
- **Type:** Numerical

Measures how efficiently an alien absorbs energy from the naturally occurring crystals found on Astrionyx.

Higher values indicate greater energy absorption efficiency.

Expected range:

- `0–100`

---

## Bioluminescence Level

- **Variable:** `bioluminescence_level`
- **Type:** Ordinal Categorical

Describes how brightly an alien naturally glows.

Order (lowest to highest):

1. Low
2. Medium
3. High

Higher levels generally correspond to longer glow durations.

---

## Glow Duration

- **Variable:** `glow_duration_minutes`
- **Type:** Numerical

Average number of minutes the alien can continuously emit bioluminescent light before needing to recharge.

---

## Telepathy Score

- **Variable:** `telepathy_score`
- **Type:** Numerical

Measures the strength of the alien's telepathic abilities.

Higher values indicate stronger telepathic communication.

Expected range:

- `0–100`

---

## Hover Height

- **Variable:** `hover_height_cm`
- **Type:** Numerical

Average height (in centimeters) the alien naturally hovers above the ground while at rest.

---

## Occupation

- **Variable:** `occupation`
- **Type:** Nominal Categorical

Primary occupation of the alien.

Possible values:

- Crystal Miner
- Research Scientist
- Planetary Guardian
- Explorer
- Merchant
- Farmer
