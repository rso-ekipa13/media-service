# media-service

Handles images. The app encrypts a picture before uploading it, asks this service for a short-lived upload link, and sends the file straight to Azure Blob Storage. The service keeps the metadata, enforces size limits and only gives download links to members of the conversation.

Built with .NET 10, PostgreSQL and Azure Blob Storage.

Owner: Eva Vidic. Status: planned.

## Where this fits

This is one of the repositories of [Pretty Good Pigeon](https://github.com/rso-ekipa13), an end-to-end encrypted messenger built by ekipa 13 for the Cloud Computing course at UL FRI (2026/27). The architecture, plan and decisions live in [docs](https://github.com/rso-ekipa13/docs).

`main` only changes through pull requests; day-to-day work goes to `dev`.
