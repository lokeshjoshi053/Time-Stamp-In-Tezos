# Time-Stamp-In-Tezos
Trusted timestamping on the Tezos blockchain.

****About
TzStamp is a cryptographic timestamping service that uses the Tezos blockchain to prove a file existed at or before a certain time.

****Stamp and Verify
To create a timestamp, choose a file to calculate its SHA-256 hash locally in your browser. Alternatively, hash the file yourself and paste the hexadecimal representation into the corresponding field. The stamp button will send the hash to the api.tzstamp.io aggregator server, which will include your file hash in its next publication. Your browser will be prompted to download a partial timestamp proof file. Once published to the blockchain, your timestamp proof will become verifiable.

To verify a timestamp, choose a file (or enter its hash) and a corresponding timestamp proof. The verify button will contact the mainnet.tezos.marigold.dev public Tezos node to verify the proof and display the timestamp. If the timestamp proof is partial, your browser will be prompted to download a full proof.

The aggregator root is published every five minutes.

