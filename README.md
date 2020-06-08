<div style="color:#444444!important;">

<img src="https://github.com/dessington/dxt2/blob/master/dxt2xfce.png">
<br/>
<br/>
<p>Lightweight OS based on Debian 10, XFCE4, Tint2, Pmenu along with many improvements over the defaults.</p>

<h3>Features</h3>
<ul>
  <li>Completely modernises XFCE</li>
  <li>Tweaked for a better desktop experience</li>
  <li>Blends with your desktop instead of trying to take it over</li>
  <li>Built from netboot with only the required packages to run XFCE efficiently, nothing else</li>
  <li>As such, it does not have all the bells and whistles - it's meant as a light base to build up from</li>
  <li>Useful custom actions (Open Root Terminal, Edit as Root, Convert to JPG)</li>
  <li>Reduced menu clutter</li>
  <li>Backports enabled</li>
  <li>Standard Debian</li>
</ul>

<hr>

<h3>Installation</h3>
https://github.com/dessington/dxt2/releases/tag/v1.4

<hr>

<h4>Post-Installation</h4>
<p>Once in your newly installed desktop open a root terminal (Ctrl-Alt-R) and run any of the following that apply<p>
  <ul>
    <li><code>addswap</code> Create & activate 2GB /swapfile</li>
    <li><code>exportiso</code> Export a live & installable iso of your current installation</li>
    <li><code>installtrim</code> Activate weekly TRIM cronjob & set scheduler to deadline (only for SSD)</li>
    <li><code>update</code> Check for updates, remove unused packages, clean apt, upgrade</li>
    <br/>
    <li><code>installbrave</code> Install Brave browser (soon)</li>
    <li><code>installchrome</code> Install Google Chrome</li>
    <li><code>installsignal</code> Install Signal Messenger</li>
    <li><code>installsublime</code> Install Sublime Text</li>
    <li><code>installteamviewer</code> Install TeamViewer</li>    
    <li><code>installvirtualbox</code> Install Virtualbox</li> 
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
  
  <hr>
  
  <h4>Help Wanted</h4>
  <p>- With customising bootcd2disk.conf for an EFI setup.</p>
  <p>- With customising bootcd2disk.conf for dual booting both BIOS & EFI.</p>

</div>
