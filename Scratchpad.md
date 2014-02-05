/give @p wooden_sword 1 1 {display:{Name:"Firesword",Lore:["Burns well, since","it is made of wood."]},Unbreaking:1,ench:[{id:20,lvl:5}],AttributeModifiers:[0:{Name:"SuperCharge",AttributeName:"generic.attackDamage",Amount:100,Operation:0,UUIDLeast:123456,UUIDMost:234567}]}

/fill -539 83 382 -544 85 377 tnt 1 keep

/testfor @p[-563,71,476,dx=10,dy=3,dz=4,score_mspawnTest0001=0]
/scoreboard players set @p[-563,71,476,dx=10,dy=3,dz=4,score_mspawnTest0001=0] 1
/summon Zombie -547 71 473 {CanPickupLoot:0,CustomName:"Urrgghh the Stout",CustomNameVisible:1,Attributes:[{Name:zombie.spawnReinforcements,Base:0},{Name:generic.movementSpeed,Base:0.2F},{Name:generic.attackDamage,Base:0.5F},{Name:generic.maxHealth,Base:100}],Equipment:[{},{id:gold_nugget,Count:4},{},{},{id:298,Count:1}],DropChances:[0.0F,1.0F,0.0F,0.0F,0.0F]}


/summon Skeleton ~ ~1 ~ {Equipment:
  [
  {id:261,tag:{ench:[{id:48,lvl:5}]}},
  {id:313,tag:{ench:[{id:7,lvl:3}]}},
  {id:312,tag:{ench:[{id:7,lvl:3}]}},
  {id:311,tag:{ench:[{id:7,lvl:3}]}},
  {Count:1,id:397,Damage:3,tag:{SkullOwner:MunkyRiver}}],CustomName:NAME,CustomNameVisible:1,SkeletonType:1,DropChances:[0.0F,0.0F,0.0F,0.0F,1.0F]}
  
  
/setblock -567 78 542 stone
/setworldspawn -567 80 542

/summon Zombie -578 77 293 {Attributes:[{Name:generic.followRange,Base:80}]}

