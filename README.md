# SetLap — versions de test / beta builds

**SetLap** relie chacun de vos tours dans *Le Mans Ultimate* au setup exact utilisé et aux conditions
de piste, pour retrouver facilement le setup d'un bon temps, comparer deux setups et gérer tous vos
fichiers de setup.

Ce dépôt sert uniquement à distribuer les versions de test aux bêta-testeurs.
*English below.*

## Télécharger

Onglet **[Releases](../../releases)** : prendre la version la plus récente et télécharger
`SetLap-Installation-<version>.exe`.

## Installer

1. Lancer `SetLap-Installation-<version>.exe`. Aucun droit administrateur n'est demandé :
   SetLap s'installe pour votre compte Windows seulement.
2. Windows peut afficher **« Windows a protégé votre ordinateur »** (SmartScreen), car l'installateur
   des versions de test n'est pas signé. Cliquer sur **Informations complémentaires**, puis
   **Exécuter quand même**.
3. Pour passer à une nouvelle version, installer simplement par-dessus : vos données sont conservées.

## Utiliser

- Dans *Le Mans Ultimate*, l'option **« Enable external plugins »** doit être activée (températures
  des pneus et essence).
- Laisser SetLap ouvert pendant que vous roulez : il enregistre vos tours et le setup chargé.
- Pour découvrir l'interface sans le jeu : menu Démarrer > **SetLap > Outils > SetLap - Démonstration
  (fausses données)**. Vos vraies données ne sont pas touchées.
- Vos données sont dans `%LOCALAPPDATA%\SetLap`. SetLap ne supprime ni n'écrase jamais
  directement vos fichiers de setup (corbeille restaurable).

## Signaler un problème ou une idée

Onglet **[Issues](../../issues)** > **New issue**. Indiquer :
- la version de SetLap (affichée en haut de la fenêtre) ;
- ce que vous faisiez, ce qui s'est passé, ce que vous attendiez ;
- si possible une capture d'écran.

---

## English

**SetLap** links every lap you drive in *Le Mans Ultimate* to the exact setup and track conditions,
so you can find the setup behind a good time, compare two setups and manage all your setup files.
The interface is available in English and French.

**Download**: open **[Releases](../../releases)**, take the latest version and download
`SetLap-Installation-<version>.exe`.

**Install**: run it (no administrator rights needed). If Windows shows *“Windows protected your PC”*
(SmartScreen, beta builds are not signed), click **More info** then **Run anyway**. To update,
install the new version over the old one: your data is kept.

**Use**: enable **“Enable external plugins”** in *Le Mans Ultimate* and keep SetLap open while driving.
To try it without the game: Start menu > **SetLap > Outils > SetLap - Demo (sample data)**.

**Report a bug or an idea**: **[Issues](../../issues)** > **New issue**, with the SetLap version
(shown at the top of the window), what you did, what happened and a screenshot if possible.
