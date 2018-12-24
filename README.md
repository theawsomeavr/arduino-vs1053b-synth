# arduino-vs1053b-synth
a synth based on the vs1053b
you must have already install the midi and the FastLED library
also you need the LiquidCrystal_I2C
https://github.com/FortySevenEffects/arduino_midi_library/
https://github.com/FastLED/FastLED
https://github.com/johnrickman/LiquidCrystal_I2C
if your lcd is not working change LiquidCrystal_I2C lcd(0x27,16,2); to LiquidCrystal_I2C lcd(0x3F,16,2);
