# PlayPal Frontend

## Project Overview

### Project Name: PlayPal
- Frontend Repo: [PlayPal Frontend Repo](https://github.com/Big-Cow-King/PlayPal-Frontend)
- Backend Repo: [PlayPal Backend Repo](https://github.com/Big-Cow-King/PlayPal-Backend)

PlayPal aims to simplify the process of finding sports partners and organizing sports activities while fostering a community of sports enthusiasts. The web application allows users to create, join, or be invited to sports events or rooms based on location, sport of choice, and availability. Users can view event details such as date, time, location, and duration, as well as engage in group discussions and private chats.

## Key Users

1. **Sports Enthusiasts:** Individuals seeking partners for sports activities, benefiting from finding events and people matching their interests and schedules.
2. **Team Organizers:** Organizers of team sports activities can efficiently manage players, locations, and matches.
3. **Event Organizers:** Organizations hosting events can arrange, manage registrations, and communicate with participants effectively.
4. **Clubs & Communities:** Clubs can manage events, grow their community, and engage members by promoting activities and events through the platform.

## Scenario Examples

- **Ben and Steven:** Professional players seeking partners for badminton doubles create an event on PlayPal, allowing nearby users to see event information and request to join.
- **UTM Tennis Club:** Organizes recurring tennis games using PlayPal, managing groups, sending reminders, and updating schedules efficiently.

## Software Engineering Principles

### Next JS + Django

- **Modularity:** Utilize Django's app structure and Next JS's component-based approach for reusable modules and UI elements.
- **Separation of Concerns:** Django's MVT pattern separates logic, data, and presentation layers, while Next JS employs component-based structure.
- **Anticipation of Change:** Apply normalization to database modules in Django and utilize flexible design patterns.
- **Abstraction:** Abstract queries and operations in Django using ORM and utilize custom hooks and components in Next JS.
- **Loose Coupling and Cohesion:** Employ RESTful API design in Django and manage state locally within components in Next JS.

## Design Principles

- **Connectivity:** Dedicated chat functions for events and personal interactions foster community engagement.
- **Flexibility:** Support a wide range of sports and user skill levels for both spontaneous matches and planned events.
- **Reliability:** Ensure event information is constantly updated and accurate.
- **Privacy:** Safely store and encrypt user data, allowing users to control their information and visibility.

## Getting Started

1. Clone the repository:

```
git clone https://github.com/Big-Cow-King/PlayPal-Frontend.git
```

2. Install dependencies:

```
npm install
```

3. Run the development server:

```
npm run dev
```

4. Open http://localhost:3000 in your browser to see the result.

You can start editing the pages by modifying `app/page.js`. The page will auto-update as you edit the file.

This project utilizes `next/font` to optimize and load Inter, a custom Google Font.

Let's make sports more accessible and enjoyable for everyone! 🏀🏈🎾
