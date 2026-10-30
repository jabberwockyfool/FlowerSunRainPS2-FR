# Flower, Sun and Rain (Patch FR) — PlayStation 2

Ce patch met en français la version PS2 de Flower, Sun and Rain (Hana to Taiyou to Ame to).
Le texte est celui de la traduction française officielle de la version Nintendo DS européenne,
reporté dans le jeu PS2. L'opening est sous-titré en français (romaji + kanji + traduction).

Aucun fichier du jeu n'est fourni : il vous faut votre propre ISO.


ISO DE DÉPART
-------------
Le patch s'applique sur l'ISO japonaise déjà patchée en anglais (patch anglais v1.0 de Patchbay Works) :

  Hana to Taiyou to Ame to (English v1.0).iso
  Taille : 3 759 833 088 octets
  MD5    : 88763D058A8B85F1FC0CBE8617E1BE59
  SHA-1  : 98E601550AFBC8DB287C6C2EE1B8B2D78B524D6C

Si vous n'avez que l'ISO japonaise, appliquez d'abord le patch anglais dessus
(ISO japonaise attendue : Hana to Taiyou to Ame to (Japan), CRC32 592A9067).

Vérifiez la somme MD5 avant de patcher : avec une autre ISO, le patch ne fonctionnera pas.


APPLIQUER LE PATCH
------------------
Windows : Delta Patcher (ou xdelta UI)
  1. Fichier d'origine : Hana to Taiyou to Ame to (English v1.0).iso
  2. Patch : FSR_PatchFR.xdelta
  3. Appliquer.

Ligne de commande (Windows, Linux, macOS) :
  xdelta3 -d -s "Hana to Taiyou to Ame to (English v1.0).iso" FSR_PatchFR.xdelta "Flower, Sun and Rain (Patch FR).iso"

Résultat attendu :
  Flower, Sun and Rain (Patch FR).iso
  Taille : 4 259 590 144 octets
  MD5    : 82F8BCA1873AFB162E1C83746CE61C82
  SHA-1  : E3F29F6BC4A4FA62D9DB9A27F837C7A5C572267B

Testé sur PCSX2.


LIMITES CONNUES
---------------
- Les quelques répliques propres à la version PS2 (sans équivalent dans la VF DS) restent en japonais.
- Les menus et images d'interface restent en anglais.
- Un dialogue de l'épilogue dépasse d'une ligne.
- Deux mots des kanji de l'opening ont été reconstitués à l'oreille (paroles officielles introuvables).


CRÉDITS
-------
- Traduction française officielle : version Nintendo DS européenne (Marvelous / Rising Star Games).
- Patch anglais PS2 : Patchbay Works.
- Portage de la VF sur PS2, sous-titres de l'opening : Saint Eresia.

Flower, Sun and Rain © Grasshopper Manufacture / Marvelous. Patch non officiel, distribué gratuitement.
