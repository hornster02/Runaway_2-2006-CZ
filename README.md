STEAM (2025-08)
<br/>
Velikost 11+23MB https://drive.google.com/drive/folders/1fYQITmbHeBdGPAdEo9j23femb5LiAdDr

Postup
<br/>
-připojit "Runaway 2_TAGES.mds" na virtuální mechaniku (mé nastavení - 1x DVD mechanika typu SCSI, písmeno Z - DAEMON Tools Lite)
<br/>
-aplikovat CZ patch
<br/>
-nakopírovat obsah složky ```_CZ-PART2``` do hry
<br/>
-nainstalovat DRM ```TagesSetup_x64.exe``` (```atksgt.sys```/```lirsgt.sys```) - vyzkoušeno ve Win7. http://www.tagesprotection.com/main.htm
<br/>
-spustit hru přes Runaway2.exe

Chyby
<br/>
-nízké FPS (už úvodní videa mohou běhat okolo 0-1FPS = hledej padající sníh), nebo černá obrazovka+zamrznutí (hlavně v menu) = může pomoci dgVoodoo2 (dgVoodoo Virtual SVGA Card - bez zbytečné 3D akcelerace)
<br/>
<br/>
<br/>

-když tedy ani po 19-ti letech zřejmě nikdo neuveřejnil CZ crack nebo alespoň CZ mini/maxi image obcházející DRM, tak jsem zkusil maxi-image vytvořit já (z DVD klonu sk*torrent.eu/torrent/details.php?id=3adcdc3e45bd26ce481a6a03bb9875c50eaeffd9). (Možné)chyby -

-kvůli chybným blokům (pro kontrolu je přiložen FullEventLogView.exe, F5 obnovit - stovky a tisíce červených řádků, bylo by to nepřehlédnutelné /// pokud se objeví po spuštění Runaway2.exe, tak je maxi-image kvůli přístupu DRM k různým datům nepoužitelný /// pokud se neobjeví a hra přesto nejde spustit, tak to může znamenat nedostatečné SW vybavení na straně uživatele /// pokud se objeví před spuštěním Runaway2.exe, tak je chyba v SW nastavení uživatele -->) zásadně nedoporučuji jakýmkoli způsobem přistupovat nebo umožnit přístup (autoplay, kontroly antiVIRUS programů, a podobné kraviny) na připojený maxi-image = čím více přístupů a "ideálně" z více programů najednou, tím možných delších lagů systému (minuty až hodiny). Pokud bude maxi-image fungovat byť u jednoho dalšího uživatele, tak funguje všude (na náhody se u protipirátských ochran nehraje). Archiv s maxi-image (23MB) má po rozbalení 6GB

-kvůli chybějícímu ```runaway2.ini``` může první pokus o spuštění hry skončit červeným křížkem bez jediného písmena (ERROR)

-```RESOURCE.000``` po instalaci z DVD a v průběhu hraní je různě upravován (snad není provázán s DRM), ale i zde pokus o spuštění může skončit stejnou ERROR (stačí použít soubor z DVD vnitřně se lišící zřejmě jenom jedním písmenkem)

-```Runaway2.exe``` v sobě obsahuje starší a ve Win7 nefunkční verzi ```TagesSetup_x64.exe```

-DRM=čeština=hra jednou přestane na nových systémech fungovat (prý se už stalo https://mrakoplashgames.cz/games/runaway.php)
<br/>
Zbývající hry od Péndulo Studios v retail překladech (The Next BIG Thing 2011, Yesterday 2012) jsou zamýšlené jako online hry (i když jsou na fyzických nosičích a vyžadují speciální HW čtecí zařízení). Vyžadují online aktivaci/deaktivaci (omezený počet aktivací a životnost služeb) čímž dochází ke kontrole a porovnání uživatelského HW/SW (moc nevěřím, že by šlo detekci nějak jednoduše omezit/podvrhnout, i když teoreticky úspěšná aktivace v konkrétní verzi virtuálního PC s konkrétním "live" Win a následný přenos aktivačních dat do toho samého "live" Win, ale ve skutečnosti běžícího na jiném reálném HW by možná stálo za zkoušku) a i zde jsou překlady bez originálních EXE nepoužitelné. Takže je vyloženě nutné si počkat (i když to by měla být samozřejmost) na CZ cracky a až poté nakupovat
<br/>
https://mrakoplashgames.cz/games/the_next_big_thing.php
<br/>
https://www.alza.cz/gaming/yesterday-cz-d1634804.htm#reviews

<br/>
<br/>
<br/>
Autohotkey v1.1 https://github.com/hornster02/Runaway_2-2006-CZ/raw/main/script.rar
<br/>
```CTRL+ALT+INS``` pozastavit/spustit skript (globální klávesa)
<br/>
```CTRL+ALT+HOME``` restartovat skript (globální klávesa)
<br/>
```Launch_App2``` vypnout hru (stisknout/držet/2x stisknout - globální klávesa) - deaktivováno, uživatelsky specifický komplexnější skript
<br/>
```F10``` pozastavit/spustit hru (držet 1 vteřinu/2x stisknout - suspend, globální klávesa)
<br/>
```F11``` (držet) zabrání kurzoru myši pohyb mimo aktivní okno - přepínač
<br/>
```F12``` (držet) zapnout/vypnout borderless fullscreen - přepínač
<br/>
```kolečko dolu``` inventář
<br/>
```kolečko nahoru``` esc
