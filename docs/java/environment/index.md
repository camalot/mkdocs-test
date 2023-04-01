
## Environment Variables


<table>
    <thead>
        <tr>
            <th>NAME</th>
            <th>DESCRIPTION</th>
            <th>DEFAULT</th>
            <th>REQUIRED</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th colspan="4"><h4><strong>OS OPTIONS</strong></h4></th>
        </tr>
        <tr>
            <td><code>UID</code></td>
            <td>The linux user id to run as</td>
            <td><code>1000</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>GID</code></td>
            <td>The linux group id to run as</td>
            <td><code>1000</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <th colspan="4"><h4><strong>SERVER</strong></h4></th>
        </tr>
        <tr>
            <td><code>TYPE</code></td>
            <td>The server <a href="java/server-types/">type</a></td>
            <td><code>VANILLA</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>EULA</code></td>
            <td>You <strong>MUST</strong> set this to <code>true</code></td>
            <td><code>&nbsp;</code></td>
            <td>✅</td>
        </tr>
        <tr>
            <td><code>VERSION</code></td>
            <td>The minecraft version</td>
            <td><code>LATEST</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>MOTD</code></td>
            <td>Set the server log in message.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>DIFFICULTY</code></td>
            <td>The difficulty level. Available values: <code>peaceful</code>,<code>easy</code>,<code>normal</code>,<code>hard</code></td>
            <td><code>easy</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>ICON</code></td>
            <td>The url or file path for the icon image to use for the server. It will be downloaded, scaled, and converted to the proper format.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>OVERRIDE_ICON</code></td>
            <td>The server icon which has been set doesn't get overridden by default. Set this to <code>TRUE</code> to override the icon</td>
            <td><code>FALSE</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>MAX_PLAYERS</code></td>
            <td>The maximum number of players that can join the server.</td>
            <td><code>20</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>MAX_WORLD_SIZE</code></td>
            <td>The maximum possible size in blocks, expressed as a radius.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>ALLOW_NETHER</code></td>
            <td>Allows players to travel to the Nether</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>ANNOUNCE_PLAYER_ACHIEVEMENTS</code></td>
            <td>Allows server to announce when a player gets an achievement.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>ENABLE_COMMAND_BLOCK</code></td>
            <td>Enables the command blocks.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>FORCE_GAMEMODE</code></td>
            <td>Force players to join in the default game mode.</td>
            <td><code>false</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>GENERATE_STRUCTURES</code></td>
            <td>Defines whether structures (such as villages) will be generated.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>HARDCORE</code></td>
            <td>If set to <code>true</code>, players will be set to spectator mode if they die.</td>
            <td><code>false</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SNOOPER_ENABLED</code></td>
            <td>If set to false, the server will not send data to snoop.minecraft.net server.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>MAX_BUILD_HEIGHT</code></td>
            <td>The maximum height in which building is allowed. Terrain may still naturally generate above a low height limit.</td>
            <td><code>256</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SPAWN_ANIMALS</code></td>
            <td>Determines if animals will be able to spawn.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SPAWN_MONSTERS</code></td>
            <td>Determines if monsters will be spawned.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SPAWN_NPCS</code></td>
            <td>Determines if villagers will be spawned.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SPAWN_PROTECTION</code></td>
            <td>Sets the area that non-ops can not edit (0 to disable)</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>VIEW_DISTANCE</code></td>
            <td>Sets the amount of world data the server sends the client, measured in chunks in each direction of the player (radius, not diameter). It determines the server-side viewing distance.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>SEED</code></td>
            <td>Sets the seed to create the Minecraft world. If you use a negative number, make sure that it is in quotes.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>MODE</code></td>
            <td>Minecraft servers are configured to run in Survival mode by default. You can change the mode using MODE where you can either provide the <a href="http://minecraft.gamepedia.com/Game_mode#Game_modes">standard numerical values</a> or the shortcut values:<br />
            <ul>
                <li>creative</li>
                <li>survival</li>
                <li>adventure</li>
                <li>spectator(minecraft 1.8 or later)</li>
            </ul></td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>PVP</code></td>
            <td>By default, servers are created with player-vs-player (PVP) mode enabled.</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>LEVEL_TYPE</code></td>
            <td>By default, a standard world is generated with hills, valleys, water, etc. A different level type can be configured by setting LEVEL_TYPE to <a href="https://minecraft.fandom.com/wiki/Server.properties#level-type">an expected type listed here</a>.
            </td>
            <td><code>minecraft:default</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>GENERATOR_SETTINGS</code></td>
            <td>For some of the level types, <code>GENERATOR_SETTINGS</code> can be used to further customize the world generation <a href="https://minecraft.fandom.com/wiki/Server.properties#generator-settings">as described here</a>.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code></code></td>
            <td></td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <th colspan="4"><h4><strong>CUSTOM RESOURCE PACK</strong></h4></th>
        </tr>
        <tr>
            <td><code>RESOURCE_PACK</code></td>
            <td>A link to a custom resource pack</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>RESOURCE_PACK_SHA1</code></td>
            <td>The checksum for the custom resource pack</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>RESOURCE_PACK_ENFORCE</code></td>
            <td>Enforce the resource pack on clients</td>
            <td><code>FALSE</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <th colspan="4"><h4><strong>WHITELIST</strong></h4></th>
        </tr>
        <tr>
            <td><code>ENABLE_WHITELIST</code></td>
            <td>Enable the whitelist to manually manage the whitelist</td>
            <td><code>false</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>WHITELIST</code></td>
            <td>A list of usernames and/or UUIDs separated by comma</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>WHITELIST_FILE</code></td>
            <td>A url or file path to a whitelist <code>json</code> formatted file.</td>
            <td><code></code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>OVERRIDE_WHITELIST</code></td>
            <td>Enforce regeneration of the whitelist on each server startup.</td>
            <td><code>false</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <th colspan="4"><h4><strong>RCON</strong></h4></th>
        </tr>
        <tr>
            <td><code>ENABLE_RCON</code></td>
            <td>Should RCON be enabled</td>
            <td><code>true</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>RCON_PASSWORD</code></td>
            <td>You <strong>MUST</strong> change this value</td>
            <td><code>minecraft</code></td>
            <td>✅</td>
        </tr>
        <tr>
            <td><code>RCON_PORT</code></td>
            <td>The port for RCON</td>
            <td><code>25575</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td><code>BROADCAST_RCON_TO_OPS</code></td>
            <td>Should RCON be enabled</td>
            <td><code>false</code></td>
            <td>⬜️</td>
        </tr>
    </tbody>
</table>

<!-- <tr>
    <th colspan="4"><h4><strong></strong></h4></th>
</tr> -->
<!-- <tr>
    <td><code></code></td>
    <td></td>
    <td><code></code></td>
    <td>⬜️</td>
</tr> -->
