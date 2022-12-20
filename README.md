# Yamaha-RX-A820-pcap

This repository is a detailed packet capture of the Yamaha RX-A820 wireless protocol allowing the control of the device wirelessly.

You can find each packet at their corresponding files in the `packets` folder.

# Headers

the protocol uses the following HTTP headers.

| Header       | content                        |
|--------------|--------------------------------|
| Content-Type | text/xml; charset="utf-8"      |
| User-Agent   | AV Controller/5.60 (Android)   |
| Accept       | \*/\*                          |

you must send the packets to `/YamahaRemoteControl/ctrl` as POST requests.

# Contribution

If you wish to contribute to this project PRs are welcome.

# License

This repository is licensed under the MIT license.
