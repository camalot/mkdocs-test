
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
            <th colspan="4">OS OPTIONS</th>
        </tr>
        <tr>
            <td><code>UID</code></td>
            <td>The linux user id to run as</td>
            <td><code>1000</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <td>`GID`</td>
            <td>The linux group id to run as</td>
            <td><code>1000</code></td>
            <td>⬜️</td>
        </tr>
        <tr>
            <th colspan="4">SERVER</th>
        </tr>
        <tr>
            <td><code>TYPE</code></td>
            <td>The server <a href="java/server-types/">type</a></td>
            <td><code>LATEST</code></td>
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
            <th colspan="4">WHITELIST</th>
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
            <th colspan="4">RCON</th>
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
    <td><code></code></td>
    <td></td>
    <td><code></code></td>
    <td>⬜️</td>
</tr> -->
