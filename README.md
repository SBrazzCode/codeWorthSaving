# codeWorthSaving
A collection of modular code that I found/made and decided I wanted to keep

# Table of Contents #
- [Scripting](#scripting)
  - [Powershell](#powershell)

# Scripting
### PowerShell

##### CheckSum One-Liner ######

`get-filehash ./relativeLocationOfFileToCompare | select -expandproperty hash | compare-object theHashYouWantToCompare`

i.e.

`get-filehash .\kali-linux-2020.4-vbox-i386.ova | select -expandproperty hash | compare-object 64f6ca69ccb3efc79e350977d33109c380a744c26158c4e3956141535242e2ca`
