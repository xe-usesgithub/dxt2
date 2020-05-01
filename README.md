<div style="color:#444444!important;">

<img src="https://raw.githubusercontent.com/dessington/dxt2/master/screenshot.png">
<br/>
<br/>
<p>Lightweight OS based on Debian 10, XFCE4, Tint2, Pmenu along with many improvements over the defaults.</p>

<p>I needed to replace Windows 7 and needed something light as I can't afford high-end hardware. Also easy to configure. So I began distro-hopping. I went through them all. Not just in VMs I installed to bare metal and used it for days to weeks to months. I ran into a million issues. I waded through tons of bad linux documentation and collected all the good bits along the way. I settled on XFCE. It was the "best" but could be better. And the idea of DXT2 was born. 3 years in the making. I hope others may find this useful too.</p>

<h3>Features</h3>
<ul>
  <li>Completely modernises XFCE</li>
  <li>Tweaked for a better desktop experience</li>
  <li>Built from netboot with only the required packages to run XFCE efficiently, nothing else</li>
  <li>As such, it does not have all the bells and whistles - it's meant as a light base to build up from</li>
  <li>Useful custom actions (Open Root Terminal, Edit as Root, Convert to JPG)</li>
  <li>Shortened application names</li>
  <li>Reduced menu clutter</li>
  <li>Backports enabled</li>
  <li>Standard Debian</li>
</ul>

<hr>

<h3>Installation</h3>
For a standard install use <a href="https://github.com/dessington/dxt2/releases/download/1.0/dxt2install.iso">dxt2install</a>

For automated install that wipes, formats & installs to first hard drive found (sda) use <a href="https://github.com/dessington/dxt2/releases/download/v1.0/dxt2autoinstall.iso">dxt2autoinstall</a>

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
  </ul>
  
  <hr>
  
  <h4>Credits</h4>
  <ul>
  <li><b>Distribution:</b> <a href="https://www.debian.org/">Debian Buster</a></li>
  <li><b>Desktop:</b> <a href="https://www.xfce.org/">XFCE4</a></li>
  <li><b>Panel:</b> <a href="https://gitlab.com/o9000/tint2">Tint2</a></li>
  <li><b>Menu:</b> <a href="https://github.com/sgtpep/pmenu">Pmenu</a></li>
  <li><b>Theme:</b> <a href="https://www.gnome-look.org/p/1283611/">Aurora Nuevo Blue</a></li>
  <li><b>Icons:</b> <a href="https://github.com/vinceliuice/Tela-icon-theme">Tela</a></li>
  <li><b>WM:</b> Breeze Dark X</li>
  <li><b>Installation:</b> <a href="https://packages.debian.org/buster/bootcd">bootcd</a> (ty Bernd)</li>
<ul>

</div>

If I could fork XFCE this is what it would be like.

