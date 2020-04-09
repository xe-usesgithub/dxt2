<div style="color:#444444!important;">

<h1 style="color:#336699!important;">DXT2</h1>

<p>Lightweight OS based on Debian 10, XFCE4, Tint2, Pmenu along with many improvements over the defaults.</p>

<p>I needed to replace Windows 7 and had just discovered Linux (6 years ago). I needed something light as I can't afford high-end hardware. Also easy to configure. So I began distro-hopping. I went through them all. Not just in VMs I installed to bare metal and used it for days to weeks to months. I ran into a million issues. I waded through tons of bad linux documentation and collected all the good bits along the way. I settled on XFCE. It was the "best" but it still wasn't nearly good enough. And the idea of DXT2 was born. 4 years in the making. I hope others may find this useful too.</p>

<h3>Features</h3>
<ul>
  <li>Completely modernises XFCE</li>
  <li>Tweaked for a better desktop experience</li>
  <li>Replaces your existing installation with very little input</li>
  <li>Built from netboot with only the required packages to run XFCE efficiently, nothing else</li>
  <li>Only 3 custom actions so as not to overcrowd YOUR menu (Open Root Terminal, Edit as Root, Convert to JPG)</li>
  <li>Removed all languages except English (you can still add your own easily)</li>
  <li>Shortened application names</li>
  <li>Reduced menu clutter</li>
  <li>Standard Debian</li>
</ul>

<hr>

<h4>Installation</h4>
<p>Boot off dxt2sda1.iso, open a root terminal (Ctrl-Alt-R) and run <code>installdxt2</code></p>
<alert><b>Warning:</b> Completely & irreversibly replaces your existing setup. Make sure you backup first!</alert>

<hr>

<h4>Post-Installation</h4>
<p>Once in your newly installed desktop open a root terminal (Ctrl-Alt-R) and run any of the following that apply<p>
  <ul>
    <li><code>addswap</code> Creates & activates 2GB /swapfile</li>
    <li><code>exportiso</code> Exports a live & installable iso of your current installation</li>
    <li><code>installchrome</code> Installs Google Chrome</li>
    <li><code>installsublime</code> Installs Sublime Text</li>
    <li><code>installteamviewer</code> Installs TeamViewer</li>
    <li><code>installtmp</code> Activates tmpfs</li>
    <li><code>installtrim</code> Activates weekly TRIM cronjob</li>
    <li><code>installvirtualbox</code> Installs & activates Virtualbox 6.0 with extension pack</li>
    <li><code>update</code> Checks for updates, removes unused packages, cleans apt, upgrades</li>
  </ul>
  
  <hr>
  
  <h4>Credits</h4>
  <ul>
  <li><b>Distribution:</b> <a href="https://www.debian.org/">Debian Buster</a></li>
  <li><b>Desktop:</b> <a href="https://www.xfce.org/">XFCE4</a></li>
  <li><b>Panel:</b> <a href="https://gitlab.com/o9000/tint2">Tint2</a></li>
  <li><b>Menu:</b> <a href="https://github.com/sgtpep/pmenu">Pmenu</a></li>
  <li><b>Theme:</b> <a href="https://www.gnome-look.org/p/1283611/">Aurora Nuevo Blue</a></li>
  <li><b>Icons:</b> <a href="https://drasite.com/flat-remix">Flat Remix</a></li>
  <li><b>Window Manager:</b> Breeze Dark X</li>
  <li><b>Installation:</b> <a href="https://packages.debian.org/buster/bootcd">bootcd</a> (ty Bernd)</li>
<ul>

</div>
