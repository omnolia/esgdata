# ESGdata

<a href="https://stromdao.de/" target="_blank" title="STROMDAO - Digital Energy Infrastructure"><img src="./static/stromdao.png" align="right" height="85px" hspace="30px" vspace="30px"></a>

Based on [DID-JWT](https://github.com/decentralized-identity/did-jwt) and [EthrDID](https://github.com/uport-project/ethr-did/).

## Configuration

Install using Node-RED Package Manager (Palett)

### Usage

#### Sample

#### Create JWT
If a new `msg.paylaod` is received a DID in JWT format will be returned as `msg.payload`. Ensure typeof `msg.payload` is an JSON-Object.

#### Validate/Resolve from JWT
If a new `msg.payload` is received with a JWT it gets validated. On success `msg.payload` contains orignal payload (from creation) and `msg.issuer` the publicKey (Identifier) of the origin.


