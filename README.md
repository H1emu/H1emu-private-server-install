<h1 dir="auto"><img src="https://i.gyazo.com/5d2322450b17f0692fd7d48014cc70d6.png" alt="" /></h1>
<h1 dir="auto">H1emu-private-server-install</h1>
<p dir="auto">Install H1emu private server</p>
<p dir="auto">(Tested with ubuntu 20.4 Clean install) (may work on other Distros&nbsp; this script will force install some packages &amp; upgrade old packages **use at your own risk**)</p>
<ol>
<li><code>sudo</code></li>
<li><code>apt install git -y</code></li>
<li><code>git clone https://github.com/H1emu/H1emu-private-server-install.git<br /></code></li>
<li><code>cd H1emu-private-server-install</code></li>
<li><code>chmod +x install.sh</code></li>
<li><code>./install.sh</code></li>
</ol>
<p dir="auto"></p>
<h2>Starting Private Server</h2>
<table>
<tbody>
<tr>
<td>Stop server</td>
<td>pm2 kill</td>
</tr>
<tr>
<td>Start server</td>
<td>cd /H1emu-private-server-install/h1z1-server/</td>
<td>Then sudo ./start.sh</td>
</tr>
<tr>
<td>Show server output</td>
<td>pm2 monitor</td>
</tr>
</tbody>
</table>
<h2>Setup MongoDB Settings</h2>
<p dir="auto">You must Block this port using firewall once setup is complete port 4321!!!</p>
<p dir="auto">Open a webbrowser to <a href="http://ip:4321">http://serverip:4321</a></p>
<p dir="auto">Locate h1server in your mongo db</p>
<p dir="auto">Change nameId:**** Server Name Strings <a href="https://github.com/QuentinGruber/h1z1-string-finder/blob/main/strings.log">HERE</a></p>
<p dir="auto">Change&nbsp; ( serverAddress:"YourServerip:1117" )</p>
<p dir="auto">Change&nbsp; ( PingAddress:"YourServerip:1117" )</p>
<div class="fieldset Number ng-star-inserted">
<div class="key">&nbsp;</div>
</div>
<p dir="auto"><img src="https://i.gyazo.com/9010a3af6b02b803f9d2922581f5b771.png" alt="" /></p>
<p dir="auto"><img src="https://i.gyazo.com/4775ad7f732383e520aaf5bd5b705eca.png" alt="" /></p>
<p dir="auto">&nbsp;</p>
<h2>&nbsp;</h2>
