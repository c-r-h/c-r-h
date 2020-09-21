![Header](Files/CaribouRock-02Jan2020.jpg "The Winter Coder")
## ☃️ The Winter Coder

If you're looking for code, there's more over on [<img height="20"
src="Files/Gitlab.Logo.png"> GitLab][GitLabCRH].  I am currently focused on
[<img height="20" src="Files/Zambezi.ProjectLogo.png"> Zambezi][Zambezi],
which is an [SMB3][WinSMB3] Offload Engine.

I started using GitLab a few years ago.  It's not as flashy as GitHub, but I
learned a few tricks and got used to it.  Moving back and forth between the
two is 90% easy and 10% annoying corner cases that trip me up.

### 🛠️ SMB/CIFS, SMB2/SMB3

**[Samba Team][SambaTeam] Member**<br/>
I write code and share knowledge about Windows core network protocols,
particularly Server Message Block ([SMB][WikiPediaSMB]).<br/><br/>
<a href="#"><img align="left" height="360" src="Files/Pointing.png"/></a>
  - [Implementing CIFS][ImpCIFS]<br/>
    Long ago, I wrote a book about CIFS (aka SMB1).  Despite Microsoft
    having [deprecated SMB1][SMB1JoseB], the book is still relevant today.
    I, for one, still use it as a reference from time to time.
  - [[MS-CIFS]] and [[MS-SMB]]<br/>
    A bit less long ago, I put together a team to write the CIFS
    specifications and update the SMB1 spec for Microsoft.<br/>
  - [SMB3 Offload Engine][Zambezi]<br/>
    These days I'm working on SMB2/3 integration with distributed file
    systems, and on SMB3 Offload.  I think it would be cool if the low-level
    message handling could be moved to a SmartNIC or similar device.<br/>
    ◦ Compression and Encryption<br/>
    ◦ Multichannel and Multi-protocol<br/>
    ◦ Packet marshalling/unmarshalling<br/>
    ◦ Direct I/O<br/>
  - I started fiddling with [PeerDist][MS-PCCRC] a while back, but have not
    spent time on it in...well...years.  I plan to get back to it.
    Eventually.
<br clear="both"/>

### 🏰 My Fiefdom

<a href="#"><img align="right" src="Files/FlyingHouseCloud.png"/></a>
- The Home Network<br/>
  The network used to be split between business and home.  There were two
  Soekris routers (remember those?) running [OpenBSD's][OpenBSD]
  [Packet Filter][PFilter], with routing in between.  It was a great setup,
  and I ran things that way for years.  More recently, I've combined down to
  a single network.  I run [OpnSense][OpnSense] on a
  [Protectli Vault][ProVault].  OpnSense is easier to manage day-to day, but
  I miss being able to fine tune my firewall to meet my picky specifications.
- What I'd like for distributed FW, monitoring and analysis.
- Reverse proxy web services

- Servers<br/>
  The server systems make use of [Linux MD RAID][LinuxRAID] for basic data
  protection.


### Ideas
- SMB3 NAS Offload Engine
- SMB3 Python Toolit
- Secure Overly Network
- Wide Area Distributed Key/Value store
- PeerDist

### Cool Hardware
- Kobol
- 2.5Gb switch
- Seed Board
- Good ol' Raspberry Pi

My desktop system is twelve years old.  My laptop is ten years old.  My
Chromebook is six months old but only because the old one broke.

Android dev?

### Books and Docs
- Written
- Reading

### GitLab

🤺
🚴
☕

<table align="center">
  <tr><td>
    Table Content.
  </td></tr>
</table>

<p align="center">
  <a href="https://www.linkedin.com/in/chrishertel/"><img height="32"
     src="Files/LinkedIn.Logo.png?raw=true"></a>
  <a href="https://www.gitlab.com/crh/"><img height="32"
     src="Files/Gitlab.Logo.png?raw=true"></a>
</p>


<p style="clear:right;">
  <a href="https://github.com/anuraghazra/github-readme-stats"><img
  align="left"
  src="https://github-readme-stats.vercel.app/api?username=c-r-h&show_icons=true&theme=graywhite&title_color=6070c0">
  </a>
  My most recent work is on <a href="https://www.gitlab.com/crh/"><img
  height="20" src="Files/Gitlab.Logo.png?raw=true"> GitLab</a>
</p>
<br clear="both"/><br/>
<a href="#"><img align="right" height="200" src="Files/Confused-t.png"/></a>
<p style="clear:left;">
  What if I put text here?
  Lots and lots and lots of text.  All sorts of text.  Much more text than I actually need.
  Lots and lots and lots of text.  All sorts of text.  Much more text than I actually need.
  Lots and lots and lots of text.  All sorts of text.  Much more text than I actually need.
  <br clear="left"/>
</p>
<a href="https://www.strava.com/athletes/christopher_hertel"><img
   align="left"
   src="https://veloviewer.com/SigImage/83887d/2/4/I/n/bcdfijojoj.png"></a>
<br clear="both"/>
<hr>
<sub>$Id: README.md; 2020-09-20 21:55:06 -0500; crh$</sub>

<!-- Reference Links -->
[MS-SMB]: https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-smb/f210069c-7086-4dc2-885e-861d837df688
[MS-CIFS]: https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-cifs/d416ff7c-c536-406e-a951-4f04b2fd1d2b
[WinSMB3]: https://docs.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview
[ImpCIFS]: http://ubiqx.org/cifs
[SambaTeam]: https://www.samba.org/samba/team/
[Zambezi]:https://gitlab.com/ubiqx/zambezi
[GitLabCRH]: https://www.gitlab.com/crh
[WikiPediaSMB]: https://en.wikipedia.org/wiki/Server_Message_Block
[OpenBSD]: https://www.openbsd.org/index.html
[PFilter]: https://www.openbsd.org/faq/pf/
[OpnSense]: https://opnsense.org/
[ProVault]: https://protectli.com/vault-4-port/
[LinuxRAID]: https://raid.wiki.kernel.org/index.php/Linux_Raid
[SMB1JoseB]: https://docs.microsoft.com/en-us/archive/blogs/josebda/the-deprecation-of-smb1-you-should-be-planning-to-get-rid-of-this-old-smb-dialect
[MS-PCCRC]: https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-pccrc/51cb03f8-c0dd-4565-9882-aeb5ab0fa07e
