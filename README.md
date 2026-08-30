<div align="center">

# Cartly.

**La compra de casa, compartida.**

Una llista de la compra compartida per a tota la casa: afegeix productes durant la setmana, organitza'ls per categories i ratlla'ls al súper. Pensada per enganxar-la a la nevera amb un codi QR.

🛒 **[Obre l'app →](https://poligle.github.io/Cartly/)**

</div>

---

## Què és

Cartly és una aplicació web d'una sola pàgina per gestionar la llista de la compra d'una casa entre diverses persones. Cada casa té el seu compte (usuari i contrasenya), i tots els qui hi entren comparteixen la mateixa llista sincronitzada en temps real.

La idea original és generar un codi QR que apunti a l'app i enganxar-lo a la nevera, perquè qualsevol de casa el pugui escanejar i afegir el que falta.

## Funcionalitats

- **Cistella i Llista** — una vista per anar afegint productes durant la setmana i una altra per ratllar-los mentre compres.
- **Categories amb color** — categories bàsiques predefinides (fruita i verdura, carn, làctics, plant-based…) i de pròpies, cadascuna amb el seu color.
- **Quantitats** per producte, amb eliminació ràpida en baixar de zero.
- **Gestos** — llisca a la dreta per marcar com a preferit, a l'esquerra per esborrar.
- **Habituals** — marca productes freqüents per tornar-los a afegir amb un toc.
- **Sincronització en temps real** entre tots els dispositius de la casa.
- **Comptes per casa** — inici de sessió amb usuari i contrasenya.
- **Multiidioma** — català, castellà i anglès.
- **Mode fosc** — manual o seguint el sistema.

## Tecnologia

- HTML, CSS i JavaScript en un únic fitxer (`index.html`), sense frameworks ni pas de compilació.
- **Firebase** (Realtime Database + Authentication) per a la sincronització i els comptes.
- Allotjat amb **GitHub Pages**.

## Ús local

En obrir el fitxer sense connexió amb Firebase, l'app funciona en mode local (les dades es guarden només en aquell navegador). Amb la configuració de Firebase, passa a mode sincronitzat entre dispositius.

## Llicència

Publicat sota llicència [MIT](LICENSE).