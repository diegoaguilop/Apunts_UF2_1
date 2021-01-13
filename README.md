# **Apunts_UF2_1**

## **PROVES**

### **Objectius de les proves**

Les finalitats de fer les proves de software serien:

* Provar si el programari no fa el que ha de fer
* Provar si el programari fa el que no ha de fer.
----------------------

### **Forma de les proves**

* **Proves dinàmiques:** Permeten mesurar el comportament de l'aplicació desenvolupada. Requereixen l'execució de l'aplicació.

* **Proves estàtiques:** S'examina el codi font. Es realitzen sense executar el codi de l'aplicació.
----------------------

### **Estratègies de prova**

* **Caixa blanca:** S'examina el codi font i la seva execució. Són proves estructurals.
  * Es treballa sobre la interfície.
  * No es tenen en compte els detalls interns de funcionament.
  * Es proporcionen entrades i s'estudien les sortides.
  * Principals tècniques:
    * Particions d'equivalència.
    * valors límit.

* **Caixa negra:** S'estudia el sistema des de fora. Són proves de funcionalitat.
  * Es comproven els fluxos d'execució dins de cada unitat (funció, classe, mòdul, etc.)
  * També poden comprovar els fluxos entre unitats durant la integració.
  * I fins i tot entre subsistemes, durant les proves de sistema.
  * Principals tècniques:
    * Cobertura de codi.
    * Prova de bucles.

![](proves_caixes.png)
----------------------

### **Tipus de proves**

* **Funcionals:** Avaluen el compliment dels requisits.
  * Proves unitàries (o d'unitat).
  * Proves de regressió.
  * Proves d'integració.
  * Proves de fum (proba de foc).
  * Proves de sistema.
  * Proves alfa i beta.
  * Proves d'acceptació (validació per part de client).

* **No funcionals:** Avaluen aspectes addicionals com rendiment, seguretat, compatibilitat, ...
  * Proves d'usabilitat.
  * Proves de rendiment.
  * Proves d'estrés.
  * Proves de seguretat.
  * Proves de compatibilitat.
  * Proves de portabilitat.
  * etc...
 ----------------------
 
 ### **Mecanismes de prova**
 
 * **Manual:** Mitjançant proves realitzades per personal de l'empresa o extern.
 
 * **Automàtic:** Mitjançant programari que executa codi de forma automatitzada i compara els resultats obtinguts i els resultats esperats.
 ----------------------
 
