System Parameters
1. Destination Geography: Coastal/Cayes, Inland/Maya Heartland, or Southern Rainforest.. 
3. Weather Profiles: Clear and Sunny, Rainy/Tropical Squall, or Severe Weather Advisory.
4. Budget Tiers:
	• Tier 1 (Backpacker / Economy): Less than 75.00 USD per day.

	• Tier 2 (Explorer / Moderate): 75.00 to 250.00 USD per day.

	• Tier 3 (Luxury / Private Tour): More than 250.00 USD per day.

6. Activity Interest: Adventure (A), Culture (C), or Relaxation (R).
Rule Summary
• Severe Weather: Stops outdoor and water tours immediately and gives safety instructions.

• Coastal Logic: Picks snorkeling or island cycling if sunny. Switches to indoor drumming lessons if rainy.

• Inland Logic: Suggests cave tours or Mayan ruins depending on the weather and budget.

• Southern Logic: Sets up eco-lodge canopy walks for luxury budget profiles.

Technical Features

• Input Validation: Prevents the program from crashing or looping infinitely if you type an incorrect menu choice or a negative number.

• Case-Insensitive Check: Accepts lowercase and uppercase input letters (like a, A, c, C, r, R).

• Clean Architecture: Routes major choices through switch statements to keep the programming logic highly organized.

Test Cases Verification Matrix

Test ID | Category | Destination | Weather | Budget | Activity | Expected Recommendation | Verification Criteria

TC-01 | Normal | 1 (Coastal) | 1 (Sunny) | 150.00 | A | Hol Chan Snorkel / Dive Tour | Validates moderate budget marine adventure logic.

TC-02 | Normal | 2 (Inland) | 1 (Sunny) | 50.00 | C | Xunantunich Maya Ruins Tour | Validates backpacker cultural heritage recommendations.

TC-03 | Boundary | 2 (Inland) | 1 (Sunny) | 75.00 | A | ATM Cave Expedition | Boundary test on exact lower limit of Moderate budget tier (75.00).

TC-04 | Boundary | 1 (Coastal) | 1 (Sunny) | 250.00 | A | Hol Chan / Private Charter | Boundary test on exact upper limit of Moderate tier (250.00).

TC-05 | Logic / Override | 1 (Coastal) | 3 (Severe) | 600.00 | A | Marine Activity Lockdown / Indoor Cultural Workshop | Validates that severe weather overrides luxury marine selections.

TC-06 | Invalid Input | 9 -> 2 | 4 -> 2 | -20 -> 85 | Z -> R | Barton Creek Canoe or Inland Spa | Validates complete defensive input recovery for all four fields.

How to Run the Code

Compilation Command:

g++ main.cpp -o BelizeTravelAdvisor

Execution Command:

./BelizeTravelAdvisor



Sample Run Output

================================================================

BELIZE TRAVEL & ACTIVITY ADVISOR SYSTEM

Ministry of Tourism & Civil Aviation

Enter Lead Traveler Name: Carlos Mendoza

Select Destination Zone:

Coastal / Cayes (Ambergris Caye, Caye Caulker, Placencia)

Inland Heartland (Cayo District, San Ignacio, Pine Ridge)

Southern Rainforest (Stann Creek, Toledo, Hopkins)

Select Destination [1-3]: 1

Current Weather Forecast:

Clear, Sunny Tropical

Intermittent Rain / Cloud Cover

Severe Weather / Small Craft Advisory

Select Weather Condition [1-3]: 1

Enter Expected Daily Budget per Person ($ USD): 150.00

Primary Activity Interest:

[A] Adventure & Marine Expeditions

[C] Cultural Tours & Culinary Workshops

[R] Relaxation & Coastal Leisure

Select Activity [A/C/R]: A

Generating tailored travel advisory... Done.

================================================================

CURATED BELIZE TRAVEL ITINERARY

Traveler Name    : Carlos Mendoza

Destination      : Coastal / Cayes

Weather Profile  : Clear & Sunny Tropical

Budget Tier      : Tier 2 (Explorer / Moderate) [$150.00 USD/day]

Selected Focus   : Adventure & Eco-Trekking

RECOMMENDED EXPERIENCE:

Hol Chan Marine Reserve Snorkeling / Scuba Dive

Take an authorized local boat charter out to the barrier reef system.

RECOMMENDED GEAR CHECKLIST:

• Reef-safe biodegradable mineral sunscreen, UV rash guard, swim fins.

LOGISTICAL ADVISORY:

• Water taxi transit running on regular schedule.

• Book authorized tour guides carrying valid BTB (Belize Tourism Board) licensing.

================================================================

Enjoy your travels in Belize - "Mother Nature's Best Kept Secret"!

elize Tourism Board) licensing.

================================================================

Enjoy your travels in Belize - "Mother Nature's Best Kept Secret"!

```


