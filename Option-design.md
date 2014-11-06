<ul class="task-list">
<li>
<p>Behavior</p>

<ul class="task-list">
<li>Common

<ul class="task-list">
<li>Load pages via Ajax

<ul class="task-list">
<li><i>Avoid iframes.</i></li>
</ul>
</li>
<li>Auto pause between browser-tabs

<ul class="task-list">
<li><i><strong>When playing  media on another tab too, the playback on the first tab will be paused.</strong></i></li>
</ul>
</li>
<li>Confirmation when closing current playing windows</li>
<li>Allow downloads 

<ul class="task-list">
<li><i><strong>Allow the direct download of media.</strong></i></li>
</ul>
</li>
<li><strong>Allow geolocation</strong>
  <ul class="task-list">
  <li><i><strong>Allow to retrieve the geolocation of users for statistical purposes.</strong></i></li>
</ul>
</li>
</ul>
</li>
<li>Queries

<ul class="task-list">
<li>Max number of recently played items

<ul class="task-list">
<li><i><strong>Limit the number of displayed rows in the &quot;recently played&quot; area on the home page</strong> .</i></li>
</ul>
</li>
<li>Time in days for statistics collection

<ul class="task-list">
<li><i>Limit the period of displayed statistics.</i></li>
</ul>
</li>
<li>Max number of table rows per page

  <ul class="task-list">
<li><i><strong>Limit the number of displayed table rows per page (artists, albums, songs, playlists, etc.)</strong>.</i></li>
</ul>
</li>
<li>Artist events - Max number of future events

<ul class="task-list">
<li><i>Limit the number of displayed rows for future events.</i></li>
</ul>
</li>
<li>Artist events - Max number of past events

<ul class="task-list">
<li><i>Limit the number of displayed rows for past events.</i></li>
</ul>
</li>
</ul>
</li>
<li>Notifications

<ul class="task-list">
<li><strong>Enable web player browser notifications</strong>
<ul class="task-list">
  <li><i><strong>Allow to display a notification which is a small pop-up to give you updates about currently playing media.</strong></i></li>
</ul>
</li>
<li>Timeout for notifications in seconds

<ul class="task-list">
<li><i>Displayed time of the notification on screen.</i></li>
</ul>
</li>
</ul>
</li>
<li>Streaming

<ul class="task-list">
<li>Media play count limitation for all users

<ul class="task-list">
<li><i>This setting can be used to limit the number of media a user can play. 0 means no limit.</i></li>
</ul>
</li>
<li>Time of inactivity before artist slideshow is shown

<ul class="task-list">
<li><i>0 means no slideshow.</i></li>
</ul>
</li>
<li>Authorize Flash web player

<ul class="task-list">
<li><i>The flash player is useful when using transcoding to be able to seek media. A fall-back is automatically processed when HTML5 and/or Aurora are also activated.<i></i></i></li>
</ul>
</li>
<li>Authorize HTML5 web player

<ul class="task-list">
<li><i>Streamed natively through the browser. Be careful, some formats are not handled by HTML5 and when using transcoding, you won't be able to seek the media. A fall-back is automatically processed when Flash and/or Aurora are also activated.</i></li>
</ul>
</li>
<li>Authorize Aurora.js player

<ul class="task-list">
<li><i>Aurora is a full javascript decoder. Support plenty of format but use more CPU. A fall-back is automatically processed when Flash and/or HTML5 are also activated.</i></li>
</ul>
</li>
<li>Broadcast per web player by default

<ul class="task-list">
<li><i>Instead of manually enable each time the broadcast on the web player, you can by default activate the functionality.</i></li>
</ul>
</li>
<li>Playback method

<ul class="task-list">
<li><i>Playing output to use.</i></li>
</ul>
</li>
<li>Use beautiful stream url

<ul class="task-list">
<li>
<i>Use eye-comprehensive urls instead of default ones.</i> </li>
</ul>
</li>
</ul>
</li>
<li>Transcoding

<ul class="task-list">
<li>Download rate limit

<ul class="task-list">
<li><i>The parameter is used when you want to download a song: if you have a value into "rate_limit", the content of the file to download is spitted into X packets of ("rate_limit" * 1024). Otherwise (ie "rate_limit" = 0), the whole content of the file is sent directly.<i></i></i></li>
</ul>
</li>
<li>Enable transcoding</li>
<li>Global bitrate for audio transcoding in kbps

<ul class="task-list">
<li><i>Example: 192kbps, 256kbps or 320kbps</i></li>
</ul>
</li>
</ul>
</li>
<li>Albums

<ul class="task-list">
<li>Default sort order</li>
<li>Group multiple disks

<ul class="task-list">
<li><i>If you have "Album [Disk1]" and "Album [Disk2], you can display them as one. Note: grouping is only applied when browsing an artist; albums are still separated into the global albums list.</i></li>
</ul>
</li>
<li>Allow to sort per release type

<ul class="task-list">
<li><i>Enable the sort order per type.</i></li>
</ul>
</li>
<li>Release type sort order

<ul class="task-list">
<li><i>A list of desired sort order separated by a comma.</i></li>
</ul>
</li>
</ul>
</li>
<li>Local playback

<ul class="task-list">
<li>Local playback access

<ul class="task-list">
<li><i><em>undefined</em></i></li>
</ul>
</li>
<li>Local playback method

<ul class="task-list">
<li><i>Local client to use.</i></li>
</ul>
</li>
</ul>
</li>
<li>Playlists

<ul class="task-list">
<li>Clear democratic votes of expired user sessions

<ul class="task-list">
<li><i>When a user session expired, all votes the user previously made are automatically removed.</i></li>
</ul>
</li>
<li>Playlist method

<ul class="task-list">
<li>
<i>When adding a media to a playlist, you can define the action to execute. You can for example clear the current playlist and start playing directly.</i> </li>
</ul>
</li>
<li>Playlist file type

<ul class="task-list">
<li><i>Type of generated playlist.</i></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li>
<p>Interface</p>

<ul class="task-list">
<li>Common

<ul class="task-list">
<li>Language</li>
<li>Show donate button</li>
<li>Display the played counter of each media

<ul class="task-list">
<li><i>Add a new field on the media page to show the number of time the media has been played.</i></li>
</ul>
</li>
</ul>
</li>
<li>Theme

<ul class="task-list">
<li>Theme choice</li>
<li>Fix headers/sidebars position on compatible themes</li>
<li>Show top menu</li>
</ul>
</li>
<li>Home page

<ul class="task-list">
<li>Show medias that are currently being played</li>
<li>Show recently played medias</li>
<li>Show video(s) of the moment

<ul class="task-list">
<li><i>Random selection of videos.</i></li>
</ul>
</li>
<li>Show album(s) of the moment

<ul class="task-list">
<li><i>Random selection of albums.</i></li>
</ul>
</li>
<li>Filter medias that are currently being played per user

<ul class="task-list">
<li><i>If a user is connected with two sessions, you can have two entries for the same person. You can avoid that by activating this option.</i></li>
</ul>
</li>
</ul>
</li>
<li>Player

<ul class="task-list">
<li>Show lyrics button

<ul class="task-list">
<li><i>Note: you need to activate at least one lyrics plugin to be able to use this functionality.</i></li>
</ul>
</li>
<li>Show name of currently playing media in page title</li>
</ul>
</li>
<li>Privacy

<ul class="task-list">
<li>Allow to show personal info in currently playing area.</li>
<li>Allow to show personal info in recently played area.</li>
<li>Allow to show streaming agent

<ul class="task-list">
<li><i>The streaming agent is the software used to stream the media (browser, external software, etc.)</i></li>
</ul>
</li>
<li>Allow to show streaming date and time</li>
</ul>
</li>
</ul>
</li>
<li>
<p>Plugins</p>

<ul class="task-list">
<li>Google

<ul class="task-list">
<li>Google api key

<ul class="task-list">
<li><i>Used for geo-location</i></li>
</ul>
</li>
</ul>
</li>
<li>Last.FM

<ul class="task-list">
<li>Username
<i><em>undefined</em></i>
</li>
<li>Password</li>
</ul>
</li>
<li>Libre.FM

<ul class="task-list">
<li>Username
<i><em>undefined</em></i>
</li>
<li>Password</li>
</ul>
</li>
</ul>
</li>
<li>
<p>Administrators</p>

<ul class="task-list">
<li>Interface

<ul class="task-list">
<li>Website title</li>
<li>URL for a custom logo

<ul class="task-list">
<li><i>The Ampache logo will be replaced by this one.</i></li>
</ul>
</li>
</ul>
</li>
<li>Server

<ul class="task-list">
<li>Force HTTP playback regardless of used port

<ul class="task-list">
<li><i><em>undefined</em></i></li>
</ul>
</li>
<li>Non-Standard HTTP port

<ul class="task-list">
<li><i><em>undefined</em></i></li>
</ul>
</li>
</ul>
</li>
<li>Restrictions

<ul class="task-list">
<li>Allow democratic controlled playback/playlist </li>
<li>Allow local playback</li>
<li>Allow media sharing</li>
<li>Allow media streaming</li>
<li>Allow media upload</li>
<li>Enable video feature</li>
<li>Lock songs 

<ul class="task-list">
<li><i><em>undefined UNNECESSARY?!?</em></i></li>
</ul>
</li>
</ul>
</li>
<li>Uploads

<ul class="task-list">
<li>Allow users to edit their uploaded media</li>
<li>Consider the uploading user as the media artist</li>
<li>Create a subdirectory per user (recommended)</li>
<li>Run the following script after upload

<ul class="task-list">
<li><i>The script need to be placed into the uploads target directory.</i></li>
</ul>
</li>
<li>Catalog that will be used for user uploads</li>
</ul>
</li>
<li>Shares

<ul class="task-list">
<li>Time in days when sharing links will expire

<ul class="task-list">
<li><i>0 means never.</i></li>
</ul>
</li>
</ul>
</li>
<li>Backends

<ul class="task-list">
<li>DAAP backend</li>
<li>DAAP backend password</li>
</ul>
</li>
<li>Plex backend

<ul class="task-list">
<li>Subsonic backend</li>
<li>UPnP backend</li>
</ul>
</li>
<li>Update

<ul class="task-list">
<li>Check automatically via Git for Ampache updates 

<ul class="task-list">
<li><i>Requires that Ampache is installed as a local Git repository.<i></i></i></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>