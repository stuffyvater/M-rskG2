Shipment

whitelist: Array<Address>
documents: Array<Document>
admin: Address

- whitelistStakeholder(Address) -> whitelist
- amendDocument(Address, string)

---

Document

author: Address
fingerprint: string

- updateDocument(newFingerprint: string): ???
- verifyDocument(fingerprint: string): bool
