# AccessibleReddit Client
A lightweight, accessibility-focused Reddit client designed to improve usability for people with impaired hand mobility.

## Overview
AccessibleReddit provides an alternative interface for browsing Reddit with fewer precise hand movements. The app features large touch targets, simplified navigation, and optional gesture/voice-initiated controls (system-level only).

This repository hosts the codebase and documentation for the accessibility client requiring Reddit API access.

## Features
- Read-only browsing of subreddit feeds and comment threads.
- Oversized interactive UI elements.
- Gesture-based navigation.
- Optional system voice-to-text for posting/commenting.
- Reddit OAuth login for user-initiated interactions.
- No automation: no scraping, no background posting, no mass voting.

## Why API Access Is Needed
- Devvit cannot support standalone native app accessibility features.
- Gesture and voice input need system access.
- The app must fetch Reddit data dynamically to present in accessible formats.

## Code Status
This is an initial skeleton used for demonstrating the project structure to Reddit during API key evaluation. Functionality will expand once API access is granted.

## License
Apache License
