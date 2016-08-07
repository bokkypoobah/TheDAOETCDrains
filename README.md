# The DAO ETC Drains
Scripts and data related to the draining of The DAO on the Ethereum ETC chain

## Summary

There are some movements of ETCs within the following The DAO split proposals on the Ethereum Classic blockchain:

* Proposal #59, sub proposal #10, 3,642,408 ETC (~ 8.7 million USD). Sub proposal voting deadline was Thu, 21 Jul 2016 03:34:56 GMT.
* Proposal #73, sub proposal #1, 6,772 ETC (~ 16,202 USD). Sub proposal voting deadline was Wed, 03 Aug 2016 07:16:53 GMT.
* Proposal #101, sub proposal #1, 269,565 ETC (~ 645,338 USD). Sub proposal voting deadline was Mon, 25 Jul 2016 18:46:42 GMT.


<br />

---

## Script To Recursively Retrieve The DAO Split Data

### New Script
This new script [theDAOETCDrains](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains) was used to generate the following data:

* On the ETC chain - [theDAOETCDrains_20160807_1255GMT.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains_20160807_1255GMT.txt)
* On the ETH chain - [theDAOETHDrains_20160807_1306GMT.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETHDrains_20160807_1306GMT.txt)

### Older Script

The older script [theDAODrains](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains) was used to generate the following data:

* [theDAODrains_ETC_20160802_1558.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_ETC_20160802_1558.txt)
* [theDAODrains_ETH_20160802_1605.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_ETH_20160802_1605.txt)

And the same older script was used to generate the following data pre-hard-fork:

* [theDAODrains_PreHF_20160626_1333.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAODrains_PreHF_20160626_1333.txt)

### Notes

The categorisation of the splits are taken from [childDaoWithdraw](https://github.com/dsystems-io/childDaoWithdraw) that is referenced from [The DAO’s Edge Cases Multisig (Post Hard Fork)](https://medium.com/edge-cases-multisig-phf-official-channel/the-daos-edge-cases-multisig-post-hard-fork-2f107380bd61#.qdjyu4d9b).

See also:

* [What is a recursive calling vulnerability?](http://ethereum.stackexchange.com/questions/6176/what-is-a-recursive-calling-vulnerability)
* [How many ethers have been drained through the recursive call attacks on The DAO?](http://ethereum.stackexchange.com/questions/6408/how-many-ethers-have-been-drained-through-the-recursive-call-attacks-on-the-dao)
* [What are the balances of The DAO and it's child DAOs on the Ethereum Classic chain?](http://ethereum.stackexchange.com/questions/7668/what-are-the-balances-of-the-dao-and-its-child-daos-on-the-ethereum-classic-cha)
* [What's happening within child DAO #59 on the ETC chain?](http://ethereum.stackexchange.com/questions/7673/whats-happening-within-child-dao-59-on-the-etc-chain?noredirect=1&lq=1)


<br />

---

## Changes To The Child DAO Balances

Here is the data showing the Baddies's child DAO and two other child DAOs with some movement in the balances as of 06:50 07/08/2016 GMT from [theDAOETCDrains_20160807_1255GMT.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains_20160807_1255GMT.txt):

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

<br />

---

## Details For Splits #59, #73 and #101

And here's some detailed data from [theDAOETCDrains_20160807_1255GMT.txt](https://github.com/bokkypoobah/TheDAOETCDrains/blob/master/theDAOETCDrains_20160807_1255GMT.txt):

### Proposal #59

      Proposal 59; SPLIT; Voting to Wed, 15 Jun 2016 05:38:01 GMT
      Open n; Passed Y; Yea 0.000000000000000200 DAO; Nay 3838630 DAO
      Deposit 0 WEI; Amount 0 WEI
      Creator 0xb656b2a9c3b2416437a811e07466ca712f5a5b5a
      Recipient 0xb656b2a9c3b2416437a811e07466ca712f5a5b5a
      
      lonely, so lonely
      
      (Baddies)
      Address      0x304a554a310c7e546dfe434669c62820b7d83490 with 11 WEI and 364240853 DAO
      ExtraBalance 0x914d1b8b43e92723e64fd0a06f5bdb8dd9b10c79 with 285.714295714285714286 ETH
        ...
        --------------------------------------------------------------------------------
        Proposal 59.10; SPLIT; Voting to Thu, 21 Jul 2016 03:34:56 GMT
        Open Y; Passed Y; Yea 0.000000000000000100 DAO; Nay 0
        Deposit 0 WEI; Amount 0 WEI
        Creator 0x7498bb5749c9801f1f7e490baf5f966dbfe4e97b
        Recipient 0xbe3ae5cb97c253dda67181c6e34e43f5c275e08b
        
        
        (Baddies)
        Address      0x10abb5efecdc09581f8b7cb95791fe2936790b4e with 3642408.52761279270689932 ETH and 364240853 DAO
        ExtraBalance 0xfde8d5f77ef48bb7bf5766c7404691b9ee1dfca7 with 0 WEI
        ...
        
<br />

### Proposal #73

      Proposal 73; SPLIT; Voting to Sat, 18 Jun 2016 16:33:00 GMT
      Open Y; Passed Y; Yea 997355 DAO; Nay 0
      Deposit 0 WEI; Amount 0 WEI
      Creator 0xa003e4b91180d3e06a03f1916fe94eb4c350850e
      Recipient 0xa003e4b91180d3e06a03f1916fe94eb4c350850e
      
      
      (Untrusted)
      Address      0x5524c55fb03cf21f549444ccbecb664d0acad706 with 1.040487359828132511 ETH and 104 DAO
      ExtraBalance 0x40b803a9abce16f50f36a77ba41180eb90023925 with 0 WEI
        --------------------------------------------------------------------------------
        Proposal 73.1; SPLIT; Voting to Wed, 03 Aug 2016 07:16:53 GMT
        Open Y; Passed Y; Yea 677220 DAO; Nay 0
        Deposit 0 WEI; Amount 0 WEI
        Creator 0xde013d0fb1b41ea3c86bb335487c52acc8484bf2
        Recipient 0xe766ac7915e126f429abd534135179144627d01a
        
        afool split again
        
        (Untrusted)
        Address      0xd98157ae53342c90cfd341417d3c856351c1df95 with 6772.203185900849465032 ETH and 677220 DAO
        ExtraBalance 0x44d4b7faaddc01c253f01d8c2c33456026c0b895 with 0 WEI
        
### Proposal #101

      Proposal 101; SPLIT; Voting to Tue, 21 Jun 2016 18:34:25 GMT
      Open Y; Passed Y; Yea 34662435 DAO; Nay 0
      Deposit 0 WEI; Amount 0 WEI
      Creator 0x5fbea6b04d5824c73a89cb8348d66492e0e4b7bf
      Recipient 0x5fbea6b04d5824c73a89cb8348d66492e0e4b7bf
      
      split909090
      
      (Infiltrated)
      Address      0xf4c64518ea10f995918a454158c6b61407ea345c with 21 WEI and 26956559 DAO
      ExtraBalance 0x7602b46df5390e432ef1c307d4f2c9ff6d65cc97 with 369.231179004682274248 ETH
        --------------------------------------------------------------------------------
        Proposal 101.1; SPLIT; Voting to Mon, 25 Jul 2016 18:46:42 GMT
        Open Y; Passed Y; Yea 0.000000000000000100 DAO; Nay 0
        Deposit 0 WEI; Amount 0 WEI
        Creator 0x79f09717c5b352078234832e5737651ddb333548
        Recipient 0x79f09717c5b352078234832e5737651ddb333548
        
        Split proposal
        
        (Infiltrated)
        Address      0x39771e2d34eda36a49ff4fa4194d7fcb839165da with 269565.591797974102411573 ETH and 26956559 DAO
        ExtraBalance 0x0f112f6698b23dd44060eca9c09f4b3463feb07f with 0 WEI
        ...

<br />

Enjoy. (c) BokkyPooBah 2016. The MIT licence.
