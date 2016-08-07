# TheDAOETCDrains
Scripts and data related to the draining of The DAO on the Ethereum ETC chain

# Script To Recursively Retrieve The DAO Split Data

## New Script
This new script [theDAOETCDrains](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains) was used to generate the following data for the ETC chain:

* [theDAOETCDrains_20160807_0650.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains_20160807_0650.txt)

## Older Script

The older script [theDAODrains](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains) was used to generate the following data:

* [theDAODrains_ETC_20160802_1558.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_ETC_20160802_1558.txt)
* [theDAODrains_ETH_20160802_1605.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_ETH_20160802_1605.txt)

And the same older script was used to generate the following data pre-hard-fork:

* [theDAODrains_PreHF_20160626_1333.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_PreHF_20160626_1333.txt)

<br />

---

# Changes To The Child DAO Balances

Here is the data showing the Baddies's child DAO and two other child DAOs with some movement in the balances as of 06:50 07/08/2016 GMT from [theDAOETCDrains_20160807_0650.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains_20160807_0650.txt):

    --- SUMMARY ---
    Type                #                      Balance                 ExtraBalance                       Tokens Address
    ------------ -------- ---------------------------- ---------------------------- ---------------------------- ------------------------------------------
    Baddies      0:59             0.000000000000000011       285.714295714285697159   364240852.7612792849540710 0x304a554a310c7e546dfe434669c62820b7d83490
    Baddies      0:59:10    3642408.527612792793661356         0.000000000000000000   364240852.7612792849540710 0x10abb5efecdc09581f8b7cb95791fe2936790b4e
    ...
    Untrusted    0:73             1.040487359828132563         0.000000000000000000         104.0487359828132412 0x5524c55fb03cf21f549444ccbecb664d0acad706
    Untrusted    0:73:1        6772.203185900849348400         0.000000000000000000      677220.3185900849057361 0xd98157ae53342c90cfd341417d3c856351c1df95
    ...
    Infiltrated  0:101            0.000000000000000021       369.231179004682303457    26956559.1797974072396755 0xf4c64518ea10f995918a454158c6b61407ea345c
    Infiltrated  0:101:1     269565.591797974077053368         0.000000000000000000    26956559.1797974072396755 0x39771e2d34eda36a49ff4fa4194d7fcb839165da

Here is the corresponding data showing the same accounts as of 15:58 02/08/2016 AEST from [theDAODrains_ETC_20160802_1558.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_ETC_20160802_1558.txt):

    Type         #                      Balance                 ExtraBalance                       Tokens Address
    ---------- --- ---------------------------- ---------------------------- ---------------------------- ------------------------------------------
    Baddies     59         0.000000000000000011       285.714295714285714286   364240852.7612792849540710 0x304a554a310c7e546dfe434669c62820b7d83490
    ...
    child DAO   73      6773.243673260677597543         0.000000000000000000      677324.3673260677605867 0x5524c55fb03cf21f549444ccbecb664d0acad706
    ...
    child DAO  101         0.000000000000000021       369.231179004682274248    26956559.1797974072396755 0xf4c64518ea10f995918a454158c6b61407ea345c
    
Here is the corresponding data showing the same accounts as of 13:33 26/06/2016 GMT pre-hard-fork from [theDAODrains_PreHF_20160626_1333.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_PreHF_20160626_1333.txt):

    Type         #                      Balance                 ExtraBalance                       Tokens Address
    ---------- --- ---------------------------- ---------------------------- ---------------------------- ------------------------------------------
    Baddies     59   3641694.241898506992612617         0.000010000000000000   364169424.1898506879806519 0x304a554a310c7e546dfe434669c62820b7d83490
    ...
    child DAO   73      6773.243673260677597543         0.000000000000000000      677324.3673260677605867 0x5524c55fb03cf21f549444ccbecb664d0acad706
    ...
    child DAO  101    268320.817835378784685843         0.000000000000000000    26832081.7835378795862198 0xf4c64518ea10f995918a454158c6b61407ea345c
