# Instagram Sample Data – GitHub README

This repository contains a comprehensive **sample dataset** modeled after Instagram user and social media data. The structure is ideal for developers, data scientists, and enthusiasts looking to build, test, or demonstrate social network features, analytics, or UI designs.

## 📦 Overview

The `profile.json` file represents a mock database for an Instagram-like app, including:

- **Users** with bios, profile images, followers, and following counts
- **Posts** with images, captions, likes, comments, and timestamps
- **Stories** featuring timed images for user feeds

## 🗂️ Features

- **40+ diverse user profiles**: Includes varied bios, verification status, and avatars (men/women, different interests)
- **Posts**: Each user can have multiple posts with realistic captions, hashtags, like counts, and user comments (all faux but realistic)
- **Stories**: Recent stories with timestamps and image links, linked to users
- **Image links**: Open-licensed Unsplash URLs for post and story images
- **Engagement details**: Likes, comments (with timestamps), and hashtags for richer interaction context
- **Verified Profiles**: Both regular and verified profiles included for complete UI coverage

## 📁 Example Data Structure

```json
{
  "id": 1,
  "username": "traveler",
  "fullName": "Travel Enthusiast",
  "avatar": "https://randomuser.me/api/portraits/men/32.jpg",
  "isVerified": true,
  "bio": "Exploring the world one mountain at a time 🌍",
  "followers": 12456,
  "following": 342,
  "postsCount": 3,
  "posts": [
    {
      "id": 1,
      "image": "https://images.unsplash.com/photo-1682695794816-7b9da18ed470?w=600...",
      "caption": "Beautiful view from the top! 🗻 #adventure #travel",
      "likes": 1243,
      "comments": [
        {
          "id": 1,
          "username": "adventure_seeker",
          "text": "Amazing view! Where is this?",
          "timestamp": "1 hour ago"
        }
      ],
      "timestamp": "2h"
    }
  ],
  "stories": [
    {
      "id": 1,
      "image": "https://images.unsplash.com/photo-1448375240586-882707db888b?q=80...",
      "timestamp": "3h"
    }
  ]
}
```

## 🚀 Usage

- **UI mockups and testing:** Plug into front-end frameworks (React, Vue, etc.) for Instagram-like feed demos.
- **Backend prototyping:** Simulate API responses for social feed, stories, and user profile endpoints.
- **Sample analytics:** Analyze engagement (likes, comments, follows) for data science or classroom demos.

## 🔑 Notes

- **No real user data:** All names, avatars, comments, and stats are synthetic for privacy and demo use only.
- **Images** sourced from Unsplash and RandomUser.me for open use—ensure attributions as needed.
- **Timestamps** represent relative times for testing (e.g., '5h', '2 days ago').
