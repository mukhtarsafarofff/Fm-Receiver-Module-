(ENG)  Assembling an FM radio was always interesting for me , like another enthusiasts. Outside of the TDA7000 IC there is only one tunable LC circuit for the local oscillator . So complete FM radio can be made enough small to be fit inside cigarette lighter.The audio output of the receiver is amplified through LM386 amplifier chip that can drive a small speaker or headphones.Electronic diagram of the HF part of the device (from antenna to the LF output) built with TDA7000 is shown on Pic.4.7. As one can see, it is a simple device, made with relatively small number of components. The IC contains all the stages of the superheterodine receiver: the mixer, the oscillator, the IF amplifier, the amplitude limiter, the FM detector and few others.The station signal is from the (telescopic) antenna led to the input circuit that consists of L2, C13, C12 and C14. It is a parallel oscillatory circuit damped with R3 resistor, which has the reception bandwidth from 88 MHz till 108 MHz (it admits all the UHF signals on the pin 13, and weakens te signals outside the reception bandwidth). Inside the IC the signals are led into the mixer, where they are being given new carrier frequencies. The IF amplifier then follows, amplifying only one of those signals, the one whose frequency is equal to the inter-frequency, followed by the limiter, the FM detector, mute circuit and LF pre-amplifier. The oscillatory circuit of the local oscillator (L1, Cp, Cs, C and C5) is connected between pins 5 and 6. Pic.4.8-a shows the PCB of the device from Pic.4.7, while Pic.4.8-b contains the component layout (on the PCB). The complete device can be seen on Pic.4.8-c. The variable capacitor from Pic.3.8 is used as the only variable capacitor here since the input circuit is aperiodic, the legs marked with FO and G. This capacitor serves us to tune the receiver to stations. In the LF part of the receiver, the amplifier made with LM386 from Pic.3.19 is utilized (the components left from the potentiometer are omitted). * L1 and L2 are the self-bearing coils.


(DEU) Das Zusammenbauen eines UKW-Radios war für mich immer interessant, wie auch für andere Enthusiasten. Außerhalb des TDA7000 IC gibt es nur einen einstellbaren LC-Schwingkreis für den lokalen Oszillator. So kann ein komplettes UKW-Radio klein genug gebaut werden, um in ein Feuerzeug zu passen. Der Audioausgang des Empfängers wird durch den LM386 Verstärkerchip verstärkt, der einen kleinen Lautsprecher oder Kopfhörer antreiben kann. Das elektronische Diagramm des HF-Teils des Geräts (von der Antenne bis zum NF-Ausgang) mit dem TDA7000 ist auf Bild 4.7 dargestellt. Wie man sehen kann, ist es ein einfaches Gerät, das mit einer relativ kleinen Anzahl von Komponenten gebaut ist. Der IC enthält alle Stufen des Überlagerungsempfängers: den Mischer, den Oszillator, den ZF-Verstärker, den Amplitudenbegrenzer, den FM-Detektor und einige andere. 
