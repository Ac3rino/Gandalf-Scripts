#Script to disable an AD user and hide from GAL
$pn = Read-Host -Prompt "Input user's first and last name (John Doe)"
Disable-ADAccount -Identity $pn
Set-ADUser $pn -Add @{msExchHideFromAddressLists="TRUE"}
