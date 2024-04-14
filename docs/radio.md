# Radios

## REDFOR radio frequencies

Preset | Purpose                         | Frequency MHz
-------|---------------------------------|--------------
1      | All Aircraft Common / Human GCI | 124.0
2      | Extra channel                   | 126.0
3      | Extra channel                   | 128.0
4      | DCS AWACS                       | 130.0
5      | Extra channel                   | 132.0
       | Helicopter Common               | 30.0 FM
       | MiG-15                          | 4.95
       | Airfield / traffic calls	 | Don't
       
## BLUFOR radio frequencies

Preset | Purpose                         | Frequency MHz
-------|---------------------------------|--------------
1      | All Aircraft Common / Human GCI | 251.0
2      | Extra channel                   | 253.0
3      | Extra channel                   | 255.0
4      | DCS AWACS                       | 257.0
5      | Extra channel                   | 259.0
       | Helicopter Common               | 30.0 FM
       | Airfield / traffic calls	 | Don't

## Software

The server uses [SRS (DCS SimpleRadio Standalone)](http://dcssimpleradio.com/) for voice comms.

Thanks to the magic of SRS, you can't hear transmissions from the other side's aircraft. (This is how Red and Blu helos can both use 30.0 MHz FM.)

In practice, many players use Discord for comms, and many players do not have SRS installed.

The SRS overlay shows what radios you have available, what they're tuned to, which one's selected, who's transmitting (including you), and how many people are connected to the channel. 

The SRS overlay can confirm what frequency a preset channel is set to.

If you use the SRS overlay key combo ([[Ctrl]] [[Shift]] [[Esc]] by default) to cycle through its modes, when it's showing as a black window with a title bar, you can drag it to a different part of the screen.

### PTT binding

Please set up a PTT button/key/switch for use with SRS, _which is not used for anything else_. Avoid using the same key you use for the DCS radio menu or everyone on channel will hear a little burst of static as you go to the weapons loadout screen etc. If you must use the same button for both, try to switch to a different channel before selecting loadouts/troops. 

## Traffic calls

Unlike some other popular DCS servers, traffic calls are not required and strongly discouraged on ECW. Just use your eyes, courtesy, and maybe your landing lights before taxying onto or landing on a runway and try not to cause anyone to crash.

## Aircraft Specific Guides

(Todo: add screenshots and more aircraft)

### Mi-8

The Mi-8 has two communication radios we care about. The primary radio (R-863) for normal U/VHF and the secondary radio (R-828) for the 30.0 MHz FM channel used by other helicopters.

1. Primary radio pedestal controls:
    - PRESET/MANUAL switch to PRESET
    - Maximise volume
2. Secondary radio controls (on right cockpit wall, next to countermeasures panel):
    - Power switch to ON
3. Use primary radio channel selector on overhead in front of pilot to switch between preset channels
4. Radio selector on overhead in front of your seat:
    - Maximise volumes
    - RADIO/ICS switch to RADIO
    - Choose primary (R-863) or secondary (R-828) radios to transmit on

You may also want to turn on your signal flares (power switches and circuit breaker) and set up binds for the different colour flares, and use them to help friendlies find/ID you, or to give a fireworks display when your door gunner shoots down an F-14 :)

### Mi-24

The Mi-24 is like the Mi-8 but simpler.

1. Turn on radio switches on pilot cockpit left sidewall
2. Adjust volumes on primary radio panel and radio selector panel
3. Use selector knob to select transmission on primary and secondary radio

### Mirage F1

1. Main (Green) radio _(TRAP 136)_:
    - Mode selector knob to PAL+G
    - Frequency selector knob to P
2. Secondary (Red) radio _(TRAP137B)_:
    - Mode selector to M
3. Click on audio panel knobs to select transmission on primary and secondary radio
