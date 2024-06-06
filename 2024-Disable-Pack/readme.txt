Overview
Author Kim Duck Un
Orignal Authors Lions and Modifed due script being public access

Install
Drag and Drop folder in your resources
ensure the folder in server.cfg
change settings in config.

Configuration Options
General Settings

    Config.DisableGangFight (default: true)
        Description: Disables gang shootouts and prevents gang members from attacking the player.
    Config.DisableWeaponDrop (default: true)
        Description: Disables weapon drops from NPCs upon their defeat.

Weapon Drops

    Config.WeaponDrop1 (default: 0xDF711959)
        Description: The hash of the first weapon to be disabled from dropping.
    Config.WeaponDrop2 (default: 0xF9AFB48F)
        Description: The hash of the second weapon to be disabled from dropping.
    Config.WeaponDrop3 (default: 0xA9355DCD)
        Description: The hash of the third weapon to be disabled from dropping.

Police Vehicle Settings

    Config.DisableWeaponFromPolVeh (default: true)
        Description: Prevents the player from receiving a shotgun when entering a police vehicle.

Vehicle Control Settings

    Config.DisableVehAirControl (default: true)
        Description: Disables vehicle air control when the vehicle is airborne.

Combat Settings

    Config.DisableWeaponPunch (default: true)
        Description: Disables the ability to punch with a weapon.
    Config.DisableCombatRoll (default: true)
        Description: Disables the combat roll maneuver.
    Config.DisableSpamPunching (default: false)
        Description: Disables the ability to spam punch.

Miscellaneous Settings

    Config.DisableDispatch (default: true)
        Description: Disables dispatch services.
    Config.DisableBigMap (default: true)
        Description: Disables the big map when pressing F1.

Version Check

    Config.VersionCheck (default: true)
        Description: Enables version checking for the script.