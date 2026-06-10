# Privacy Policy

**Last updated:** June 2026

This privacy policy describes how this application ("the app") handles data when used with TikTok's Login Kit and Content Posting API.

## 1. Scope
The app is operated by a single developer for personal use to upload videos to the developer's own TikTok account. It is not offered to third-party users.

## 2. Data Accessed Through TikTok
When the developer authorizes the app via TikTok Login Kit, the app receives:
- TikTok username and open ID
- Basic profile information (display name, avatar URL)
- An OAuth access token and refresh token scoped to `user.info.basic` and `video.upload` / `video.publish`

The app does **not** access TikTok messages, contacts, followers, watch history, or any data belonging to other TikTok users.

## 3. How Data Is Used
- The access token is used solely to upload videos to the developer's own TikTok account via the Content Posting API.
- Username and open ID are used only to confirm which account is authenticated.

## 4. Storage and Retention
- Access tokens and refresh tokens are stored locally on the developer's machine in an environment file (`.env`) that is not committed to source control.
- No data is transmitted to any third-party server operated by the developer.
- Tokens are retained until the developer revokes access or they expire per TikTok's policy.

## 5. Sharing
The app does not sell, share, or transmit any TikTok data to any third party. All communication is directly between the app and TikTok's official API endpoints.

## 6. Deletion and Revocation
The developer may revoke the app's access at any time via TikTok account settings: https://www.tiktok.com/setting/privacy-and-safety . Upon revocation, stored tokens become invalid and are deleted from the local `.env` file.

## 7. TikTok Developer Terms
Use of the app is subject to TikTok's Developer Terms of Service: https://developers.tiktok.com/legal/

## 8. Contact
mc500.business@gmail.com
