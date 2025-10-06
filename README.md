# Start bitcoin core

Lai startētu bitcoin core fona režīmā ievadi komandu ar parametru.

{% code title="Input" %}
```bash
bitcoind -daemon
```
{% endcode %}

{% code title="Output" %}
```bash
Bitcoin Core starting
```
{% endcode %}

Bet lai pārbaudītu.

{% code title="Input" %}
```bash
bitcoin-cli getblockchaininfo
```
{% endcode %}

{% code title="Output" %}
```bash
{
  "chain": "main",
  "blocks": 917942,
  "headers": 917942,
  "bestblockhash": "00000000000000000001bde696bd82a3e76e59f585e9d36fc1a1cebe8d5b8b78",
  "difficulty": 150839487445890.5,
  "time": 1759780197,
  "mediantime": 1759773467,
  "verificationprogress": 0.9999998112320316,
  "initialblockdownload": false,
  "chainwork": "0000000000000000000000000000000000000000e919f3e3402aa50a49b4b4df",
  "size_on_disk": 787098469235,
  "pruned": false,
  "warnings": ""
}
```
{% endcode %}

Lai apturētu bitcoin core

{% code title="Input" %}
```bash
bitcoin-cli stop
```
{% endcode %}

{% code title="Output" %}
```bash
Bitcoin Core stopping
```
{% endcode %}
