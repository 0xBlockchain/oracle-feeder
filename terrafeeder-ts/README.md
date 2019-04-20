# USAGE

## Install depencancies
```
$ yarn
```

## Create key by mnemonic 
```
$ yarn start update-key
Enter a passphrase to encrypt your key to disk: ********
Repeat the passphrase: ********
Enter your bip39 mnemonic : <some nice mnemonic>
saved!
✨  Done in 9.19s.
```

## Voting
```
$ yarn start vote --source "http://price.terra.money/last" --lcd "https://lcd.terra.money" --chain-id terra-0001 --denoms krw,usd
Enter a passphrase: *******
Voted : musd = xxxx.xxxxxxxxxxxxx,  txhash : 096A3C93058CC4A1B4C5F50F0CA8DF7F4F89DFA8533047AB69FCA46E32ABF860
Voted : mkrw = xxxx.xxxxxxxxxxxxx,  txhash : F2CBAF070ADF29F616670082784807220DE25307D79EF4784682752AE1A5CD9D
Voted : mcny = xxxx.xxxxxxxxxxxxx,  txhash : 7A1F109E7DD13FAC3481AD0C2670B78593CFC675E5207018EC2645B0D5FC73C0
Voted : mjpy = xxxx.xxxxxxxxxxxxx,  txhash : 33E407437F258649D8360EEA5BEBA88D1D03A6DCFC629407E3DB7A2949613951
Voted : meur = xxxx.xxxxxxxxxxxxx,  txhash : 1246F33C31C016627348DA4FC5A2DDCCE6A4F730063F85BFEFB0F4E838371D00
Voted : mgbp = xxxx.xxxxxxxxxxxxx,  txhash : 5AE5357786AB233269E0E7296C9F51F653615B8FB6962F77D5EC51501900A545
Voted : msdr = xxxx.xxxxxxxxxxxxx,  txhash : 27B19E30AE5E3F6543CF15182A13E4F14A22B16FC3FADF44DDA7F38CFD2ED651

```
