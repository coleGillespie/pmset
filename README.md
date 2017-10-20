# known power states

## Darkwake

add info about what can happen in darkwake here

### EC.ACAttach/Maintenance
  - observed when a machine has the lid shit and AC power is plugged in
  ```
DarkWake from Normal Sleep [CDN] due to EC.ACAttach/Maintenance: Using AC (Charge:60%) 45 secs  
  ```
### XHC1/:
- observed when machine was in backback driving down the road
```
DarkWake from Normal Sleep [CDN] due to XHC1/: Using BATT (Charge:100%) 5 secs
```

## Sleep
add info about sleep here



### 'Maintenance Sleep':TCPKeepAlive=active
  - seems to happen often and is paired with an mDNS timeout
```
Entering Sleep state due to 'Clamshell Sleep':TCPKeepAlive=disabled Using Batt (Charge:61%) 483 secs 
```

### 'Clamshell Sleep':TCPKeepAlive=disabled
  - observed when closing the lid to a macbook
```
Entering Sleep state due to 'Clamshell Sleep':TCPKeepAlive=disabled Using Batt (Charge:61%) 483 secs 
```
  
  ### 'Software Sleep pid=114':TCPKeepAlive=active
  - manually putting the machine to sleep
```
Entering Sleep state due to 'Software Sleep pid=114':TCPKeepAlive=active Using AC (Charge:100%)
```

## Wake
add info about wake here
### EC.LidOpen/Lid Open: Using AC
  - observed when closing the lid to a macbook
  ```
Wake from Normal Sleep [CDNVA] due to EC.LidOpen/Lid Open: Using AC (Charge:67%) 994 secs
  ```

      
     
