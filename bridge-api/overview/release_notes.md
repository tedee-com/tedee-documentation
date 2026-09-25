 ![](/assets/github-logo.svg "GitHub Logo") [Edit on Github](https://github.com/tedee-com/tedee-documentation/blob/master/bridge-api/overview/release_notes.md)

## PIN management

New endpoints to manage the PIN codes stored on a Tedee Lock:

- `GET /lock/{deviceId}/pin` - list the PINs (id and alias)
- `POST /lock/{deviceId}/pin` - create a PIN
- `GET /lock/{deviceId}/pin/{pinId}` - get one PIN with its code and access schedule
- `PUT /lock/{deviceId}/pin/{pinId}` - update a PIN
- `DELETE /lock/{deviceId}/pin/{pinId}` - delete a PIN

See [Endpoints: Pin](/#tag/Pin).
