BISHOUJO SENSHI SAILOR MOON  
ENGLISH AND HIDDEN FEATURES BY TANGOBUNNY  
VERSION 1.1.1 BPS PATCH  
============================================================  

Patch filename:  
`Bishoujo Senshi Sailor Moon - English and Hidden Features by TangoBunny v1.1.1.bps`  

This BPS patch converts the clean, original Japanese 128 KiB Game Boy ROM  
directly into the 256 KiB Version 1.1.1 English and Hidden Features ROM.  

No earlier IPS/BPS patch, Version 1.0 patch, Version 1.1 patch, or  
development-version patch should be applied first. Use the original  
Japanese ROM as the source, even when upgrading from an older translation.  

Release status:  
  Version 1.1.1 maintenance release, published 26 August 2026  
  Stable/public TangoPunk.com zine release  
  All patch files are free and may be freely distributed.  
  AI tools were used.  


DOWNLOAD VERSION 1.1.1  
----------------------  

[Release notes for v1.1.1](https://github.com/TangoBunny/GB-Sailor-Moon-English/releases/tag/v1.1.1)  
[Download Sailor.Moon.GB.TangoBunny.1.1.1.zip](https://github.com/TangoBunny/GB-Sailor-Moon-English/releases/download/v1.1.1/Sailor.Moon.GB.TangoBunny.1.1.1.zip)  

Extract this ZIP to obtain the v1.1.1 .bps patch and BPS_PATCH_README.txt.  
The packaged README confirms that this is a complete patch from the original  
Japanese ROM; it is not an incremental patch for a v1.1 translated ROM.  

Release ZIP verification (independently calculated from the download, and  
matching the SHA-256 digest published in GitHub's release-asset metadata):  

  Filename:   Sailor.Moon.GB.TangoBunny.1.1.1.zip  
  Size:       12,559 bytes  
  SHA-256:    FB172FA14044CFB28A1CD1E89713D1C8ECF6228D3FC1BFF995C630A9BD542CE1  


HOW TO APPLY THE PATCH  
----------------------  

Download and extract the v1.1.1 ZIP linked above, then:  

  1. Make a backup of your original Japanese ROM dump.  
  2. Open the .bps file in Floating IPS (Flips), or another patcher that  
     supports the BPS1 patch format. Use the v1.1.1 .bps file from the ZIP.  
  3. When asked for the source ROM, choose the clean original Japanese ROM:  

       Bishoujo Senshi Sailor Moon (Japan).gb  

  4. Save the patched result as a new .gb file. The recommended filename is:  

       Bishoujo Senshi Sailor Moon - English and Hidden Features by  
       TangoBunny v1.1.1.gb  

  5. Check the output SHA-256 in EXPECTED PATCHED ROM - VERSION 1.1.1  
     below to confirm that patching succeeded. Do not use the historical  
     Version 1.1 checksums.  

The BPS format contains source, target, and patch CRC32 checks. A compatible  
patcher should reject the wrong source ROM rather than creating a bad output.  


REQUIRED CLEAN SOURCE ROM  
-------------------------  

  Game:       Bishoujo Senshi Sailor Moon (Japan)  
  Size:       131,072 bytes (128 KiB)  
  SHA-256:    B1090AD4909F8222E4C325D8F939CB8B80DE6430F80343FDA501EDC9166CE847  
  SHA-1:      C008913A9FBB395A7A504FE65D1D29C530755CB3  
  MD5:        7AFB675171D58105112DBACF2CED77CB  
  CRC32:      C2763E73  

If the source hash differs, the dump may have a copier header, be modified,  
come from another region or revision, or be damaged. Do not force the patch  
onto it.  


EXPECTED PATCHED ROM - VERSION 1.1.1  
------------------------------------  

These output hashes are supplied by BPS_PATCH_README.txt in the v1.1.1 ZIP.  
The target size and CRC32 were also checked against the BPS patch. The output  
SHA-256, SHA-1 and MD5 have not been independently recalculated for this  
README update. The packaged README records a successful patching test using  
the required clean Japanese ROM.  

  Size:            262,144 bytes (256 KiB)  
  SHA-256:         EDBE25E627A12E66AECE6BBA5C5D54215DC7A292096AB6D20043AD9B9CAC1505  
  SHA-1:           C7464C5E7A778ABE0F82B10D43DE58B553868129  
  MD5:             03738394B23D0776A40650BBC631E3C8  
  CRC32:           BA04589B  
  Cartridge:       MBC1 (header cartridge type 0x01)  
  ROM size code:   0x03 (256 KiB)  
  Header checksum: 0x73  
  Global checksum: 0xA86C  


BPS PATCH CHECKSUMS - VERSION 1.1.1 (VERIFIED)  
--------------------------------------------  

The file size, hashes and internal BPS CRC32 below were independently  
verified from the patch in the downloaded release ZIP. The embedded source  
and target CRC32 values were read directly from the BPS patch.  

  Size:                  10,885 bytes  
  SHA-256:               5AB191365A4309175870E41E2D6DA5A0EB3AD930DBE4A1DC7B95E557D894C3D4  
  SHA-1:                 7CCDC32A2ABDC974BD5E00BFC8028560EAACE629  
  MD5:                   14929CBE920A0AFAD9F908D59A7F0E01  
  File CRC32:            2144DF1C  
  Embedded source CRC32: C2763E73  
  Embedded target CRC32: BA04589B  
  Internal patch CRC32:  F114056B  
  Format:                BPS1  
  Created with:          Deterministic local BPS1 encoder  


VERSION 1.1.1 CHANGES  
---------------------  

  - Fixed two linked action-stage defeat bugs: health no longer wraps from  
    zero to 255, and the status bar no longer incorrectly fills with heart  
    icons when Sailor Moon is defeated.  
  - All English text, graphics, hidden features, cheats, controls and  
    stage-skip behaviour from Version 1.1 are otherwise unchanged.  


VERSION 1.1 CHANGE  
------------------  

  - In a normal finite-health game, pause, hold Left, and press Select to use  
    the existing stage-skip system.  
  - The new command does not enable or set infinite health.  


MAIN FEATURES  
-------------  

  - Complete English dialogue/script in British English.  
  - Title screen changed to the classic English Sailor Moon logo.  
  - Expanded and revised English Charm descriptions.  
  - Crisp pixel-font title credits.  
  - English stage introductions for all four levels.  
  - English TAKE A BREAK pause caption in both portrait variants.  
  - Start on the title screen begins the game normally.  
  - Select on the title screen opens the hidden developer Stage Select.  
  - Stage Select entries 1-4 launch Levels 1-4.  
  - Stage Select entry 5 shows an added hidden message.  
  - Optional infinite-health mode on the Boy/Girl selection screen.  
  - Pause-screen stage skipping with finite- and infinite-health controls.  
  - Correct Queen Beryl initialization and full final-boss controls.  


LATEST CONTROLS  
---------------  

  Title:  
    Start  = begin the game normally  
    Select = open the developer Stage Select  

  Boy/Girl choice:  
    A      = confirm a normal finite-health game  
    Select = enable infinite health and confirm the highlighted choice  

  Paused gameplay:  
    Start                          = unpause  
    Hold Left, then press Select   = stage skip without infinite health  
    Select in infinite-health mode = stage skip without holding Left  
    Final boss/post-boss           = stage skip disabled  

  Original retained command:  
    A+B+Select+Start = software reset  


COMPATIBILITY  
-------------  

  - 256 KiB MBC1 Game Boy ROM.  
  - Compatible with suitable Game Boy emulators and 256 KiB-or-larger  
    MBC1-compatible flash/reproduction cartridges.  
  - An original 128 KiB mask-ROM cartridge requires physical ROM-chip  
    replacement to hold the expanded version.  


HISTORICAL VERSION 1.1 CHECKSUMS - NOT FOR VERSION 1.1.1  
------------------------------------------------------  

These values are retained for users checking an older Version 1.1 download.  
They describe the old patch and its output, not the current v1.1.1 release.  
Use the Version 1.1.1 verification sections above for the current download.  

Old patch filename:  
`Bishoujo Senshi Sailor Moon - English and Hidden Features by TangoBunny v1.1.bps`  

EXPECTED PATCHED ROM - VERSION 1.1 ONLY  
--------------------------------------  

  Size:       262,144 bytes (256 KiB)  
  SHA-256:    2160866C9FA01D4F05B7581F7FB69F62DB5E9EF2151DAEBDD06E12BD10937DA6  
  SHA-1:      09B10E92C4AF126CBFB9F2F6F1639993E258618F  
  MD5:        16E3D7719BA57FBC7376513C6F2864F0  
  CRC32:      E679F74C  
  Cartridge:  MBC1 (header cartridge type 0x01)  
  ROM size:   Header code 0x03 (256 KiB)  
  Header checksum: 0x73  
  Global checksum: 0xA355  


BPS PATCH CHECKSUMS - VERSION 1.1 ONLY  
-------------------------------------  

  Size:       10,589 bytes  
  SHA-256:    6515CEA559D7C2B8F6A20E1460389188C290FE94BEB4717620B10765685BE0BD  
  Embedded source CRC32: C2763E73  
  Embedded target CRC32: E679F74C  
  Internal BPS patch CRC32: 49504A0D  
  Created with: Floating IPS 1.98, BPS delta format  


DISTRIBUTION  
------------  

  The patch file is free and may be freely distributed. Do not distribute a  
  copyrighted Japanese ROM with it. Users should create their own clean ROM  
  dump from a legally owned cartridge.  

  English and Hidden Features version by TangoBunny  
  TangoPunk.com  
  AI tools were used.  


END OF BPS PATCH README  

