```mermaid
flowchart LR
  killerwhale[Killer Whales<br>Apex Predator]
  seal[Sea Lions]
  barracuda[Barracuda]
  dolphin[Dolphins<br>Apex Predator]
  
  squid[Squid]
  penguin[Penguins]
  krill[Krill]
  clam[Clams]

  sardine[Sardines]
  cod[Cod<br>Fish] 
  salmon[Salmon<br>Fish]
  herring[Herring<br>Fish]
  tuna[Tuna<br>Fish]
  
  
  anchovie[Anchovies]
  
  %%Plants
  plankton[Plankton]
  algae[Algae]
  
  photosyn[Photosynthesis]
    
  plankton -- Uses --> photosyn
  algae -- Uses --> photosyn
  
  
  %% First Stage
  krill -- Eats --> plankton
  krill -- Eats --> algae
  
  clam -- Eats --> plankton
  clam -- Eats --> algae
  
  sardine -- Eats --> plankton
  anchovie -- Eats --> plankton
  
  tuna -- Eats --> squid
  tuna -- Eats --> herring
  tuna -- Eats --> clam
  
  squid -- Eats --> plankton
  squid -- Eats --> algae
  squid -- Eats --> krill
  squid -- Eats --> clam
  squid -- Eats --> squid
  
  cod -- Eats --> herring
  cod -- Eats --> clam
    
  killerwhale -- Eats --> seal
  killerwhale -- Eats --> salmon
  killerwhale -- Eats --> herring
  killerwhale -- Eats --> tuna
  killerwhale -- Eats --> penguin
  
  penguin -- Eats --> krill
  penguin -- Eats --> squid
  penguin -- Eats --> sardine
  penguin -- Eats --> anchovie
  penguin -- Eats --> cod
      
  dolphin -- Eats --> squid 
  
  salmon -- Eats --> herring
  salmon -- Eats --> krill
  salmon -- Eats --> squid
  
  seal -- Eats --> penguin
  seal -- Eats --> krill
  seal -- Eats --> herring
  seal -- Eats --> squid
  seal -- Eats --> salmon
  
  herring -- Eats --> plankton
  herring -- Eats --> krill
  
  barracuda -- Eats --> anchovie
  barracuda -- Eats --> herring
  barracuda -- Eats --> tuna
  
  

```
