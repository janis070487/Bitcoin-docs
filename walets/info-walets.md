# Info Walets

Lai skatītu pilnu informācīju par ielādētu, aktīvu maciņu.

{% code title="Input" %}
```bash
bitcoin-cli -rpcwallet=wallet_nosaukums getwalletinfo
```
{% endcode %}

{% code title="Output" %}
```json
{
  "walletname": "wallet_nosaukums",
  "walletversion": 169900,
  "balance": 0.00000000,
  "txcount": 0,
  "unlocked_until": 0,
  "private_keys_enabled": true
}

```
{% endcode %}

Parādās info:

* kāds ir maciņa nosaukums,
* vai tas ir šifrēts,
* Maka bilance,
* vai tam ir privātās atslēgas, utt.
