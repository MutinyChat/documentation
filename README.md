# [VERY DRAFT] Mutiny Chat documentation
## Aim
Our aim is to create a new simple open protocol based on the IRC to provide safe, stable and independent from commercial and political interests way of communication on the Internet.

## Tasks
* Server node:
  1. Implement routing between nodes using DHT
  2. Make TLS-connections between nodes mandatory
  3. Remove any client authentification
  4. Make UTF-8 the only encoding
  5. Add support for rich formatting
  6. Add support for sending media files
* Client node(Android):
  1. Implement protocol support
  2. Implement an easy way to create and manage encryption keys
  3. Implement message encryption/decryption/verification via GnuPG
  4. Implement an easy way to add a contact via QR-code(?)
  4. Implement a possibillity to make a direct connection to client nodes
  5. Implement a possibillity to route contact's list traffic through the client node
