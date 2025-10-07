---
description: >-
  Bitcoin core pēc noklusējuma makus glabā specjālā mapē wallets. lai pārbaudītu
  mapes wallets saturu ievadi komandu.
---

# Create Wallets

{% code title="Input" %}
```bash
bitcoin-cli listwalletdir
```
{% endcode %}

{% code title="Output" %}
```bash
{
  "wallets": [
  ]
}
```
{% endcode %}

Ja izvadē parādās šāds uzraksts, tas nozīmē kad mapē wallets nav neviena maka.

<kbd>Lai izveidotu jaunu maku.</kbd>

{% code title="Input" %}
```bash
bitcoin-cli createwallet "test_walet_1"
```
{% endcode %}

#### Dubultajās pēdiņās ir maka nosaukums, kuru var brīvi izvēlēties.

{% code title="output" %}
```bash
{
  "name": "test_walet_1"
}
```
{% endcode %}

