# Privacy Policy — Telegram Archive

**Last updated:** November 3, 2026

## Purpose

Telegram Archive is a personal-use application intended to copy messages that its owner can access in Telegram into the owner's Google Drive for searching and summarization.

## Data processed

The application may process Telegram message text, captions, message identifiers, timestamps, sender identifiers and links to messages. It also processes Google OAuth credentials necessary to access files the application creates.

## Google data access and use

The application requests the Google Drive `drive.file` scope. It uses this permission to create, read and update its own archive and state files in the authorized Google account. It does not request permission to read unrelated Google Drive files. Google OAuth credentials are intended to be kept in private GitHub Actions secrets, not in this public repository.

## Storage and third parties

Archived messages are stored in the owner's Google Drive. Scheduled execution uses GitHub Actions; source messages originate from Telegram. Data is processed by the infrastructure of these services in the course of operating the archive. If the owner separately uses ChatGPT to analyze the files through a connected Google Drive account, that is an additional, owner-initiated data transfer governed by the applicable service settings and policies.

The application does not intentionally sell personal information or share the archive with advertisers. The owner controls sharing settings and access to the Google Drive archive.

## Retention and deletion

Archive files remain in the owner's Google Drive until deleted by the owner. The owner can disconnect the Google authorization in Google Account settings and remove the scheduled workflow and its credentials in GitHub.

## Security

The application is designed to store access tokens and Telegram sessions in private GitHub Actions secrets. No security system guarantees absolute protection; the owner is responsible for securing their Google, Telegram and GitHub accounts.

## Contact

For privacy-related requests, use the GitHub repository owner's profile: https://github.com/rusalchuk

This policy describes the intended behavior of the open-source-style personal tooling as configured by its owner. It is not a representation that the service has already been deployed.
