# digitalnote-swap
Use this wallet to swap your coins.

This is a **MANDATORY** update for users that still have coins on the old network that need to be swapped to the new DigitalNote chain.  *If you do not need to swap your coins, already have swapped your coins, or are withdrawing coins from an exchange like Bittrex or Upbit then you do not need to download this update and you should only be using the new DigitalNote wallet software now (https://github.com/DigitalNoteXDN/DigitalNote-2/releases).*  This software update is ONLY for users who still have coins on the old chain and this patch is MANDATORY for these users to be able to swap their coins.  Once you complete the swap process via this update and our Discord bot you can delete this old chain software and move to the new DigitalNote wallet software linked above.  You can also delete the old blockchain from your harddrive once you move to the new one.

• Detailed swap instructions are provided here: http://www.digitalnote.biz/xdn/pdf/DigitalNote_Swap_Instructions.pdf
• The latest blockchain bootstrap is provided here (use this if you face syncing issues or if you just want to speed up the process): http://bootstrap.digitalnote.biz/xdn/7.0.4_998186.zip
• App data files are located in ~/.digitalnote on Macs and ~/AppData/Roaming/digitalnote on Windows
• If you have a deposit of XDN locked for a period longer than the swap period of 6 months, please contact our team on our Discord channel for assistance (https://discord.gg/4dUquty).  If you have a deposit set to unlock in under 6 months, simply wait until your deposit is unlocked and then swap it over.  We cannot unlock locked deposits manually.
• If you require a different Linux build please contact us and we will attempt a compile for your distro.  The Linux binary we have provided was built on Linux Mint 18.1 Serena (libboost v1.58.0.1 Ubuntu1).

# Release Notes
• The TX size limit bug from original dev has been fixed, the maximum block size increase is now enabled correctly (200KB max).  This will allow larger quantities of XDN to be swapped at a time to allow for a smoother transition.
• Mining ability has been removed for users as propagating blocks on the old network will be solely handled by the DigitalNote team.  Mining reward is 0 XDN as the mining process is only to facilitate the swap process and push user's transactions to the new chain.  Do not try to mine on the old chain, there is no point.  You should be mining or staking on the new chain now.
• **The source for this release is closed source as to thwart manipulation of the old chain and to allow for a smoother transition while users continue the swap process.  The source code provided below is not the current release as this is a closed source release.  Do not attempt to compile the source code under assets or it will not connect to the current network.**

# SHA-256 Checksums
To verify that your release is official, use the following SHA-256 hashes.  We recommend a program such as "MD5 & SHA Checksum Utility" to do so (https://raylin.wordpress.com/downloads/md5-sha-1-checksum-utility/):

digitalnote_win64_v7.0.4.zip
0381BD8396764129DB4B8A1B75768058559E83C027E59D6B978BB996CBBD61F7

digitalnote_linux64_v7.0.4.zip
802DF26E6D6852497D5FC12BE9B279F68B189A1B555FB667ADD72833449CEA10

digitalnote_highsierra_v7.0.4.zip
2192D941D38C867A76F791BC4E829343C0CCDE411BDE9C4F1CF54731F0C4498B
