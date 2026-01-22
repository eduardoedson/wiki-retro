---------------------------------------

@rates

Displays the server rates.

---------------------------------------

@refresh

Synchronizes the player's position on the client with the one stored on the server.
Additionally, @refreshall will refresh all online players.

---------------------------------------

@autotrade

Allows you continue vending offline, then logs off.
The character will continue vending until you log in to that account again,
all items are sold, or the mapserver closes.

---------------------------------------

@iteminfo <item name/ID>

Displays item information (type, price, weight, drops).

Example:
@iteminfo Jellopy

---------------------------------------

@noask

Toggles automatic rejection of deals and invites.

---------------------------------------

@showexp

Toggles the display of experience gain messages.

---------------------------------------

@ksprotection

Toggles Kill Steal Protection.

---------------------------------------

@showdelay

Shows or hides the red "Cannot use the skills" message.

---------------------------------------

@autolootitem <+/- item name/ID>
@autolootitem reset

Starts or stops autolooting a specified item.
Typing "reset" will clear the autoloot item list.
By default, 10 items can be autolooted at one time.

---------------------------------------

@whereis

Displays the maps in which monster normally spawns.
This does not include mobs summoned by scripts.

---------------------------------------

@whodrops <item name/ID>

Displays a list of mobs which drop the specified item.
Only the highest drop rates are shown. 

---------------------------------------

@showzeny

Toggles the display of Zeny gain messages.

---------------------------------------

@hominfo / @homstats

Displays homunculus stats in different formats.

---------------------------------------

@commands

Displays a list of @ commands available to the player.

---------------------------------------

@autoloot {<%>}

Enables or disables autolooting items from killed mobs.
If a percentage is given, only items dropped at that rate and below will be autolooted.

---------------------------------------

@mobinfo <mob name/ID>

Displays monster information (rates, stats, drops, MVP data).

Example:
@mobinfo Poring

---------------------------------------

@ltp

Activates or deactivates a minimap marker showing the last location
where the character was teleported.

---------------------------------------

@woetime

Displays the days and times when War of Emperium (WoE) events occur
on the server.

---------------------------------------

@autopot <hp|sp> <item id> {<min hp|sp % [1..100]>} {<delay [100..1000]>}
@autopot <hp|sp> list
@autopot <hp|sp> on|off
@autopot info
@autopot help
@autopot blacklist

Allows configuring automatic usage of healing items for HP or SP.
The item will be used when the defined HP/SP percentage is reached,
respecting the configured delay.

Use "list" to display configured items.
Use "on|off" to enable or disable autopot.
Use "blacklist" to manage maps where autopot is disabled.

---------------------------------------