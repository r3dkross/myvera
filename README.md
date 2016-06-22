# myvera
Passage de la homelive en Vera

- Une fois l'accès local activé et ssh

- Connection en root via le terminal

  ou

-Sous Altui dans l'onglet commande os


Puis

Version 1.7.1598:

- wget http://builder1204.mios.com/rl/712/mt7620a_Luup_ui7-1.7.1598-en-mios.squashfs -O /tmp/newmios.squashfs
- wget http://builder1204.mios.com/rl/712/mt7620a_Luup_ui7-1.7.1598-en-mios.sh -O /tmp/newmios-hooks.sh
- ash -x /usr/bin/cmh-upgrade.sh

  ou 


Version 1.7.1707:

- wget http://builder1204.mios.com/rl/713/mt7620a_Luup_ui7-1.7.1707-en-mios.squashfs -O /tmp/newmios.squashfs
- wget http://builder1204.mios.com/rl/713/mt7620a_Luup_ui7-1.7.1707-en-mios.sh -O /tmp/newmios-hooks.sh
- ash -x /usr/bin/cmh-upgrade.sh

