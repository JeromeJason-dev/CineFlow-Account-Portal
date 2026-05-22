# CINEFLOW CONTENT CREATOR REGISTRATION PORTAL

CineFlow is a clean, semantic HTML5-based onboarding interface designed for aspiring content creators to register and join the CineFlow network. The platform features native multimedia integration to guide incoming talent alongside client-side form validations to ensure data consistency before server-side processing.

---

## FEATURES

*   **Multimedia Resource Integration:** 
    *   Embedded promotional network video supporting multi-format fallback mechanics (`.mp4` and `.webm`).
    *   Interactive helpful tips audio track to assist onboarding applicants natively.
*   **Strict Client-Side Validation:**
    *   **Alphanumeric Username Guard:** Enforced through native Regex formatting to reject white spaces and special characters.
    *   **Age Verification Layer:** Hardcoded contextual baseline capping the native date selector to ensure all registrants are 18+ years of age.
    *   **Dynamic Data Controls:** Implements specific range sliders for volume forecasting and explicit file type controls (`.jpg`, `.png`) for user profile avatars.
*   **Semantic Layout Design:** Segmented cleanly into intuitive contextual groups using standard `<fieldset>` and accessible, user-interactive `<label>` components.

---

##  PROJECT STRUCTURE

To keep the platform's multimedia features loading seamlessly, ensure your local workspace matches the following layout configuration:

```text
cineflow-portal/
│
├── index.html                  # Core normalized onboarding page layout
└── assets/                     # Media asset directory
    ├── images/
    │   └── logo-poster.jpg     # completely lowercase asset path
    ├── videos/
    │   ├── promo-video.mp4     # Space strings removed for web safety
    │   └── promo-video.webm    # Safe, lowercase structural format path
    └── audio/
        └── onboarding-tips.mp3     # Clean, readable production audio guide

```

## TECHNOLOGIES USED
HTML5

## GETTING STARTED

### Installation
1. Clone the repository:
```
bash 
git clone https://github.com/JeromeJason-dev/CineFlow-Account-Portal.git

cd CineFlow-Account-Portal
```

## FUTURE ROADMAP
* [] Add CSS styling for polished visual design
* [] Add Mobile responsiveness

## LICENSE
This project is licensed by the MIT license

## PURPOSE
It's aimed to create an environment where new content creators can build their brand and interact with other well established content creators.

## COPYRIGHT
&copy; 2026 CineFlow-Account-Portal