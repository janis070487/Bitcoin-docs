# Walets

Visi Bitcoin core maki glabājas specjālā mapē walets. Kad pirmo reizi palaid bitcoin core ar comandu

{% code title="Input" %}
```
bitcoind -daemon
```
{% endcode %}

Mape walets ir tukša. Lai tur parādītos tur kāds maks tas ir jaizveido. Kad izveido maku mapē walets

izveidojas atsevišķa mape kuras nosaukums būs, kādu nosaukumu ievadījāt izveidošanas laikā.

Un tanī mapē jau glabājas visi saistītie dati kas ir saistīts ar to maku.&#x20;

Vārdu sakot

Fiziski visi maciņu dati (atslēgas, bilance, transakciju vēsture utt.) glabājas **failu sistēmā**, mapē:

```ini
~/.bitcoin/wallets/
```

Katra maciņa katalogā ir dati (`wallet.dat`, `database`, `descriptor.json` u.c.) — tie ir  glabājas uz diska un nau pieejami.

Kad atkārtoti tiek startēt `bitcoind`, tas **neielādē nevienu maku automātiski**, ja vien `bitcoin.conf` nav norādīts:

```ini
wallet=<nosaukums>
```
