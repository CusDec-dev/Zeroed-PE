
############# V1.0.0 ############# 04.09.2026
Removing DOS message: This program cannot be run in DOS mode
Removing Rich, DanS
Removing Debug directory
Removing pdb paths
Removing in .NET file DotNET version (support only v2.0 or 4.0)
Blank section names
Break ASPack Detection signature (Tested on Detect It Easy)
Break UPX Detection signature and make "upx -d" unpacking impossible (Tested on Detect It Easy and the newest upx 5.2.0)
Removing compiler signatures: il2cpp, FASM, TASM, Borland, MinGW, GCC, Clang, Microsoft Linker/Visual
Break TinyCC compiler signatures and patch EP (Tested on Detect It Easy) only for x86 files
Zeroed TimeDateStamp to minimal (1970-01-01 UTC / Unix epoch 0)
Removing signatures detection for AHTeam EP Protector (Tested on Detect It Easy)
Removing PyInstaller strings, Anti-pyinstxtractor
Normalize linker/subsystem versions
Randomize import DLL casing
#######################################

############# V1.0.1 ############# 08.09.2026
Updated compiler signatures added: DelphiLazarus, FreePascal, Go(ID), LegacyVisualBasic, Rust
Added DOS Stub some stuff
Load Config wipe when CFG is not enabled
Some debug flags 
Checksum zeroed
OS Version now zeroed
Rust compiler cleanup: *.rs paths, RustBacktraceMutex, /rustc/, cargo/std markers
Import mutation(i just update the method in "Randomize import DLL casing")
Deleted function "Removing in .NET file DotNET version (support only v2.0 or 4.0)" It's gonna break your .NET executables files, sorry:(
#######################################

############# Detect It Easy Help:) #############
https://github.com/horsicq/Detect-It-Easy/issues/379
https://github.com/horsicq/Detect-It-Easy/commit/aa4b7198f8523aec3314aff465135cc9126f7f22
#######################################

############# V1.0.2 ############# 09.09.2026
Break Obfus.h signature ( Tested on Detect It Easy )
Break ObfusHeader.h signature ( DO NOT TESTED )
Removing Borland,Delphi,C++ TDS(Turbo Debugger Symbols)
Break ASM-Guard signature with watermark ( Tested on Detect It Easy)
Fixed import mutation
Break TriProt cryptor EP signature ( Tested on Detect It Easy )
Removing LLVM/LLD markers "LLD PDB"
Patch MSVC EP marker ( safety nop ) 
RECORD!!! 2000+ Lines of code
#######################################

############# Detect It Easy Help:) #############
https://github.com/horsicq/Detect-It-Easy/issues/380
https://github.com/horsicq/Detect-It-Easy/commit/9b377a8b839db09be5e91bcf9be31ff6c0c9b92f
#######################################
      
############# V1.0.3 ############# 10.09.2026
Update "Break UPX detection signature" add EntryPoint patching and break retdec-unpacker
DO NOT removing full DOS message, before: This program cannot be run in DOS mode. after: This program cannot be run
Break MPRESS signature and break retdec-unpacker (Tested on Detect It Easy)
Removing PureBasic signature
TriProt Cryptor get removed of project
RECORD!!! 2500+ Lines of code
#######################################

SSSSSSSSSs.                                                                     .sSSSSs.    .sSSSSs.    Author: CusDec 
SSSSSSSSSSS .sSSSSs.    .sSSSSSSSs. .sSSSSs.    .sSSSSs.    .sSSSSs.            SSSSSSSSSs. SSSSSSSSSs  Github: https://github.com/CusDec-dev
     S SSS  S SSSSSSSs. S SSS SSSSS S SSSSSSSs. S SSSSSSSs. S SSSSSSSs.         S SSS SSSSS S SSS SSSS' 
    S  SS   S  SS SSSS' S  SS SSSS' S  SS SSSSS S  SS SSSS' S  SS SSSSS         S  SS SSSSS S  SS       
   S..SS    S..SS       S..SSsSSSa. S..SS SSSSS S..SS       S..SS SSSSS sssssss S..SS SSSSS S..SSsss    
  S:::S     S:::SSSS    S:::S SSSSS S:::S SSSSS S:::SSSS    S:::S SSSSS         S:::SsSSSSS S:::SSSS    
 S;;;S      S;;;S       S;;;S SSSSS S;;;S SSSSS S;;;S       S;;;S SSSSS         S;;;S       S;;;S       
S%%%SSSSSSS S%%%S SSSSS S%%%S SSSSS S%%%S SSSSS S%%%S SSSSS S%%%S SSSS'         S%%%S       S%%%S SSSSS 
SSSSSSSSSSS SSSSSsSS;:' SSSSS SSSSS SSSSSsSSSSS SSSSSsSS;:' SSSSSsS;:'          SSSSS       SSSSSsSS;:' 
                                                                                                        
                                                                       
                                             
                                             
