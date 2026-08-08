BISHOUJO SENSHI SAILOR MOON  
ENGLISH AND HIDDEN FEATURES BY TANGOBUNNY  
VERSION 1.0 BPS PATCH  
============================================================  

Patch filename:  
  Bishoujo Senshi Sailor Moon - English and Hidden Features by  
  TangoBunny v1.0.bps  

This BPS patch converts the clean, original Japanese 128 KiB Game Boy ROM  
into the 256 KiB Version 1.0 English and Hidden Features ROM.  

No earlier IPS patch or development-version patch should be applied first.  
Use the original Japanese ROM as the source.  

Release status:  
  Version 1.0  
  First stable/public release for the TangoPunk.com zine  
  (All patch files are free and can be freely distributed)  
  AI tools were used.  


HOW TO APPLY THE PATCH  
----------------------  
  1. Make a backup of your original Japanese ROM dump.  
  2. Open the .bps file in Floating IPS (Flips), or another patcher that  
     supports the BPS1 patch format.  
  3. When asked for the source ROM, choose the clean original Japanese ROM:  

       Bishoujo Senshi Sailor Moon (Japan).gb  

  4. Save the patched result as a new .gb file. A suggested filename is:  

       Bishoujo Senshi Sailor Moon - English and Hidden Features by  
       TangoBunny v1.0.gb  

  5. Check the output SHA-256 below if you want to confirm that patching was  
     successful.  

The BPS format contains source, target, and patch CRC32 checks. A compatible  
patcher should reject the wrong source ROM instead of creating a bad output.  


REQUIRED CLEAN SOURCE ROM  
-------------------------  
  Game:       Bishoujo Senshi Sailor Moon (Japan)  
  Size:       131,072 bytes (128 KiB)  
  SHA-256:    B1090AD4909F8222E4C325D8F939CB8B80DE6430F80343FDA501EDC9166CE847  
  CRC32:      C2763E73  

If your source hash differs, the dump may have a header, be modified, be from  
another region or revision, or be damaged. Do not force the patch onto it.  


EXPECTED PATCHED ROM  
--------------------  
  Size:       262,144 bytes (256 KiB)  
  SHA-256:    7C6EF37F4E1FFD9D1AE07B08B085FCA67C6EC9FC480F30740137942BBF28A067  
  CRC32:      BC554B3B  
  Cartridge:  MBC1 (header cartridge type 0x01)  
  ROM size:   Header code 0x03 (256 KiB)  


BPS PATCH CHECKSUMS  
-------------------  
  Size:       133,853 bytes  
  SHA-256:    DF36865356E26704D81FBE607A35BA14D60AD5FBEC354FBE56C6F50E3D7A056D  
  Internal BPS patch CRC32: 1703F667  


MAIN FEATURES  
-------------  
  - Complete English dialogue/script. (British English. I'm British.)  
  - Title screen changed to the classic English Sailor Moon logo  
  - Expanded and revised English Charm descriptions.  
  - English Sailor Moon title artwork with crisp pixel-font credits.  
  - English stage introductions for all four levels.  
  - English TAKE A BREAK pause caption in both portrait variants.  
  - Start on the title screen begins the game normally.  
  - Select on the title screen opens the hidden developer Stage Select.  
  - Stage Select entries 1-4 launch Levels 1-4.  
  - Stage Select entry 5 (which originally just loaded Level 1) now shows an  
    added hidden message.  
  - Hidden infinite-health mode activated with Select on the Boy/Girl screen.  
  - Cheat-gated pause/Select stage skipping.  
  - In infinite-health mode, corrected Queen Beryl skip initialization  
    and restored final-boss controls.  


LATEST CONTROLS  
---------------  
  Title:  
    Start  = normal game  
    Select = Developer Test Stage Select (Originally inaccessible in the ROM)  

  Boy/Girl choice:  
    A      = normal game selection (the only difference is Girl Mode gives you  
             more health than the Boy Mode)  
    Select = Newly added cheat mode, works for both Girl and Boy Mode  

  Cheat mode:  
    (Cheat mode enables infinite health)  
    Start               = pause/unpause  
    Select while paused = skip to the next main phase (only when the  
                          cheat mode mode is active)  
    Final boss          = stage skip disabled (it's the last level)  

  Original retained command:  
    A+B+Select+Start = software reset  


COMPATIBILITY  
-------------  
  - 256 KiB MBC1 Game Boy ROM.  
  - Compatible with Game Boy emulators and suitable 256 KiB-or-larger  
    MBC1-compatible flash/reproduction cartridges.  
  - An original 128 KiB mask-ROM cartridge requires physical ROM-chip  
    replacement to hold this expanded version.  


VERIFICATION  
------------  
  ROM size: 262,144 bytes  
  Cartridge type: MBC1 (header 0x01)  
  ROM size code: 0x03 (256 KiB)  
  Header checksum: 0x73  
  Global checksum: 0xAC7B  
  SHA-256: 7C6EF37F4E1FFD9D1AE07B08B085FCA67C6EC9FC480F30740137942BBF28A067  

  This patch was reapplied to the required clean Japanese ROM after creation.  
  The reconstructed output was byte-for-byte identical to the verified  
  Version 1.0 release ROM and matched its SHA-256 checksum.  


DISTRIBUTION  
------------  
  The patch file is free and may be freely distributed. Do not distribute a  
  copyrighted Japanese ROM with it. Users should create their own clean ROM  
  dump from a legally owned cartridge.  

  English and Hidden Features version by TangoBunny  
  TangoPunk.com  
  AI tools were used.  


END OF BPS PATCH README  
