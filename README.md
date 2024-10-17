# Minecraft Item Transfer Protocol (MITP)

## About
MITP is a protocol for item transfer within Minecraft using [ComputerCraft](https://github.com/dan200/ComputerCraft). The goal is to establish an efficient connection between devices for the reliable exchange of items and data in Minecraft. MITP simulates the behavior of a basic TCP/IP protocol to ensure transmission reliability and security.

## Features
- Item Transfers: Protocol designed to send items between computers within Minecraft.
- Session Management: Session management to maintain reliable connections between devices.
- Message Validation: Validation of incoming data, including headers and checksums.
- Secure Connections: Implementation of authentication and data encryption functions.
- Ephemeral Ports: Use of ephemeral ports for temporary communications.
- Logs system: Activity logging for auditing and debugging purposes.

## Future Features
* parseRequest(): Parse incoming requests.
* buildResponse(): Build responses to requests.
* ParseMessageBody(): Parse the message body.
* verifyCredentials(): Verify authentication credentials.
* HandleError(): Handle errors.
* sendErrorResponse(): Send an error response.
* encryptData(): Encrypt data before transmission.
* checkAccessPermissions(): Verify access permissions.
* emitEvent(): Emit events for monitoring.
* getSupportedVersion(): Get the supported version of the protocol.

## Changelog
### 0.5v
- Session creation.
- Message validation.
- Implementation of checksums.

## License
This project is licensed under the GNU v3 License. See the [LICENSE](./LICENSE) file for more details.

## Credits
Developed by DarThunder.
