VIDEO OF THE SCRIPT: https://streamable.com/5g07mk

## PRS-POLICEREFILL ##

## CREATED FOR FREE-USE ##

## THIS SCRIPT IS NOT GONNA BE REPOSTED OR SOLD IN ANYWAY! ##

## PRS#4932 - PRS#4932 ##

## BUCKO EDIT.. added ammo refill  so you dont have to keep getting new gun you can now just get ammo 

CHECK OUT PRS DISCORD  https://discord.gg/hytJd6VPCD 

REVIEW
![image](https://user-images.githubusercontent.com/43683580/177974566-e4ddc435-0a58-4190-a4f1-52fe119521d5.png)


 too add more ammo go to  server >  line75###

```
Player.Functions.AddItem('pistol_ammo', 12)
Player.Functions.AddItem('your ammo name', how many to give )
    TriggerClientEvent("inventory:client:ItemBox", source, QBCore.Shared.Items['pistol_ammo'], "add")
    TriggerClientEvent("inventory:client:ItemBox", source, QBCore.Shared.Items['your ammo name'], "add")

end) 
