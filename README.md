<div style="color:#444444!important;">

<h1 style="color:#336699!important;">DXT2</h1> <h6>https://dxt2.co.za</h6>

<img src="https://dxt2.co.za/screenshot.jpg">

<br/>

<p>Lightweight OS based on Debian 10, XFCE4, Tint2, Pmenu along with many improvements over the defaults.</p>

<p>I needed to replace Windows 7 and needed something light as I can't afford high-end hardware. Also easy to configure. So I began distro-hopping. I went through them all. Not just in VMs I installed to bare metal and used it for days to weeks to months. I ran into a million issues. I waded through tons of bad linux documentation and collected all the good bits along the way. I settled on XFCE. It was the "best" but could be better. And the idea of DXT2 was born. 3 years in the making. I hope others may find this useful too.</p>

<h3>Features</h3>
<ul>
  <li>Completely modernises XFCE</li>
  <li>Tweaked for a better desktop experience</li>
  <li>Replaces your existing installation with very little input</li>
  <li>Built from netboot with only the required packages to run XFCE efficiently, nothing else</li>
  <li>As such, it does not have all the bells and whistles - it's meant as a light base to build up from</li>
  <li>Useful custom actions (Open Root Terminal, Edit as Root, Convert to JPG)</li>
  <li>Removed all languages except English (you can still add your own easily)</li>
  <li>Shortened application names</li>
  <li>Reduced menu clutter</li>
  <li>Backports enabled</li>
  <li>Standard Debian</li>
</ul>

<hr>

<h4>Installation</h4>
<p>Burn the iso to flash <code>dd if=dxt2rc1.iso of=/dev/sdx status=progress && sync</code></p>
<p>Boot the live system. Do not mount any drives. Open a root terminal (Ctrl-Alt-R) and run <code>installdxt2</code>. You'll need to enter your new username and password, and reset the root password. The rest is automatic.</p>
<alert><b>WARNING:</b> Completely & irreversibly replaces your existing setup. Make sure you backup first!</alert>

<hr>

<h4>Post-Installation</h4>
<p>Once in your newly installed desktop open a root terminal (Ctrl-Alt-R) and run any of the following that apply<p>
  <ul>
    <li><code>addswap</code> Create & activate 2GB /swapfile</li>
    <li><code>exportiso</code> Export a live & installable iso of your current installation</li>
    <li><code>installtmp</code> Activate tmpfs</li>
    <li><code>installtrim</code> Activate weekly TRIM cronjob & set scheduler to deadline (only for SSD)</li>
    <li><code>update</code> Check for updates, remove unused packages, clean apt, upgrade</li>
    <br/>
    <li><code>installchrome</code> Install Google Chrome</li>
    <li><code>installchromium</code> Install Chromium</li>
    <li><code>installfirefox</code> Install Firefox-ESR</li>
    <li><code>installoffice</code> Install LibreOffice 6.1</li>
    <li><code>installsublime</code> Install Sublime Text</li>
    <li><code>installteamviewer</code> Install TeamViewer</li>    
    <li><code>installvirtualbox</code> Install & activate Virtualbox 6.0 with extension pack</li>
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
