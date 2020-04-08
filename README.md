<h1>DXT2</h1>

<p>Lightweight OS based on Debian 10, XFCE, Tint2, Pmenu along with many improvements over the defaults</p>

<p>I needed to replace Windows 7 and had just discovered Linux (6 years ago). I needed something light as I can't afford high-end hardware. Also easy to configure. So I began distro-hopping. I went through them all. Not just in VMs I installed to bare metal and used it for days to weeks to months. I ran into a million issues. I waded through tons of bad linux documentation and collected all the good bits along the way. I settled on XFCE. It was the "best" but it still wasn't nearly good enough. And the idea of DXT2 was born.</p>

<h3>Features</h3>
<ul>
  <li>Completely modernises XFCE</li>
  <li>Tweaked for a better desktop experience</li>
  <li>Replaces your existing installation with very little input</li>
  <li>Built from netboot with only the required packages to run XFCE efficiently, nothing else</li>
  <li>Only 3 custom actions so as not to overcrowd YOUR menu (Open Root Terminal, Edit as Root, Convert to JPG)</li>
  <li>Shortened application names</li>
  <li>Reduced menu clutter</li>
</ul>

It's standard Debian and uses the standard Debian repos.

<h4>Post-Installation</h4>
<p>Once in your newly installed desktop open a root terminal (Ctrl-Alt-R) and run any of the following that apply<p>
  <ul>
    <li><code>addswap</code><br/>creates & activates 2GB /swapfile</li>
    <li><code>exportiso</code><br/>exports a live & installable iso of your current installation</li>
    <li><code>installchrome</code><br/>installs Google Chrome</li>
    <li><code>installsublime</code><br/>installs Sublime Text</li>
    <li><code>installteamviewer</code><br/>installs TeamViewer</li>
    <li><code>installtrim</code><br/>activates weekly TRIM cronjob</li>
    <li><code>installvirtualbox</code><br/>installs Virtualbox 6.0</li>
    <li><code>update</code><br/>checks for updates, removes unused packages, cleans apt, upgrades</li>
  </ul>
  
