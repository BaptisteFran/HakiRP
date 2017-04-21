# Serveur

Ce que j'ai déjà :

- Loginscreen
- Banque
- Taxi
- Policier
- Pole Emploi <--- a améliorer


#TODO List

1. Sauvegarde des coordonnées et respawn au même endroit
2. Loadouts suivant un certain niveau de permission (policiers, pompiers, médecins)
3. Banque -- DONE
4. Métiers (poubelles, mineur)
5. Menu général (plus de commandes) (ID, téléphone, actions)
6. Fonctions de policiers, médecins (menottes, heal, voir idendité, drag)
7. Activités ? (drogue, braquage, stripclub...)



#Métiers :

- Bus
- Policier
- Médecin
- Pompier
- Dépanneur
- Fourgon blindé (Amener de l'argent de la banque aux différents ATM)
- Mineur



#Banque : ------- DONE

- Déposer argent
- Retirer argent
- Sauvegarder argent dans DB


#Pole-emploi : ------- DONE

- Prendre un job
- Recevoir une paye toutes les 10min
- Ne pas pouvoir prendre d'autre job sans démissionner
- Rajouter des jobs <---- à faire



sessionsFound
Params: sessions

sessionJoining
Params: cur, max, hostName

sessionJoined
Params:

sessionJoinFailed
Params:

sessionHostFailed
Params: err

sessionHosted
Params:

sessionInitialized
Params:

sessionStateChanged
Params: state

getResourceInitFuncs
Params: isPreParse, add

onClientResourceStart
Params: res

onClientResourceStop
Params:

onResourceStop
Params: name

playerActivated
Params:

playerDropped
Params:

onPlayerJoining
Params: netId, name

onPlayerKilled
Params: playerId, attackerId, reason, position

onPlayerDied
Params: playerId, reason, position

onClientMapStart
Params:

onClientMapStop
Params:

onMapStart
Params:

getMapDirectives
Params: add

onClientGameTypeStart
Params:

------------------------ RegisterServerEvent ---------------------------

playerSpawned (in spawnmanager?)
Params:
