# Suzuki Cappuccino EA11R Parts Cross Reference

## Car Specifications

### Fuel Economy
| Condition | L/100Km | US MPG | UK MPG | Distance | Range (US miles) |
|-----------|---------|--------|-----|----------|------------------|
| Urban cycle | 7.2 | 32.7 | 39.2 | 416Km / 259M | 258 | 
| Constant 90Km/h (56mph) | 5.4 | 43.5 | 52.3 | 555Km / 345M | 343 |
| Constant 120Km/h (75mph) | 7.7 | 30.5 | 36.7 | 389Km / 242M | 240 |

- **Fuel tank: 30L (7.9 US Gal, 6.6 UK Gal )**


### Fuel Requirements
| EURO RON (Research Octane Number) | US/CA AKI (anti-knock index) | MON (Motor Octane Number) | Petrol type |
|-----------------------------------|------------------------------|---------------------------|-------------|
| **Stock engine recommended => 90** | 85 | 80 | "Regular gasoline" in Japan |
| 91-92 | 87 | 82-83 | "Regular Gasoline/Petroleum" in Australia, New Zealand and the US |
| 92 | 88.5 | 85 | . |
| 95 | 91 | 87 | SP95 euro |
| 96 | 92 | 88 | . |
| **N2 and better compression => 98** | 94 | 90 | SP98 Euro |
| 100 | . | . | "Premium" gasoline in Japan |

**Notes:**
- Japan, UK and the Continent home market Cappos engines are identical, and require 90 RON fuel minimum, but ECU could have been modified and need 98 RON ones
- In the US remove 2 AKI in mountain area to compensate lack of oxygen for combustion

### Performance Stages

**NOTE**: Performance Stages are kind of bullshit, this guid is notional only and mosly applies to just my build.

|  .  |Stage 0 (Stock Boi)| Stage 1| Stage 2 | Stage 3 |
|-----|-------------------|--------|---------|---------|
| **Est HP** | 60B | 60+ | 80 | 100BHP (+40) |
| **Intake** | . | Free-Flowing intake. (Custom, HKS inspiried) | . | . |
| **Intercooler** | . | Intercooler Piping. (Custom) | Larger, better flowing Intercooler | . |
| **Turbo** | . | . | . | BIGGER |
| **Ignition** | . | Advance timing, Colder Range Spark Plugs. | . | Coil-On-Plug conversion |
| **Fuel** | . | 91 AKI | . | 295cc+ injectors, upraged fuel pump and FPR |
| **Internals** | . | . | . | K6A pistons, +2mm Head gasket |
| **Exhaust** | . | Cat Back (Fujitsubo Legalis K or similar) | . | . |
| **Brakes** | . | Braided lines and agressive pads. (Custom brake lines, ProjectMu Bspec pads) | . | . |
| **Suspension** | . | Coilovers, 15" wheels, sticky tires. (BCRacing coilover, JDM Integra Type-R wheels) | . | . | 
| **ECU** | . | . | Monster Sport N1 or KeiSport ECU (MegaSquirt2) | ECU N2 + bigger turbo | . |

### Performance Examples

| Mode | Torque | HP | 
|------|--------|----|
|**Stock:** | 85Nm | 63 BHP |
|**5w30 + Iridium spark plugs @ 0.8 bar boost:** | 89.5 Nm | 75.1 |

#### Spicy Performance Build Examples
- **Spicy Rebuild**:  HF4 turbo, K6A forged pistons, => 320cc injectors, free flowing intake, coil on plugs conversion, and standalone ecu around. (150 bhp @ 19psi boost )
- **Spicy**: Stock block and head, N2 ECU w/ 380cc injectors, Modified Ht07 turbo, 130l fuel pump and FPR upgrade, +2mm head gasket, Boost controller, intercooler upgrade. (160HP [Jun, Cappuccino drift guy])
  - ht07 with billet compressor wheel (high flow / a little bigger)?

### ECU N2 Information

**N2:** Non tune-able Suzuki Sport plug and play ECU. Originally from the F100 kit.

**Features:**
- RPM limiter is raised to 9300
- Speed Limiter is removed
- Boost Limiter is removed
- Boost Pressure 1.2bar. To increase you'll need a boost controller and you should have an AFR gauge

**Requirements:**
- Injectors 295cc
- NGK #9 spark plugs
- Bigger Turbo (maps optimized for it) OR AFR if stock Turbo (plx afr system recommended)
- High octane fuel
- Electronic Boost Controller (EBC) optionally, and AFR gauge recommended

**Most cost effective boost controllers:**
- [Electronic] Blitz Dual SBC "Type-R" boost controllers (dual solenoid, work for a long time accurately, around $150)
- [Manual] Hallman Pro w/ceramic ball is the best bang for the buck (around $100 on ebay)
- Gizzmo IBC + scramble button

**⚠️ Note:** Plug and Play ECU like the skuzzle need a throttle position sensor and custom map tuning so more complex/expensive

*Source: David Janetski / Garage Kei*

## Service Schedule
| Item | 6 months | 1 Year | 2 Years | 5 Years | Distance C | Distance R | Comments |
|------|----------|--------|---------|---------|------------|------------|----------|
| Engine Oil | R | E | . | . | 1,000 Km | 5,000 Km | API grade SH, SG, SF (higher letter more recent). 19000km/12000miles if fully synth (recommended as doesn't burn like mineral oil). Should be clear enough with no particles, no lumps/black |
| Engine Oil filter | R | E | . | . | . | 7,500 Km | Change at each oil change, easier, 3/4 UNF |
| Engine Oil drain | R | . | . | . | . | . | Replace seal each oil change |
| Gearbox Oil | C | R | . | . | 10,000 Km | 20,000 Km | . |
| Differential Oil | C | R | E | . | 10,000 Km | 20,000 Km | . |
| Engine Sparkplugs | . | R | E | . | . | 60-80,000 Km | . |
| Brake Fluid | . | C | R | . | . | 40,000 Km | . |
| Brake Pads | . | . | . | . | . | 25-70,000 Km | . |
| Brake Discs | . | . | . | . | . | . | . |
| Air filter | . | C | R | . | 30,000 Km | 60,000 Km | . |
| Engine Coolant | . | . | R | E | 20,000 Km | 40,000 Km | + Thermostat if taking time to heat up OR going in red, OAT coolant eat silicone, green Ethylene glycol recommended |
| Thermostat | . | . | . | . | ?? | ?? | Coolant needs purging |
| Engine Timing belt | . | . | . | R | . | 60,000 Km | Coolant needs purging, water pump and alternator need to come off. Tensioner bearing should feel perfectly smooth with no appreciable sideways rock. If it feels at all rough/notchy then replace |
| Alternator belt | . | . | . | R | . | 90,000 Km | . |
| A/C belt | . | C | . | R | 90,000 Km | 140,000 Km | . |

**Legend:**
- **C** = Check
- **R** = Replace
- **E** = Extended Replacement

---

## Parts Reference

### Air Filters
| Part | Quantity Needed | Stock P/N or Type | Acceptable alternatives | Notes |
|------|-----------|-----------------|-------------------------|-------|
| Intake, Air Filter | 1 | SUZUKI 13780-54G00 | BOSCH 1987429175, BOSCH S9175, Fram CA9588, HENGST E1230L, LUBER-FINER AF5099, MANN C1827, WIX WA9427, K&N 33-2709 | Stock fitment, of course. |
| Intake, IAC Solenoid | 1 | 18117-64d01 | Suzuki 18117-60B1089-94 | Suzuki Swift (93-94) or Geo Metro(1.0/1.3l)  |
| Cooling, Coolant | 4L | Ethelyene Glycol (**NON OAT**) | . | See section on coolant. |
| Cooling, Expansion Tank | 1 | Suzuki 17931-80001 | 1 | Also used on the Suzuki Samurai (1986-1995) |
| Cooling, Thermostat | 1 | Suzuki 17600-82810 or 17600-85811 | Suzuki 17670-73G01 | The 17670-73G01 part opens @ 78˚C, the stock part open @ 82˚C. |
| Cooling, Thermostat, Gasket | 2 | Suzuki 17569-82001-H17 | . | Also used on Suzuki Swift 1989-1994 |
| Cooling, Water Pump | 1 | Suzuki 17400-50813 | . | . |
| Oil, Filter | 1 | Suzuki 16510-82701 | Bosch (0986452058, OD058, or P2058), CHAMPION COF100180S, GUD Z537, HENGST H97W13, KOLBENSCHMIDT 847-OS, Mann W67/2, UFI 23.255.00, UFI 2325500, Wix WL7119, Motorcraft FL-910S | 12-14PSI bypass pressure |
| Oil, Motor Oil | 4L | 10W30 | 5W30 | 5W30 is a good year-round option in California. The engine will take between 3.2L and 3.8L. |
| Ignition, Spark Plugs | 3 | MGK DCPR7ERX-P (EA11R), NGK DCPR7EVX (EA21R) | . | May need a colder heat range with more boost and/or timing |
| Ignition, Spark Plug Leads | . | . | . | . |
| Ignition, Distributor, Rotor |  . | . | . | . |
| Ignition, Distributor, Cap | . | . | . | . |
| Fuel, Filter | . | . | . | . |
| Fuel, Pump |  . | . | . | . |
| Fuel, Injectors | . | . | . | . |
| Belt, Timing | . | . | . | . |
| Belts, Timing Tensioner | . | . | . | . |
| Belt, Alternator | . | . | . | . |
| Belt, AC | . | . | . | . |
| Brakes, Rotors, Front | . | . | . | . |
| Brakes, Rotors, Rear | . | . | . | . |
| Brakes, Pads, Front | . | . | . | . |
| Brakes, Pads, Rear | . | . | . | . |
| Accessories, Alternator | . | . | . | . |
| Accessories, AC Dryer |  . | . | . | . |
| Accessories, 
| Drivetrain, Clutch |  . | . | . | . |
| Drivetrain, Throwout Bearing | . | . | . | . |
| Drivetrain, Transmission, Lubrication | . | . | . | . |
| Drivetrain, Differential, Lubrication | . | . | . | . |
| Seal, Cam Shaft |  . | . | . | . |
| Seal, Crank Shaft |  . | . | . | . |
| Seal, Cam Carrier |  . | . | . | . |


       Leads    |          | 
                |          |>- Magnecor     KV85 Sark Plug Cable Set 45520,mgn-3503 https://www.dcperformance.co.uk/uprated/magnecor-kv85-ignition-leads/suzuki/cappuccino.html, https://www.larkspeed.com/category/view/MAGNECORSUZ/Magnecor-Ignition-Leads-Suzuki-, http://www.venommotorsport.com/engine/magnecor/8-5mm-ht-leads/suzuki-cappuccino/
 Fuel filter    |          | Suzuki Cappuccino Genuine number AY505-NS004, AY505-NS008,  £25
                |          | - Suzuki esteem 1998 same form factor but shorter
                |          | - uprated Nissan Skyline R32 General, R33GT-R, R34GT-R
                |          | - Microgard 33597 
                |          | - Fram      G5982
      pump      |          | universal (miata) fuel pump with little modification, fit if you file the barbs off http://amazon.com/dp/B073PVRHVT/ref=cm_sw_r_cp_apa_i_VoMrCbQ3RW604?fbclid=IwAR0JtFjL-rwSw0B2-Pvc6VORdQ_IZq7RYWQNekUoLyFu0I8w8KzyQD4NHFw
      rail adapt|          | - SRA06 Subaru Impreza fuel rail adapter(GDB EJ20) bolts right in 
      injectors |          | Stock 
                |          | - Suzuki Sport 295cc DENSO 19550-2270 / 4GA36-K10
                |          | - Half Way     327cc DENSO 19550-2130  
                |          | - SARD         300cc RED SARD SKU: 96303 PN: 63573
                |          | - Monstersport            195500-4433
                |          | - mazdaspeed Mx5 injector purple DENSO 195500-4060. Any mx5 injectors fit. Could use 320cc supra greens. Make sure you flow test injectors...took 6 to get 3 that matched and flowed correctly
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Timing cam belt |        1 | 128100-9240 Suzuki sport
                |          | NZ00012K    Timing Belt Kit, All OEM spec quality items.
                |          | - NZ00012   Timing belt
                |          | - NZ00013   Timing belt tensioner
                |          | - NZ00015   Waterpump & gasket
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Gearbox         |    1.06L | 75w-90 GL4
                |          | - Castrol Syntrans Multivehicle  75w- 90 GL4 It is excellent for curing the notorious notchy/grinding change into 2nd gear.
                |          |>- Castrol Syntrax  Universal     75W- 90     can be used for both gearbox and differential as it meets the criteria for both GL-4 and 5.
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Differential    |     0.8L | 75w- 90 GL5 SAE
                |          |>Castrol Syntrax  Universal     75W- 90  can be used for both gearbox and differential as it meets the criteria for both GL-4 and 5.  Replacing every other year should be possible if you don't do mega mileage.
                |          | STD - Red Line or Amsoil             75W- 90 or (75W140 not good on LSD, chatters at low speed worse, at speed the rear end makes an unhappy howl)
                |          | STD - Castrol Syntrax  Longlife      75w- 90 GL5 without 
		|          | LSD - Castrol Axle          GL-5 SAE 80W- 90 /SAE 75W90 75W140 80W90
                |          | LSD - Castrol Syntrax  Limited Slip  75w-140
                |          | LSD - Amsoil 75w90 Severe Gear
                |          | LSD - Royal Purple 75w90
                |          | LSD - Redline MT90
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Clutch          |        1 | - SZK017 Exedy service kit - 12000-06759 - replace 4£ tail seal at same time
                |          | - SZD048U      Clutch disc
                |          | - SZC547       Clutch cover
- bearing       |          | 6000lu 10x26x8mm (any this size) Release/throw out bearing
                |          | - RCTS338SA2
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Brakes Front    |          | http://www.clubcappo.co.uk/board/Blah/Blah.cgi?b=MOAD,m=1160242853
        - Discs |        2 | 55311-80F03
         /Rotors|          | - HOLDEN BARINA MF, MH                                 1/1989-1994 FRONT
                |          | - SUZUKI ALTO HATCH                                      1988-1995 FRONT
                |          | - SUZUKI CINO SF413                    1.3L 3/5 DOOR 5/1994-5/2000 FRONT
                |          | - SUZUKI SWIFT SF310, 413, SF410 1.0L, 1.3L          1/1989-5/2000 FRONT
                |          | - Demon Tweaks - KBD692 - Black diamond grooved G6/12 Front discs  £106.19
                |          | - RDA22 
                |          | 31015 Duralast Brake Rotor
        - Pads  |        2 | suzuki swift
                |          | - PP163 Font Predator pads  £026.69  
                |          | - dp2762, dp762 (race) EBC GreenStuff
                |          | - RDB1155 RDA GP MAX
       Back     |        2 |>  
        - Discs |      2x2 | -  Demon Tweaks - KBD960 - Black diamond grooved G6/12 Back  discs  £136.17
                |          | ???
        - Pads  |      2x2 | 55200-62840
                |          | - Font Predator pads  £0xx.x9  Demon Tweaks Black diamond grooved G6/12 Back  discs KBD960 £136.17
                |          | - EBC DP1093
       Fluid    |     1.0L | Use DOT 3, 4 or 5.1, but not 5 as it is silicon based and not compatible with ordinary brake fluid.
                |          | - 
       Line     |      2x2 | 51560-80F00 / 51570-80F00
                |          | - SSZ0100-4F Goodridge @72€
                |          | - ???        Monster Sport @19000JPY
       Light    |          | high Level brake light: green/white wire for live feed & black solid for earth, spade connectors close to radio antenna base 
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Alternator      |          | 31400-76G11           Denso Alternator (55A) [rebuild 125$ about]
                |          | - VR-H2005-39,133872  MOBILETRON DENSO ALTERNATOR VOLTAGE REGULATOR (KUBOTA DAIHATSU TOYOTA SUZUKI) to swap before replacing whole alternator
                |          | - 131400-76F00        Suzuki Wagon R MC21 (65A), compatible, you just need to exchange the pulley.
                |          | - NZ00073, EAL-1501   Compatible alternators part numbers
           belt |595-600 mm| NZ00050  Suzuki fan belt. 10x600mm v-belt. If you are pushed then 610mm max but the adjuster will be maxed out too.
                           | HB600a   Halfords Alternator Belt
                |          | 15235    vbeltsupply.com Auto V-Belt with cogs.
A/C        belt |10x765mm  | J1100765 New air conditioning belt
                |          | HB763a   Halfords A/C belt (which their systems shows as alternator belt)
           drier|          | NRF33031 Autodoc (slightly taller, use proper 10mm ports, NRF33327 was told compatible but used  8.7mm diameter ports which are too small)
Starter         |          | 
                |          | - rebuild with Mitsubishi john deer starter parts
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Battery         |          | Original 12V 40Ah 330A max 187x127x227mm, type 054, same battery as used in the Ignis, Wagon R and X90 according to Varta, 9-11Kgs
  - Lead Acid   |          | 540 127 033 3132 Varta BLEU Dynamique A15
                |          | 33610-73210-bnr  Suzuki Alto ah35 prix 45 euros
                |          | https://www.furukawadenchi.co.jp/english/products/car/ultrabattery.htm?fbclid=IwAR2XC4SbUUDxy8NALK15dD5RPBiCM9DMl_yV6mA11K9Bk5NQdg3P9hvUZHI
                |          |>YUASA YBX3054 60€, YBX5054 76€
  - Li-Ion      |          | Shorai      LFX18A1-BS12 270Cca 18.0Ah 145 x 66 x 105mm LiFePO4 1.00Kg [$190] https://minkara.carview.co.jp/userid/299715/car/1155349/4738093/parts.aspx
                |          | Antigravity AG801        240Cca  9.0Ah 110 x 57 x  95mm LiFePO4 0.70Kg [€180] https://www.facebook.com/photo.php?fbid=3008153039226258&set=gm.2389356767797955&type=3&theater&ifg=1
                |          | Shido       LT14B-BS     288Cca  4.8Ah 150 x 65 x 144mm LiFePO4 1.10Kg [£100]
Battery charger |          | The generally recognised "one to have" in the motorcycle world is the "Optimate III".". The tech blurb says suitable for batteries up to 28Ah, but in reality they'll do small car batteries like the Capp no problems.
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Alloys+Tyres    |          | Original (EA11r 7/EA21R 6 branches)  114.3x4, 14x5.0J 4.7kg - 165/65R14 78H 2.1 bar - Goodyear Eagle F1 - original size, space saver T115/70D14 (Steel)
                |          |                                      114.3x4, 15x????       - 175/55R15 77V 2.1 bar
                |          | Suzuki Sport Type C red trim         114.3x4, 14x5.5J ???Kg - 1?5/??R14
		|          | Suzuki BBS optional wheel            114.3x4,        
                |          |>Volk Rays    Te37   3.7Kg            114.3x4, 15x5.5J       - 165/50/15 -1.0% Compromise tyre on the larger rims
- Lug           |      4x4 | m12x1.25
                |          | - dorman 610-336
- Extended stud |          | ARP 100-7711 but different thread pitch from the stock m12x1.25, so you'll need new m12x1.5 lugnuts
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Seats           |          | 13.5Kg each with all hardware minus seatbelt (Drivers side above 28lbs, Passenger side 29lbs)
                |          | - Mazda RX7/FD seats are the ones to use, and they fit the Cappo with very minimal modification. 
                |          | - Sparco Sprint seats fit into a Cappuccino 2-3cm lower. Requires mounting a universal subframe to the car though, so having holes drilled in the floor. 
                |          | - Lotus Elise / VX220 seats 3cm lower https://forums.mightycarmods.com/forum/technical/how-to-forum/800419-lotus-elise-seats-in-a-suzuki-cappuccino?fbclid=IwAR1ZGcnDG3U8xlVqjpkSFG5T42DJ6ibWdKZrHUbgTm8ic36-dvkpzIN8WLg
                |          | - B5 Tillett seat https://www.tillett.co.uk/shop/images/gallery/Copen%20small%20file.jpg?fbclid=IwAR2WYDv53E17NHLRbtMDvA_b4lDPzERx1f6notmCNkgVBWa7Hx2iDGd-j7o
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
Steering wheel  |          |standard 350mm (non-srs) , 380mm (srs, mx5 parts to replace 365mm and 340mm)
                |          | directly compatible: raid & boss, 330mm and 350mm most common, lower and visibility of dash is reduced
Gear Knob       |          | 12 x 1.25 (same as lug nut)
                |          | - dorman 610-336
Key             |          | OEM KEY BLANK 37145-60A00, SUZUKI 99-04 VITARA 01-02 XL7, 99-02 GRAND VITARA 
Ignition switch |          | 97 Suzuki Swift only thing you have to do is solder the cappuccino's wiring loom plug on instead of the Swift's (and the one for the key beeper - 2 green wires). All colours for wires were the same except the Black wire with white stripe (It is Blue with a black stripe on the swift for the corresponding wire)
----------------+----------+------------+------------+------------------------------------------------------------------------------------------------------------------------------------------------
- Aluminium: Bonnet,Lower front wings, 3 piece aluminium removable hardtop
- Antenna:   The Cappo is 5mm female base.

Misc parts
Tie rod end:               Same as Suzuki Swift, Moog ES3043RL
Windshield Washer Pump:    TAAP Windshield Washer Pump 5-768

Care products
- Paint and Carbon fiber:   meguiars-scratch-x-2
- Rubber/plastic restorer:  Auto\Finesse Revive trim dressing

## Factory Options

| Part Number | Description | Price | Notes |
|-------------|-------------|-------|-------|
| 99000-99023-599 | Knee pads | . | . |
| 99000-79C49-003 | Ignition key lighting | . | Same as Suzuki Jimny |
| 99000-9900R-E01 | New Rear boot rack genuine | . | . |
| 99000-99004-Y16 | Black Mats (BCF nylon) | 11,000 yen | . |
| 99000-99004-B14 | Black tight Mats (polypropylene) | 8,000 yen | Super rare, thinner and fragile |
| 48100-70G90 | EA11R steering Wheel Nardi Super GARA 3 | 58,800 yen | . |
| 28113-80F10 | EA11R Gearstick knob NARDI PRESTIGE LINE LEATHER BLACK | 8,000 yen | Not engraved if by Nardi directly |
| . | Car radio: Clarion CRX74 radio/cassette + CD Changer support | . | For UK, dunno for Jap models |
| . | Subwoofer: Clarion GS-316S | . | Original option (but Blaupunkt GTHS80 also has the correct compatible connector) |
| 99000-99025-62M | Rear/Cargo net | . | Requires installation hardware: 4x Domed head Philips M5 x 0.8 pitch x 20mm long, 4x washers (12.5mm outer diameter), 4x rubber nut with insert (Well Nut Q-1032" which is M5 x 0.8 pitch, hole width 10mm) |
		  
ECU   ¦ ECU Stock                    ¦ ECU N1 (* with injector kit)           ¦ ECU N2       ¦ Suzuki Sport 295cc           ¦ Half Way 327cc    
------+------------------------------+-------------------------+--------------+--------------+------------------------------+-------------------
EA11R ¦ 33920-80F10                  ¦ 4JA36-L15, 283501-2810M, 284521-2810M* ¦ 4JA36-L27    ¦ DENSO 19550-2270 / 4GA36-K10 ¦ DENSO 19550-2130  
------+------------------------------+-------------------------+--------------+--------------+------------------------------+-------------------
EA21R ¦ 5MT 33920-80F21, 33920-80FV0 ¦ 4JA36-???, 283500-2820M, 284520-2820M* ¦ 4JA36-L40    ¦                              ¦                   
      +------------------------------+-------------------------+--------------+              +------------------------------+-------------------
      ¦ 3AT 33920-80F31, 33920-80FV1 ¦                         ¦              ¦              ¦                              ¦                   

## ECU Options

| Turbo | EA11R | EA21R |
|-------|-------|-------|
| Stock | IHI RHB31 VZ24 13900-80F00 RHB31FW-34004FP7NRBRFL2416CDZ VD110079 | Hitachi HT06-3 (stamped on top line) 13900-73810 (upto chassis number 101673), 13900-83CA0 (from chassis number 101674 onwards) |
| Stage 2 Turbo | IHI RHB31FW VZ25 4JA36-T10 RHB31FW-50001FP9NRBRFL275CDZ VE110087 | Hitachi HT07A |
| F100/K100 turbo kit | 185510-2810, 4JS36-A50 w/ ECU N2 | 185520-2820, 4JS36-A60 w/ ECU N2 |
| F111/K111 turbo kit | 186510-2810 | 186520-2820 |
- They are alternatives to standard turbos - to make a part similar to the F100 or F111 you need to machine the compressor housing and turbine housing to suit the new larger compressor wheel and turbine wheel. 
- Specs for the F100/F111 turbo are on the Japanese version of the Monster Sport site.

## Timing Belt Service Parts
| Part Number | Price | Description |
|-------------|-------|-------------|
| 17400-50812 | 9,320 JPY | Water pump + gasket joint |
| 128100-9240 | 11,700 JPY | Distribution belt Suzuki Sport |
| 11407-62D11-000 | . | Distribution belt (stock) went from 55,49€ in 2009 to 288€ in 2012 |
| 12810-81401 | 4,150 JPY | Distribution belt tensioner |
| 16100-70834 | 12,190 JPY | Oil pump (includes gasket 16119-73012) |
| 09283-32D38 | 530 JPY | Oil pump to "spy villebrequin" seal/gasket |

## Differential
| Part Number | Description | Price | Notes |
|-------------|-------------|-------|-------|
| 27411-80F00-000 | Normal diff | . | . |
| 27400-80810-000 | Sexel (JTEKT) Torsen LSD. LSD Torsen type A | . | [Reference](http://www5.famille.ne.jp/~skinski/e-lsd.htm) |
| 27395-80F00 | Side bearing (included with LSD) | 2,700 Yen | . |
| 73431-73B20 | Oil seal (ordered separately) | 570 Yen × 2 | 2 seals needed |

Oil
----
Mineral oil:        from processed crude oil.
Semi-synthetic oil: a mixture of synthetic oil and mineral oil. Engines requiring this oil cannot use mineral oil but may benefit from upgrading to synthetic oil.
Synthetic oil:      is usually the most expensive as it works over a wide range of temperatures and conditions for longer than mineral.

As far as general lubricating performance goes, the "wear rating" is the best guide;
oil for petrol (gasoline) engines will have an "S?" rating, something like SH or a later letter of the alphabet. 
Basically the later the letter, the more recent the classification. 
The main benefits of the synthetic technology have been to do with:
- reduced viscosity variation with temperature (i.e. thin when cold, thick when hot compared to traditional mineral oil), so less issues with cold start pumping/low hot pressure/reduced oil film thickness
- maximum temperature capability
- service life (extended change intervals are now normal, typically 10k miles). 

In a normal road engine developed for "traditional" oil, and if you change the oil frequently, then the virtues of fully synthetics are not exploited. 
Having said that, it'll do no harm (except to your wallet!). 
My experience with engine durability tests has been that generally speaking, modern engine material technology will give perfectly satisfactory component life given just normal straightforward routine servicing. Incidentally, the real life limiting factor for journal bearing wear rate (mains/big ends etc) is actually contaminant particle size; I'd recommend changing filters at each oil change, the extra cost is fairly trivial compared to everything else.
source: http://www.score.org.uk/phpbb3/viewtopic.php?f=2&t=654

American Petroleum Institute (API) Service Classification
The API’S certification mark and service symbol identify quality motor oils for petrol and diesel powered vehicles. Oils with these symbols meet the API’s service standards. The first ever API category was SA, the next SB, then SC and so on. All API categories up to and including SH are now obsolete. The current categories are; SJ, for 2001 and older engines; SL, for 2004 and older engines; SM, for 2010 and older engines; and SN, for 2011 and older engines. For diesel engines, CH-4, CI-4 and CJ-4 are the current categories.

European Automobile Manufacturers’ Association (ACEA) Sequence
This is the European equivalent of the API rating. These ratings consist of a letter indicating the class of oil: A/B or passenger car compatible motor oils, C for catalyst compatible motor oils and E for heavy duty diesel engine oils. The classes are divided into categories ranging from 1-9 and you can read them all here.

Excellent read: http://www.clubcappo.co.uk/board/Blah/Blah.cgi?,b=Technical,m=1200916600

Service [http://lacappuccinoenfrance.forumactif.org/t363-vidanger-le-liquide-de-refroidissement]
0) Heat the motor a bit so the oil is more fluid
1) Lift te car driver side.
2) Remove sum plug (17mm spanner, M14x1.5mm), 30-40Nm when putting it back. Plug on the side, doesn't fall straight with pressure at the beginning, beware...
3) Remove oil filter (belt key sliding, needed proper oil filter remover tool), 12-16Nm when putting back, 3/4 UNF.
4) Open oil cap on motor, last drops should fall
5) Put back sump plug (oil pan plug) and oil filter, après having sensually passed your oily finger on the M14 joint.
6) Put new oil (3.0L about, 2.8L engine + 0.2L filter) progressively, it is easier to add than remove

## Coolant

The Factory Service Manual says: "Use a good quality Ethelye Glycol coolant" with no additional information on coolant specs.

| Coolant Type | Technology | Lifespan | Comments |
|--------------|------------|----------|----------|
| Green | Phosphate | 2 years | Came as standard from Suzuki |
| Blue | Silicate | 2 years | Used on older vehicles where OAT may damage cooling system |
| Red/Pink | OAT | 5 years | Organic Acid (Additive) Technology, Silicate free, more modern (Suitable for most vehicles manufactured after 1998), eats silicone |
| Waterless | Evans | 20 years | Evans Waterless Coolant |

Service [http://www.clubcappo.co.uk/board/Blah/Blah.cgi?b=HT,m=1130239639]
1. Remove the radiator cap when the engine is cold. As you do this you will hear some hissing as the pressure is relieved from the system.
1. With the radiator cap removed, run the engine until the upper radiator hose becomes hot. 
1. Turn the engine off and open the radiator drain plug, located on the underside of the radiator, to drain the coolant. Take care not to get scalded, a pair of thick work gloves is advisable.
1. Retighten the drain plug and refill the system with clean water, running the engine again until the top hose becomes hot.
1. Repeat the drain and refill procedure until clear water flows.
1. Drain the system once more and refit and tighten the drain plug fully.
1. Remove the hose from the reservoir tank and then remove and empty the tank. Clean this out thoroughly and refit.
1. Add good quality antifreeze and water to the radiator and tank. Remember that there will be some water left in the system so take this into account when mixing. Fill the radiator to the base of the filler neck and the reservoir tank to 'FULL'. Replace the reservoir cap, aligning the arrows on the cap with those on the tank.
1. Run the engine, with the radiator cap still removed, until the radiator upper hose is hot.
1. With the engine idling, add coolant to radiator until the level reaches the bottom of the filler neck. Install radiator cap, making sure that the ear of the cap lines up with the reservoir tank hose.

**NOTE**: Steps 9 and 10 may need to be repeated several times to ensure that all air is purged from the system.

If you can only do 3.4-3.5L, heater matrix prob at fault
1 - if the heater matrix drains out when you empty the system (by siphoning usually) it's common that they don't re-fill easily 
2 - if you look at the system, the radiator cap is quite low on the Capp, and so you are unlikely to get the top hose properly full. 
    The system finishes the filling by ejecting air out of the rad cap vent pipe when it heats up and the pressure increases; 
	this should bubble out of the long siphon pipe attached to the cap in the make-up bottle. 
	The pipe must go below the coolant level in the make-up bottle because when the system cools down again, and the coolant contracts, it sucks coolant back into the radiator. 
	It usually takes 2 or 3 "hot/cold cycles" like this to properly stabilise and achieve near 100% filling. Some cars are much better than others at this. 
    My Capp took about 3 cycles and took in almost 0.5L in total; I put some masking tape on the bottle and marked it with a felt pen to be sure when it was stable. 
	Because of this amount, I think the heater matrix is the likely culprit.
    Murray Betts, Score Message Board Guru
3 - Do few 2-3 with heater on and it should take 400-500ml extra



EA21R boot release lever and cable for EA11R
--------------------------------------------
83320-80F00     Interior boot release kit lever - https://minkara.carview.co.jp/userid/1056967/car/1200540/2590911/note.aspx
83340-80F0V     interior boot release kit cable (83340-80F0V) - http://www5.famille.ne.jp/~skinski/c-trunkopener.htm

First and second gear synchro repair
-------------------------------------
24400-73D00 x 1 - HUB ASSY,LOW SPEED SYNC => if dogteeth are wrecked (and if they are, the teeth on the gear probably are too)
24431-85020 x 2 - RING,LOW SPEED SYNC     => recommend to do with this job as keys and spring are cheap and related to a good synchro engagement.
24436-84200 x 2 - SPRING,SYNC RING LOW    => recommend to do with this job as keys and spring are cheap and related to a good synchro engagement.
24472-60B00 x 3 - KEY,SYNCHRONIZER        => recommend to do with this job as keys and spring are cheap and related to a good synchro engagement.
24780-79001 x 1 - OIL SEAL                => in and out seal, good idea to do during disassembly
24151-70D00 x 1 - SEAL,INPUT SHAFT OIL    => in and out seal, good idea to do during disassembly
09262-25129 x 1 - BEARING(25X52X15)       => bearing that'll be pulled and pressed, good insurance to replace since its hard to get to later

Dimensions for using "SEAT,GEAR CONTROL LOWER" in top position: washer 35mm diameter x 6.5mm high (the "SEAT,GEAR CONTROL LOWER" is 6mm high so buy another allow to sort for cheap)

Gear Stick Bushings (mine desintegrated all plastic bits, left only the sprink ok, the shim was bent beyond recognition, you know when there is play lifting the gear stick that something is missing as it shouldn't move)
-------------------
25551-60A02     - BUSH,GEAR CONT LEVER          - bottom cylindrical seal
08321-0108A x 2 - Lock washer                   - sliders going on side bolts for rotation
28117-82C02 x 3 - SEAT,GEAR CONTROL LOWER       - (can be used as upper too, as it is part of the gear stick, can't be ordered but a custom washer will do or another one of this)
28118-80F00     - SHIM,GEAR SHIFT LEVER T:0.6   - Shim
28119-80F00     - SPRING,GEAR SHF CONT LVR SEAT - Spring

Differential mount Bushings
---------------------------
4JI36-D11                             Suzuki sport            - 1x - http://www5.famille.ne.jp/~skinski/c-defbush.htm, https://www.suzukisport-racing.com/ss_racing/mtbc/mtbc_5.html#r-defmt 
Steve Hole @ Clubcappo did custom ones better than Suzuki sport, for which one user didn't solve the clunk noise with
https://www.powerflex.co.uk/, http://www.superflex.co.uk/index.html, www.antivibrationmethodsrubber.co.uk torsion bush
Diameter pending

Seals and rubber parts
------
Door
  83821-80F00     LH Front outer Weather Strip
Roof
  78837-80F01     WEATHERSTRIP, roof CTR RH
  78847-80F01     WEATHERSTRIP, roof CTR LH
  84642-80F00     WEATHERSTRIP, roof side RH
  84652-80F00     WEATHERSTRIP, roof side LH
  78797-80F01     RR LH Molding Side roof
  78747-80F01     RR RH Molding Side roof
  78797-80F01     FR LH Molding Side roof
  78744-80F01     RF RH Molding Side roof
  78845-80F01     RR RH Molding CTR roof
  78745-80F01     RH Molding Side No 1
Console box mat
  75817-80F00-5PK console box rubber
Seat belt guide
  86451-80F00-5ES Seat belt guide
Windscreen washer spreader [gicleur]
  38480-80F01

Transmission mount:        86-95 suzuki samurai By cutting off the two tac welded nuts
Motor mount:               86-95 suzuki samurai
universal joints for prop shaft rear and middle joints : Hardy Spicer part number is RUJ-0603           

Drive Shaft
-----------
moog u-joint #392 works for the rear two u-joints on the driveshaft

Lights and indicators
---------------------
- 35910-80F00 Rear registration plate light (screw rust, black rear part breaks while unmounting)
SAPFIL          Front Indicator vents with light fit into bumper from japan
HLKHID-SH       Silk Road HID front Lights and are super rare [http://silkroad-jp.com/portfolio-2/exterior/ext_cap_light]
  60P-O60     4 light kit (70,000 yen)
  99-O4285    85f lamp unit (with bulb and LED) (8,000 yen)
  99-O42 LED  Position LED (875 yen)
http://www.sissk.co.jp/meker_topixs/spl/cappuccino.htm
- Dual headlights (HID 130.368 Yen or halogen 69.258 Yen)
- LED 4 light tail price list              (\ 29.274 Yen)
- FX146           Rear LED Lights

Roof panels wrapping [https://www.facebook.com/photo.php?fbid=2905716512803245&set=gm.2327639737302992&type=3&theater&ifg=1]
--------------------
- 5D Premium HIGH GLOSS Black Carbon Fiber Vinyl Wrap Bubble Free Air Release 12"x60"?  https://www.ebay.com/itm/281791346935?ul_noapp=true
- Edge Door Guard Trim Car Moulding Guards Auto Molding Protector 32ft Strip Black      https://www.ebay.com/itm/223140791460?ul_noapp=true

All enough wrap to do full roof and back pillar  the trim cost me under $30
Do not use hard plastic trim with a gel type glue as when very hot (in the trunk) will melt, stick out of the trim and get everything sticky. 

ECU capacitors repair kit
-------------------------
According http://auc.aleado.com/yahoo/lot?auctionID=m161187086#enlargeimg the capacitors are below but pics of ECu show one capacitor only 15uf 35v and only one that matches 491-0563 x 4 - Nichicon 15µF 100V dc Aluminium Electrolytic Capacitor, Through Hole 6.3 (Dia.) x 11 mm +105°C 6.3mm 2.5mm... Anybody got high res pics of the ECUs (stock, N1, N2) ?
- 374-566  x 4 - Nippon Chemi-Con 220µF  35V dc Aluminium Electrolytic Capacitor, Through Hole 8   (Dia.) x 11.5mm +105°C 8  mm 3.5mm
- 374-556  x 4 - Nippon Chemi-Con 100µF  35V dc Aluminium Electrolytic Capacitor, Through Hole 6.3 (Dia.) x 11  mm +105°C 6.3mm 2.5mm
- 390-350  x 5 - Nippon Chemi-Con  47µF  63V dc Aluminium Electrolytic Capacitor, Through Hole 8   (Dia.) x 12  mm +105°C 8  mm 3.5mm
- 491-0428 x 5 - Nichicon          33µF  63V dc Aluminium Electrolytic Capacitor, Through Hole 6.3 (Dia.) x 11  mm  105°C 6.3mm 2.5mm
- 491-0563 x 4 - Nichicon          15µF 100V dc Aluminium Electrolytic Capacitor, Through Hole 6.3 (Dia.) x 11  mm +105°C 6.3mm 2.5mm

Symptoms: [source FB Frankie Chan Ken Yong]
- black smoke when cold which leads to mot fail. too much gas is injected to chamber(way too much, it flood and it can't get over 6000 and it surge). 
- later on i use a wide band o2 sensor installed in downpipe and tune the air fuel ratio with a Air fuel controller. that makes it totally different performance

Window Regulator
----------------
1998-2002 Toyota Corolla window regulator is a direct swap but you need to replace the plug.
- come preinstalled on a window scroller thing if you buy it from an overstock site
- the screws for the Corolla motor are slightly bigger than the Capp motor, so require some force to get through the Capp's bracket.
- The motor still stutters near the top (it seems to be a lever/geometry issue, not a motor issue) but it is WAY quieter. When the engine is on, you can't even hear the regulator actuate!
- the switch was backwards but the plug was reversible, so I didn't need to rewire lol. here is the mapping:

Car wire color ¦ Motor wire color
---------------+-----------------
Green          ¦ Red
Red            ¦ Blue

Car radio connector
-------------------
W    - Permanent live
WB   - Accessory position on ignition
B    - Earth
RY   - Backlighting (headlamp feed)
Bl B - Left Speaker
Bl   - Left Speaker
RG   - Right Speaker
BR   - Right Speaker

Subfoower connector (under passenger seat, well hidden)
-------------------
1,5   - BrR and BrY (rear speakers)
4,7   - BlR and BlY (rear speakers)
2     - RW          (constant positive)
6     - Bl          (ignition)
3     - B           (negative)

Dashboard removal by @Andy Barker
-----------------
Pick a sunny day and take the roof off. No special tools are required just a selection of screwdrivers and a socket set, and probably some pliers if you intend to remove the dash pad from the dash assy. 
01. Remove the centre cubby (covered elsewhere on the site for the boot release retrofit). 
02. Remove the centre console trim (2 screws at either side of the stereo and one in front of the shift lever) This reveals the centre dash screw (below the stereo). 
03. Remove the two speaker covers (TIP, when pushing the centre of the clips in use a small tack hammered in to a piece of wood to push them in, the amount that the tack protrudes should stop you pushing the centre of the clip too far and loosing it in the sill cavity, carefully remove one of the clips to tune the amount that the tack protrudes) This exposes the two outer dash screws. 
04. Remove the steering wheel and steering column lower cover. (TIP, to free the steering wheel off the spline, lossen the nut and then work the wheel off, the nut will stop it flying off and hitting you as you're pulling it towards you). 
05. Unclip the electrical connectors on the dash lower (behind the drivers right knee) 
06. Remove the glove box (fixing in the right hand back corner, effectively a hinge), this allows access to the HVAC controls (disconnect them) and the bonnet release (unbolt this and also unclip it from the dash at the rear on the passenger side). 
07. Remove the meter surround. There are 5 screw (I think) two above the meter assy and 2 below, with one around the corner on the by the vent. 
08. Unbolt the column, this allows it to be moved down to remove the dash later. 
09. Prise out the tweeters and the centre screw cover by the windscreen, this reveales three screws holding the dash in. 
10. Now unscrew the 6 screws holding the dash in (three under the screen, one at each side and one in the centre). With a bit of juggling it should slide over the column. 
In the gospel according to Haynes, refitting is the reverse of removal. Please bear in mind this is from memory over one year ago - it worked, but don't blame me for scratched knuckles or broken trim. 

LED lamps for dashboard
- http://lacappuccinoenfrance.forumactif.org/t633-tuto-mettre-des-ampoules-led-sur-le-compteur?highlight=ampoules
- 11 x T5  1 SMS LEDs (polarity not indicated, needs testing, 1 for Air commands multidirectionnal or tape on it included)
- 04 x T10 4 SMS LEDs a bit short, go for 6
- 01 x ??? Fuse like shape "roof" light on center console

Links info
  - http://www.aussiesky.net/cappuccino/                                       Documents repository
  
  - http://clubcappo.co.uk                                                     Forum (English) UK
  - http://www.suzuki-cappuccino.com/phpbb3/index.php                          Forum (English)
  - http://lacappuccinoenfrance.forumactif.net/                                Forum (French)  France
  - http://www.suzuki-cappuccino.eu/                                           Forum (German)  Germany
  - http://ww1.tiki.ne.jp/~marcy/index1.html                                   Owners club     Japan
  
  - https://www.facebook.com/groups/ClubCappo/                                 [Closed Facebook Group] ClubCappo - Cappuccino Owners Club group (admin: Andy Milne, David Janetski@Japan)
  - https://www.facebook.com/groups/2024808397586129/                          [Closed Facebook Group] suzuki cappuccino America                (Admin: Jay Ferio, Spenser Blackburn, Chris Blair, Jason Bolt)
  - https://www.facebook.com/groups/2259297573/                                [Public Facebook Group] Suzuki Cappuccino Club                   (Admin: David Janetski@Japan)
  - https://www.facebook.com/groups/36402601897/                               [Public Facebook Group] Suzuki Cappuccino Club                   (Admin: Vik Kwan@Hong Kong)
  - https://www.facebook.com/NZSuzukiCappuccino/                               [Public Facebook Group] Suzuki Cappuccino Club NZ
  
  - https://minkara.carview.co.jp/smart/car/suzuki/cappuccino/                 Japanese tutorials and review
  - http://www5.famille.ne.jp/~skinski/index.htm                               Japanese tutorials and review
  - http://www.t-net.ne.jp/~saiki.com/cappuccino/                              Japanese tutorials and review
  - https://methinksperchance.net/cars/1995-suzuki-cappuccino-ea11r/           English blog and tutorials
  - http://sicks.jp/cappuwiki/index.php?title=CappuccinoWiki                   Wiki for cappuccino options and specs
  
  - https://web.archive.org/web/20100110210845/http://www.garagejohn.com:80/   Garage John [Down] custom cappuccino parts or https://translate.google.com/translate?sl=ja&tl=en&u=https%3A%2F%2Fweb.archive.org%2Fweb%2F20100110210845%2Fhttp%3A%2F%2Fwww.garagejohn.com%3A80%2F

Links Buy parts
- https://www.megazip.net/zapchasti-dlya-avtomobilej/suzuki/cappuccino-1870    Japanese new part provider
- https://www.amayama.com/en?v=1                                               Japanese new part provider
- http://catalog.impex-jp.com/suzuki/                                          Japanese new part provider
- https://www.monster-sport.com/e/car/cap.html                                 Monster Sport
- https://www.nengun.com/suzuki/cappuccino-ea11r                               Nengun
- https://www.rhdjapan.com/search/model/suzuki_cappuccino/car/suzuki
- http://toyoshimacraft.com/                                                   Toyoshima Craft (carbon fiber parts)
- http://yahoo.aleado.com                                                      Japan Yahoo Auctions in english
- https://www.croooober.com/en/                                                Japanese sites with rare cappuccino parts too
- https://item.rakuten.co.jp/suzukimotors/
- https://garagekei.com/shop/                                                  Garage Kei, part sale and part export
- https://jessestreeter.com/                                                   Part export (5€ bank fee + 10€ commission per item + shipping)

- http://www.t-t-works.com/kapugarage.htm                                      T. T. Works (suspentions, straigntening, exhaust)
- http://www.mgm-jp.com/cap1e.html                                             MGM (turbo, ecu chip, exhaust, brake, clutch)
- http://www.i-jworks.com                                                      Jworks Exhaust Meister
- https://www.tryforce.jp/product_cate/cappuccino/                             Triforce (Suspension, manifold, long block)
- http://www.kc-technica.com/tuning/ea11r/index.html                           KC Technica 
- http://www.spiegel.co.jp/                                                    Spiegel (Suspensions)
- http://www.asian-autoparts.com/                                              Asian Auto Parts (FR/BE)
- http://www.greenline.jp/                                                     Green Line (Various parts)
- http://www.palsports.co.jp/item.php?blogid=3&tag=40                          Pal Sports
- http://www.suruga-performance.com/index.php/catalogsearch/result/index/?car_model_2=614&q=suzuki+cappuccino
- http://www.carparts.co.jp/car/index.php?action=step1&carid=441
- http://www.cozy-lights.net/parts-c.htm
- http://www.c-pupa.com/parts/
- http://www.sissk.co.jp/meker_topixs/spl/cappuccino.htm
- http://www.est.hi-ho.ne.jp/liberal/myweb2_038.htm
- http://www.spiegel.co.jp/
- http://www.news-gt1.com/
- http://www.hayashiracing.com/
- http://www.rs-watanabe.co.jp/index2.htm
- https://auto-style.jp/ea21r/
- http://www.usracingsports.co.jp/index.html
- https://www.navic-kyoto.jp/online/list.php?brand=3&maker=1&car_model=?????+EA11.21

Links Buy parts service
- UK
   - http://www.europerformance.co.uk/pages/products/search_car/product.mhtml?car=suzukicappuccino
   - https://www.autolinkmx5.com/suzuki-parts-20-c.asp                            UK service parts and used parts (cheap)
- FR
   - https://www.webdealauto.com/fr/suzuki-cappucino-0-7.12839.html?search-type=vehicule

Engine service/tuning/rebuilding
- Japan
    - http://www.a-route.com/link.htm
    - http://www.halfway.co.jp/
    - http://www.arms-eng.com/cappuccino.html
    - http://www.d-eagle.com/products/cappuccino/
- UK
    - https://www.tdi-plc.com/
- Australia
    - http://www.perfectrun.com.au/
- Ireland
    - http://www.iviengines.ie/
- SP
    - https://www.totcar.com
    
Models
- http://www.works-y3f.com/m_cars/3_jpn/others/cino/cino.html