# Load walets

Tanī brīdī kad tiko izveido maku, tas nau jāielādē. Maks automātiski ir ielādēts un ir pieejams

Bet tiklīdz apstādini bitcoind procesu, visi maki tiek šifrēti failā saglabāti uz cietā diska un izdzēsti no RAM.

Tiklīdz atkārtoti startē bitcoind maki ir jāielādē operatīvajā atmiņā lai tos var izmantot. ar komandu&#x20;

```
bitcoin-cli loadwallet Wallet_nosaukums
```

"Wallet\_nosaukums" raksti tā maka nosaukumu kuru vēlies ielādēt.

Ja nezini precīzi kādi maki ir mapē walets izmanto komandu.

```
bitcoin-cli listwalletdir
```

Bet lai pārbaudītu kādi maki ir ielādēti un var izmantot izmanto komandu

```
bitcoin-cli listwallets
```

Brt lai kādu maku atslēkgtu.

```
bitcoin-cli unloadwallet "Wallet_nosaukums"
```
