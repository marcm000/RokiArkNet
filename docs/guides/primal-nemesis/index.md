# Primal Nemesis

!!! note "Baseline Reference"
    All testing and stat values in this guide are based on **Level 150 creatures with unboosted stats**. Scaling will vary on boosted servers or higher-level wilds. This guide assumes a working understanding of basic ARK mechanics, taming, and general gameplay progression.

---

## Tier List

Click any tier to jump to its section.

<div style="overflow-x:auto">
<svg width="100%" viewBox="0 0 680 720" xmlns="http://www.w3.org/2000/svg" style="font-family:inherit">
  <defs>
    <marker id="arr" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M2 1L8 5L2 9" fill="none" stroke="#ff6a00" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
    </marker>
  </defs>

  <!-- Alpha -->
  <a href="#alpha"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="40" y="20" width="120" height="38" rx="8" fill="#1a3a2a" stroke="#ff6a00" stroke-width="1"/>
    <text x="100" y="39" text-anchor="middle" dominant-baseline="central" fill="#ff6a00" font-size="14" font-weight="500">Alpha</text>
  </g></a>
  <line x1="100" y1="58" x2="100" y2="78" stroke="#ff6a00" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Alpha Skeletal -->
  <a href="#alpha-skeletal"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="40" y="78" width="160" height="38" rx="8" fill="#1a3a2a" stroke="#ff6a00" stroke-width="1"/>
    <text x="120" y="97" text-anchor="middle" dominant-baseline="central" fill="#ff6a00" font-size="14" font-weight="500">Alpha Skeletal</text>
  </g></a>
  <line x1="120" y1="116" x2="120" y2="136" stroke="#ff6a00" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Apex -->
  <a href="#apex"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="60" y="136" width="120" height="38" rx="8" fill="#1a2a3a" stroke="#4a9eff" stroke-width="1"/>
    <text x="120" y="155" text-anchor="middle" dominant-baseline="central" fill="#4a9eff" font-size="14" font-weight="500">Apex</text>
  </g></a>
  <line x1="120" y1="174" x2="120" y2="194" stroke="#4a9eff" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Apex Skeletal -->
  <a href="#apex-skeletal"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="60" y="194" width="160" height="38" rx="8" fill="#1a2a3a" stroke="#4a9eff" stroke-width="1"/>
    <text x="140" y="213" text-anchor="middle" dominant-baseline="central" fill="#4a9eff" font-size="14" font-weight="500">Apex Skeletal</text>
  </g></a>

  <!-- Fan to elementals -->
  <line x1="140" y1="232" x2="140" y2="252" stroke="#888" stroke-width="0.5"/>
  <line x1="140" y1="252" x2="560" y2="252" stroke="#888" stroke-width="0.5"/>
  <line x1="140" y1="252" x2="80" y2="252" stroke="#888" stroke-width="0.5"/>

  <!-- Elemental nodes -->
  <!-- Storm -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="80" y1="252" x2="80" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="42" y="270" width="76" height="34" rx="8" fill="#2a2a3a" stroke="#9a7aff" stroke-width="1"/>
    <text x="80" y="287" text-anchor="middle" dominant-baseline="central" fill="#9a7aff" font-size="12" font-weight="500">Storm</text>
  </g></a>
  <!-- Volcanic -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="180" y1="252" x2="180" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="138" y="270" width="84" height="34" rx="8" fill="#2a2a3a" stroke="#ff6a00" stroke-width="1"/>
    <text x="180" y="287" text-anchor="middle" dominant-baseline="central" fill="#ff6a00" font-size="12" font-weight="500">Volcanic</text>
  </g></a>
  <!-- Frost -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="270" y1="252" x2="270" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="232" y="270" width="76" height="34" rx="8" fill="#2a2a3a" stroke="#4a9eff" stroke-width="1"/>
    <text x="270" y="287" text-anchor="middle" dominant-baseline="central" fill="#4a9eff" font-size="12" font-weight="500">Frost</text>
  </g></a>
  <!-- Nature -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="360" y1="252" x2="360" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="318" y="270" width="84" height="34" rx="8" fill="#2a2a3a" stroke="#4aff7a" stroke-width="1"/>
    <text x="360" y="287" text-anchor="middle" dominant-baseline="central" fill="#4aff7a" font-size="12" font-weight="500">Nature</text>
  </g></a>
  <!-- Earth -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="460" y1="252" x2="460" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="418" y="270" width="84" height="34" rx="8" fill="#2a2a3a" stroke="#c8a04a" stroke-width="1"/>
    <text x="460" y="287" text-anchor="middle" dominant-baseline="central" fill="#c8a04a" font-size="12" font-weight="500">Earth</text>
  </g></a>
  <!-- Water -->
  <a href="#storm--volcanic--frost--nature--earth--water"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <line x1="560" y1="252" x2="560" y2="270" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>
    <rect x="518" y="270" width="84" height="34" rx="8" fill="#2a2a3a" stroke="#4acfff" stroke-width="1"/>
    <text x="560" y="287" text-anchor="middle" dominant-baseline="central" fill="#4acfff" font-size="12" font-weight="500">Water</text>
  </g></a>

  <!-- Converge to Plasma | Ghost -->
  <line x1="80" y1="304" x2="80" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="180" y1="304" x2="180" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="270" y1="304" x2="270" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="360" y1="304" x2="360" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="460" y1="304" x2="460" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="560" y1="304" x2="560" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="80" y1="334" x2="560" y2="334" stroke="#888" stroke-width="0.5"/>
  <line x1="320" y1="334" x2="320" y2="350" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Plasma | Ghost -->
  <a href="#plasma--ghost"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="220" y="350" width="90" height="34" rx="8" fill="#2a1a3a" stroke="#cf7aff" stroke-width="1"/>
    <text x="265" y="367" text-anchor="middle" dominant-baseline="central" fill="#cf7aff" font-size="12" font-weight="500">Plasma</text>
  </g></a>
  <a href="#plasma--ghost"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="320" y="350" width="90" height="34" rx="8" fill="#2a1a3a" stroke="#aaaaaa" stroke-width="1"/>
    <text x="365" y="367" text-anchor="middle" dominant-baseline="central" fill="#aaaaaa" font-size="12" font-weight="500">Ghost</text>
  </g></a>

  <!-- Converge to Plague -->
  <line x1="265" y1="384" x2="265" y2="404" stroke="#888" stroke-width="0.5"/>
  <line x1="365" y1="384" x2="365" y2="404" stroke="#888" stroke-width="0.5"/>
  <line x1="265" y1="404" x2="365" y2="404" stroke="#888" stroke-width="0.5"/>
  <line x1="315" y1="404" x2="315" y2="418" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Plague -->
  <a href="#plague"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="235" y="418" width="160" height="38" rx="8" fill="#3a1a1a" stroke="#ff4a4a" stroke-width="1"/>
    <text x="315" y="437" text-anchor="middle" dominant-baseline="central" fill="#ff4a4a" font-size="14" font-weight="500">Plague</text>
  </g></a>
  <line x1="315" y1="456" x2="315" y2="476" stroke="#ff4a4a" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Bionic -->
  <a href="#bionic"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="235" y="476" width="160" height="38" rx="8" fill="#1a2a3a" stroke="#4acfff" stroke-width="1.5"/>
    <text x="315" y="495" text-anchor="middle" dominant-baseline="central" fill="#4acfff" font-size="14" font-weight="500">Bionic</text>
  </g></a>
  <line x1="315" y1="514" x2="315" y2="534" stroke="#4acfff" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Demonic | Celestial -->
  <a href="#demonic--celestial"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="180" y="534" width="110" height="38" rx="8" fill="#2a1a2a" stroke="#ff4aaa" stroke-width="1"/>
    <text x="235" y="553" text-anchor="middle" dominant-baseline="central" fill="#ff4aaa" font-size="13" font-weight="500">Demonic</text>
  </g></a>
  <a href="#demonic--celestial"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="340" y="534" width="110" height="38" rx="8" fill="#1a1a2a" stroke="#ffffaa" stroke-width="1"/>
    <text x="395" y="553" text-anchor="middle" dominant-baseline="central" fill="#ffffaa" font-size="13" font-weight="500">Celestial</text>
  </g></a>

  <!-- Converge to Godly -->
  <line x1="235" y1="572" x2="235" y2="592" stroke="#888" stroke-width="0.5"/>
  <line x1="395" y1="572" x2="395" y2="592" stroke="#888" stroke-width="0.5"/>
  <line x1="235" y1="592" x2="395" y2="592" stroke="#888" stroke-width="0.5"/>
  <line x1="315" y1="592" x2="315" y2="606" stroke="#888" stroke-width="0.5" marker-end="url(#arr)"/>

  <!-- Godly -->
  <a href="#godly"><g style="cursor:pointer" onmouseover="this.querySelector('rect').style.filter='brightness(1.3)'" onmouseout="this.querySelector('rect').style.filter=''">
    <rect x="215" y="606" width="200" height="44" rx="8" fill="#2a2a1a" stroke="#ffdd00" stroke-width="2"/>
    <text x="315" y="628" text-anchor="middle" dominant-baseline="central" fill="#ffdd00" font-size="16" font-weight="500">Godly</text>
  </g></a>

  <!-- Water non-progression note -->
  <rect x="420" y="610" width="220" height="50" rx="8" fill="none" stroke="#4acfff" stroke-width="0.5" stroke-dasharray="4 3"/>
  <text x="530" y="628" text-anchor="middle" fill="#4acfff" font-size="11">Water (non-progression)</text>
  <text x="530" y="644" text-anchor="middle" fill="#888" font-size="11">Pacific = Alpha | Atlantic = Apex</text>
</svg>
</div>

---

## Getting Started

Focus on building a core crafting base, preparing for early hunts, and securing the resources required for future tiers.

### Core Crafting Structures

**Primal Forge**

- Smelts metal and alloys
- Crafts advanced ingots such as Copper and Tin from metal nodes
- Also used to craft Zinc Ore

**Primal Cauldron**

- Used for brewing custom kibbles, potions, dyes, and consumables

**Primal Bench**

- Primary station for modded gear, kibble, and boss item crafting

### Loot System

All loot in Primal Nemesis rolls randomized stat bonuses — armor, weapons, tools, saddles, rings, and dino totems.

Loot sources:

- Loot Bosses
- Quests
- Wild dino kills

Higher tiers provide more stat slots and stronger values. Loot quality ranges from Common through Ancient.

---

## Alpha

*Section coming soon.*

---

## Alpha Skeletal

*Section coming soon.*

---

## Apex

*Section coming soon.*

---

## Apex Skeletal

*Section coming soon.*

---

## Storm | Volcanic | Frost | Nature | Earth | Water

*Section coming soon.*

---

## Plasma | Ghost

*Section coming soon.*

---

## Plague

*Section coming soon.*

---

## Bionic

*Section coming soon.*

---

## Demonic | Celestial

*Section coming soon.*

---

## Godly

*Section coming soon.*
