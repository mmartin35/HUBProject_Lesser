# Hackathon Week Lesser :

Prise programmée ayant 2 modes :

- mode automatique: adaptation a la fréquence d'utilisation. 
- mode manuel: allumage et extinction télécommandés.

## Comment faire :

Reprogrammer une prise programmable (horaire) pour la lier à une carte arduino. <br>

Carte arduino calculant l'utilisation en temps réel et s'adaptant à la consommation moyenne. <br>

Connecter au module arduino un récepteur rf connecté à une télécommande. <br>

## Pourquoi :

Economie de 11% sur la consommation d'électricité -> Augmentation du prix de l'électricité (Hausse de 39% du prix de l'électricité en France entre 2023 et 2024). *r1

## Inconvénients :

Consommation passive de la prise (solution: l'utiliser seulement sur la prise la plus énergivore).

#### Prix de la prise et du module:

- Prise programmable: 5,30e TTC (4,24e HT) *r2
- Arduino uno: 3,91e TTC (3.13e HT) *r3
- Commutateur RF + télécommande: 6,91e TTC (5,53e HT) *r4
- Assemblage: 3,00e

#### Total:

Nous partons du principe que 1 personne = 1 prise

- Entreprise 500 personnes = 11.960e
- Facture moyenne 500 personnes = 300.000e /an (en Suisse) *r5
- Déperdition 500 prises = 2 * 500 = 1000e /an
- 300.000 * 0.11 (économie moyenne /prise) - 1000 = 32.000e
- 1ère année = 32.000 - 11.960 = 20.400e <br>
- TTC: 19,08e
- HT: 15,90e
- Vente: 29,90e TTC (23,90e HT)
- Rentabilité: 29,90 - 15.90 = 14e HT

## Sources :

r1: Avec une hausse de 10 % au 1er février, l'**augmentation** des tarifs de l'**électricité** atteindrait environ 39 % sur un an puisqu'ils ont déjà été augmentés de 15 % en février 2023 et de 10 % en août 2023, rapporte Le Parisien. <br>

r2: https://fr.aliexpress.com/item/1005006176559524.html?spm=a2g0o.productlist.main.21.e843ubyCubyCbK&algo_pvid=6d4e2c21-f5ab-405c-b8e9-702e9514fe17&algo_exp_id=6d4e2c21-f5ab-405c-b8e9-702e9514fe17-10&pdp_npi=4%40dis%21EUR%2116.23%215.29%21%21%21124.75%2140.65%21%40211b61bb17053147829798495e9d49%2112000036140746230%21sea%21FR%210%21AB&curPageLogUid=oX4LxlyBQI3r&utparam-url=scene%3Asearch%7Cquery_from%3A <br>

r3: https://fr.aliexpress.com/item/32840365436.html?spm=a2g0o.productlist.main.5.47163244tIyFhx&algo_pvid=a603584e-83a4-4c69-876d-f0d1b2a7a0fd&aem_p4p_detail=2024011502355112060021138327500017474975&algo_exp_id=a603584e-83a4-4c69-876d-f0d1b2a7a0fd-2&pdp_npi=4%40dis%21EUR%214.83%213.91%21%21%215.17%214.19%21%40211b61bb17053149517643221e9d49%2112000016336828198%21sea%21FR%210%21AB&curPageLogUid=68Vk5pvhpjiP&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=2024011502355112060021138327500017474975_3 <br>

r4: https://fr.aliexpress.com/item/1005004262299781.html?spm=a2g0o.productlist.main.99.42e54f582MILJk&algo_pvid=8302aa10-9f84-4098-ba48-cd78dba5e9b8&algo_exp_id=8302aa10-9f84-4098-ba48-cd78dba5e9b8-49&pdp_npi=4%40dis%21EUR%216.90%212.55%21%21%217.38%212.73%21%40211b61bb17053154842745494e9d49%2112000028560066086%21sea%21FR%210%21AB&curPageLogUid=df64gOTYK7Eb&utparam-url=scene%3Asearch%7Cquery_from%3A <br>

r5: https://www.uvek.admin.ch/uvek/fr/home/detec/medias/communiques-de-presse.msg-id-67023.html <br>
