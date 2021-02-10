# Vaja1-ADC-single-conversion-STM32F0
Zelena LED je priključena na PA5 pin, MODRA pa na noben pin, ker jo STM32 nima.Na pin PA0 je priključen POTENCIOMETER.
Analogni vhod je pin PA0.
Najina razvojna ploščica ima 3 ADC pretvornike.
ADC pretvorniki inajo lahko oznako s trikotnikom. To pomeni, da so pini, ki jih uporablja ADC pretvornik zasedeni.
To lahko odpravimo tako, da tiste pine, ki jih uporablja ADC pretvorba postavimo v resetirano stanje.
Vseh vhodnih kanalov ADC prevorbe je 15 oz. 16, če štejemo zraven še pin 16 na katerem lahko izvajamo samo singel-ended pretvorbo.
Poleg pina, ki sva ga izbrala za potenciometer se izpiše ADC1_IN5.
V Parameter settings sva izbrala ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Ostale možnostni ločljivosti pa so še: 
# 12-bitna ločljivost, od 0 do 4095.
# 10-bitna ločljivost, od 0 do 1023.
# 6-bitna ločljivost, od 0 do 63.
