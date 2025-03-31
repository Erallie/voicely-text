# **Privacy Policy**

**Last Updated:** March 31, 2025

Gozar Productions LLC ("Company," "we," "us," or "our") values your privacy. This Privacy Policy explains how we collect, use, store, and disclose information when you use our text-to-speech bot, **Voicely Text** (the "Service").

By using the Service, you acknowledge that you have read and understood this Privacy Policy. If you do not agree, please discontinue use of the Service.

---

## **1. Information We Collect**

We do not collect personally identifiable information beyond what is necessary for the Service's functionality. The following data is processed:

- **Discord User ID & Server ID:**
  - **User IDs** are stored in a JSON file to maintain user preferences.
  - **Server IDs** are stored in a JSON file to maintain server settings.
  - Both are also temporarily logged for **debugging purposes** and deleted when the bot restarts.
- **Message Content:**
  - Used to generate text-to-speech (TTS) files, which are **immediately deleted** after processing.
  - Temporarily logged for **debugging purposes** and deleted when the bot restarts.
    - If a message contains a **Discord @mention**, the bot-specific nickname or server nickname of the mentioned user may be **temporarily included in logs** but is **deleted upon bot restart**.
  - Includes bot commands used to set **User & Server Preferences**, which are stored in a JSON file:
    - **Autoread:** Controls whether messages are automatically read when the user joins a voice channel (`true` or `false`).
    - **Accent:** A supported IETF language tag that determines the bot's voice.
    - **Region:** A specified top-level domain that affects the accent. The supported top-level domains include those listed on [Google's supported domains](https://www.google.com/supported_domains), plus `us`.
    - **Nickname & Server-Specific Nicknames:** Custom text specified by the user, used when the bot refers to them (e.g., when announcing a text-to-speech message). **Nicknames are encrypted at rest.**
    - **Server Settings:**
      - **Autoread** (default for the server).
      - **Accent** (default for the server).
      - **Region** (default for the server).
      - **Timeout:** An integer value specifying the duration of inactivity before the bot automatically leaves the voice channel.
      - **Admin Roles:** A list of server role IDs that have access to admin-only commands.

- **Channel IDs:**
  - **Temporarily included in logs** for debugging purposes and **deleted upon bot restart**.

We **do not** collect or process sensitive personal information (e.g., names, email addresses, IP addresses).

---

## **2. How We Use Your Information**

We use the collected data **exclusively** to:
- Provide and improve the **Voicely Text** Service.
- Store and apply **user and server preferences**, including nicknames.
- Debug and troubleshoot errors via **temporary logs** (deleted upon bot restart).

We do **not** sell, trade, or share user data with third parties.

---

## **3. Data Retention & Deletion**

We retain your data **only as long as necessary**:
- **User & Server Preferences:** Stored indefinitely unless deleted via bot commands by the user or server admin.
- **TTS Message Content:** Immediately deleted after the TTS file is generated.
- **Debug Logs:** Stored temporarily and **deleted upon bot restart**.

### **Server Data & Bot Removal**

If the bot is removed from a server, its stored data (including preferences and nicknames) is **not automatically deleted**. Users can manually delete server data using bot commands.

### **How to Delete Your Data**

- You can delete **user or server preferences**, including nicknames, using the appropriate bot commands.
- For additional deletion requests, contact us at **[erika@gozarproductions.com](mailto:erika@gozarproductions.com)**.

---

## **4. Data Security**

We take reasonable measures to protect the data stored by the bot:
- **Nicknames are encrypted at rest** per Discord’s Developer Policy.
- All temporary logs are deleted upon bot restart.

However, **no method** of transmission over the internet is **100% secure**, and we cannot guarantee absolute protection.

---

## **5. Your Privacy Rights**

### **For EU/EEA Users (GDPR Rights)**

If you are in the European Economic Area (EEA), you have the right to:
- **Access & correct** your stored preferences.
- **Request deletion** of stored data.
- **Object to processing** (though this may prevent use of the Service).
- **Withdraw consent** (where applicable).

### **For California Users (CCPA Rights)**

If you are a California resident, you have the right to:
- **Know what data we collect** and how we use it.
- **Request deletion** of stored data.
- **Opt-out of data sales** (we do not sell your data).

To exercise your rights, contact us at **[erika@gozarproductions.com](mailto:erika@gozarproductions.com)**.

---

## **6. Third-Party Services**

This Service operates within **Discord** and does not control Discord’s data policies. We encourage you to review **[Discord’s Privacy Policy](https://discord.com/privacy)** for more information.

Additionally, Voicely Text uses **gTTS**, an open-source tool that sends message content to a public Google endpoint for speech generation. While this is not part of Google Cloud's official Text-to-Speech API, the message content is still transmitted to and processed by **Google servers**, and is therefore subject to **[Google’s general Privacy Policy](https://policies.google.com/privacy)**.

---

## **7. Children's Privacy**

The Service is **not intended for children under 13**. If we learn that a child's data has been collected, we will take immediate steps to delete it.

---

## **8. Changes to This Privacy Policy**

We may update this Privacy Policy periodically. Updates will be posted here, and significant changes may be announced through Discord or our website.

---

## **9. Contact Us**

If you have questions about this Privacy Policy, contact us at:

- **Email:** [erika@gozarproductions.com](mailto:erika@gozarproductions.com)
