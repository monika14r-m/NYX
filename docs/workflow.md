# How Nyx Works

## 1. Create an Event

A user creates an event.

Nyx generates:
- Event ID
- Invite Code
- QR Code

---

## 2. Join Event

Participants join using:
- QR Code
- Invite Code

---

## 3. Capture Photos

Users take photos inside the Nyx camera.

---

## 4. Upload

Each photo is:

- Compressed
- Added to offline queue (if needed)
- Uploaded to AWS S3

---

## 5. Live Sync

Backend notifies every participant through WebSockets.

Every gallery updates instantly.

---

## 6. Gallery

Users can:

- View everyone's photos
- Filter by participant
- Download
- Share
