# Cloud Storage

If you are currently using a Cloud Storage Service like Dropbox, Google Drive, Microsoft OneDrive or Apple iCloud, you are putting complete trust in your service provider to not look at your files.

Consider reducing the need to trust your provider, by using an alternative below that supports [end-to-end encryption](https://wikipedia.org/wiki/End-to-end_encryption) (E2EE).

## Nextcloud

> Nextcloud is a suite of free and open-source client-server software for creating your own file hosting services on a private server you control. It also comes with experimental end-to-end encryption (E2EE).
> 
> We recommend checking if your Nextcloud provider supports E2EE, otherwise you have to trust the provider to not look at your files.
> 
> When self hosting Nextcloud, you should also remember to enable E2EE to protect against your hosting provider from snooping on your data.
> 
> - [Visit nextcloud.com](https://nextcloud.com/)
> - [Privacy Policy](https://nextcloud.com/privacy/)


## Proton Drive

> Proton Drive is an end-to-end encrypted (E2EE) general file storage service by the popular encrypted email provider ProtonMail.
> 
> Proton Drive is currently in beta and only is only available through a web client.
> 
> When using a web client, you are placing trust in the server to send you proper JavaScript code to derive the decryption key and authentication token locally in your browser. A compromised server can send you malicious JavaScript code to steal your master password and decrypt your data. If this does not fit your threat model, consider using an alternative.
>
> - [Visit protonmail.com](https://protonmail.com/)
> - [Privacy Policy](https://protonmail.com/privacy-policy)


## Tahoe-LAFS (Advanced)

> Tahoe-LAFS is a free and open decentralized cloud storage system. It distributes your data across multiple servers. Even if some of the servers fail or are taken over by an attacker, the entire file store continues to function correctly, preserving your privacy and security. The servers used as storage pools do not have access to your data.
> 
> Due to the complexity of the system and the amount of nodes needed to set it up, Tahoe-LAFS is only recommended for seasoned system administrators.
> 
> - [Visit tahoe-lafs.org](https://www.tahoe-lafs.org/)

