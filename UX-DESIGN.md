# User Experience Design - NextQuad

## Interactive Prototype

🔗 **[View Interactive Prototype](https://www.figma.com/design/d9sAx6JfiaAR5zUUyGk0eo/NextQuad-Wireframes?node-id=109-2&t=hrsWrP18m1sV444F-1)**

This mobile prototype demonstrates the core user flows and interactions for the NextQuad MVP, including dorm feeds, event management, campus map navigation, and user account features.


## App Map

![App Map](ux-design/prototype/app-map.png) # Just a placeholder here, need to upload app map .png file, route should be "ux-design/prototype/app-map.png"

The app map illustrates the hierarchical structure and navigation flow of the NextQuad application. The main sections include:

- **User Authentication**: Sign up and sign in flows
- **Dorm Feeds**: Community posts and social interactions within residence halls
- **Events**: Event discovery, creation, RSVP, check-in, analytics, and post-event surveys
- **Campus Map**: Interactive campus navigation and location-based features
- **Settings**: User preferences, account management, and app configuration

## Wireframes

### 1. User Authentication

**[To be completed]**


### 2. Dorm Feeds Section

**[To be completed]**


### 3. Events Section

#### 3.1 Event Main (Event Discovery)
![Event Main](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Main.png)

**Purpose**: The main landing page for discovering and browsing campus events.

**Key Features**:
- Search bar for finding specific events by keyword
- Category filters (#Music, #Social, #Study, etc.) for quick filtering
- Event cards displaying essential information:
  - Event cover image placeholder
  - Event title and date/time
  - Location
  - RSVP count ("24 going")
  - Category tags
- Bottom navigation: "My Event" and "Add Event" buttons

**User Interactions**:
- Tap any event card to view detailed event information
- Tap category filters to show only events of that type
- Use search bar to find events by keyword
- Tap "My Event" to view hosted and attended events
- Tap "Add Event" to create a new event


#### 3.2 Event Detail
![Event Detail](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Detail.png)

**Purpose**: Display comprehensive information about a specific event and allow users to RSVP.

**Key Features**:
- Event cover image placeholder (large format)
- Event title (e.g., "Fall Music Festival")
- Date, time, and location details
- "About this event" section with full description
- Host information with avatar and organization name
- Prominent "RSVP TO EVENT" button

**User Interactions**:
- Scroll to read complete event details (For now one screen contains everything so no need to scroll)
- Tap "RSVP TO EVENT" to register attendance
- View host information
- Navigate back to event list via top navigation


#### 3.3 Event RSVP Confirmation
![Event RSVP](ux-design/prototype/NextQuad_Events_Wireframes/Event%20RSVP.png)

**Purpose**: Confirm successful RSVP registration and provide event reminder.

**Key Features**:
- Success confirmation message: "✓ You're all set! See you there"
- Event summary card showing:
  - Event cover image
  - Event title
  - Date, time, and location

**User Interactions**:
- View RSVP confirmation
- Reference event details for attendance
- Navigate back to browse more events


#### 3.4 Event Create
![Event Create](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Create.png)

**Purpose**: Allow users to create and publish new campus events.

**Key Features**:
- Event photo upload area with placeholder
- Form fields for event details:
  - **Event Title**: Text input
  - **Date & Time**: Date/time picker input
  - **Location**: Text input
  - **Description**: Multi-line text input
- **Category selection**: Selectable tags (#Music, #Social, #Study, etc.)
- "Publish Event" button to submit

**User Interactions**:
- Tap photo upload area to add event image
- Fill in all required event information fields
- Select one or more category tags
- Tap "Publish Event" to create the event
- Navigate between "My Event" and "Event Main" tabs


#### 3.5 My Event (Event Management Dashboard)
![My Event](ux-design/prototype/NextQuad_Events_Wireframes/My%20Event.png)

**Purpose**: Central dashboard for event organizers to manage their events and track engagement.

**Key Features**:

- Needs Attention Section: Events requiring immediate action
    - Action buttons: "Check-ins" and "Take Survey"
- Upcoming Events: Future events with RSVP counts
    - "View Details" button for each event
- Past Events:
    - "View Stats" button to see event metrics

**User Interactions**:
- Tap "Check-ins" to check in to event
- Tap "Take Survey" to fill in post-event feedback
- Tap "View Details" for upcoming events
- Tap "View Stats" to see comprehensive event analytics
- Tap "Add Event" to create a new event


#### 3.6 Event Check In
![Event Check In](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Check%20In.png)

**Purpose**: Allow attendees to check in to events and provide location verification.

**Key Features**:
- Event cover image
- Event title (e.g., "Fall Music Festival 2")
- "Check-in Available" status indicator
- Location confirmation: "✓ You're at Kimmel Center"
- QR code display area with instruction text: "Show this to event host"

**User Interactions**:
- View check-in availability status
- Verify location automatically or manually
- Display QR code to event organizer for scanning
- Navigate between "My Event" and "Event Main"


#### 3.7 Event Survey (Post-Event Feedback)
![Event Survey](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Survey.png)

**Purpose**: Collect feedback from attendees after event completion.

**Key Features**:

- Survey Questions: Overall Rating, Multi-select checkboxes, etc.
- Action Buttons:
    - "Submit Feedback" button (primary action)
    - "Skip for now" link (secondary action)

**User Interactions**:
- Enter numeric rating
- Select multiple aspects that were enjoyed
- Choose likelihood of future attendance
- Provide optional written feedback
- Submit survey or skip to complete later


#### 3.8 Event Analytics
![Event Analytics](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Analytics.png)

**Purpose**: Provide event organizers with comprehensive metrics and insights about their event's performance.

**Key Features**:

- Key Metrics Panel
- RSVP Timeline: Visual graph showing RSVP pattern over time
- Engagement Metrics
- Insights Section: Data-driven observations
- Additional insights

**User Interactions**:
- View comprehensive event performance metrics
- Analyze RSVP patterns over time
- Review engagement rates
- Navigate to detailed insights


### Events Section User Flows:

1. **Browse & RSVP Flow**:
   Event Main → Event Detail → Event RSVP Confirmation

2. **Create Event Flow**:
   Event Main → Event Create → Event Main (with new event published)

3. **Manage Events Flow**:
   My Event → Event Analytics/Check-ins/Survey Review

4. **Attend Event Flow**:
   My Event → Event Check In → Show QR Code

5. **Post-Event Flow**:
   My Event → Event Survey → Submit Feedback → Event Analytics


### 4. Campus Map Section

**[To be completed]**


### 5. Settings Section

**[To be completed]**
