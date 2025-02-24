# GUIDE D’UTILISATION DU MODULE D’AMPLIFICATION DE PETIT SIGNAL RÉGLABLE AD620

## Aperçu

Ce module est un amplificateur de tension uV/mV de haute précision ou un amplificateur d’instrumentation de petits signaux basé sur le circuit intégré AD620 d’Analog Devices. Avec ladite puce, le module peut amplifier les tensions uV et mV AC ou DC. De plus, vous pouvez ajuster le décalage de niveau zéro de votre signal de sortie pour améliorer la précision des formes d’onde de votre projet. En interne, ce module crée une alimentation séparée de votre alimentation CC pour ajuster le décalage de votre signal de sortie. La puissance de sortie divisée est disponible pour l’utilisateur avec la borne V- comme alimentation négative.

## Image et étiquette du produit

![AD620 adj petits amplificateurs de signal étiquettes](#PIC1-2.png)

## Comment utiliser ce module

1. **Alimentation**
   - Fournissez d’abord une source DC au Vin et au GND au niveau des bornes d’entrée. Cela mettra le module sous tension.
   - Pour une meilleure linéarité, réglez votre alimentation à environ 3 – 10V.

2. **Ajustement de la tension de décalage de sortie**
   - Court-circuiter les bornes d’entrée -S et +S.
   - Placez un oscilloscope ou un voltmètre sur les bornes de sortie Vout et GND.
   - Réglez le potentiomètre Adjust Offset. Mettez-la à zéro pour obtenir une tension de décalage zéro.

3. **Mesures asymétriques**
   - Placez votre signal à amplifier sur la borne d’entrée du signal +S.
   - Mettez le GND de votre signal sur la borne d’entrée du signal -S.
   - Vérifiez la sortie Vout avec votre lunette ou votre voltmètre. Vous pouvez ajuster l’amplitude de votre forme d’onde à l’aide du potentiomètre Adjust Gain.

4. **Mesures différentielles**
   - Placez votre signal + sur la borne d’entrée du signal +S.
   - Placez votre signal - sur la borne d’entrée du signal -S.
   - Vérifiez la sortie Vout avec votre lunette ou votre voltmètre. Vous pouvez ajuster l’amplitude de votre forme d’onde à l’aide du potentiomètre Adjust Gain.
