2). 
    
    b). Omogočili smo pin: PA8 poleg pina se izpiše TIM1_CH1.

    d). Vrednost prescaler: 16.

    e). Takt časovnika znaša: 10 kHz.

    f). To pomeni da ima Duty cycle 50% vrednost.

3).
    
    b). sConfigOC.Pulse = 50;

4).
    
    c). ConfigOC.Pulse = 25;

KAJ POČNEJO UKAZI V 1, 2 in 3 vrstici:

(1. Vrstica) = Register spreminja vrednost duty cycla

(2. Vrstica) = Poveča duty cycle za 10%. 

(3. Vrstica) = Ko duty cycle preseže 90% se vrne nazaj na 10%.
