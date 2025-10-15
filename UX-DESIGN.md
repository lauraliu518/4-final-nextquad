# User Experience Design - NextQuad

## Interactive Prototype

🔗 **[View Interactive Prototype](https://www.figma.com/design/d9sAx6JfiaAR5zUUyGk0eo/NextQuad-Wireframes?node-id=109-2&t=hrsWrP18m1sV444F-1)**

This mobile prototype demonstrates the core user flows and interactions for the NextQuad MVP, including dorm feeds, event management, campus map navigation, and user account features.


## App Map

![App Map](ux-design/prototype/app-map.png) # Just a placeholder here, need to upload app map .png file, route should be "ux-design/prototype/app-map.png"

The app map illustrates the hierarchical structure and navigation flow of the NextQuad application. The main sections include:

- **User Authentication**: Sign up and sign in flows
- **Dorm Feeds**: Community posts and social interactions within residence halls
- **Campus Map**: Interactive campus navigation and location-based features
- **Events**: Event discovery, creation, RSVP, check-in, analytics, and post-event surveys
- **Settings**: User preferences, account management, and app configuration

## Wireframes

### 1. User Authentication

**[To be completed]**


### 2. Dorm Feeds Section

**[To be completed]**


### 3. Campus Map Section
#### 3.1 Campus Map Main
![Event Main](ux-design/prototype/NextQuad_CampusMap_Wireframes/Campus_Map_Default.png)
  
**Purpose**:  
To provide users with a clear and interactive map interface for exploring campus locations and accessibility features.

**Key Features**:
- Displays multiple **map pins** marking campus facilities and buildings.  
- Includes a **Filter dropdown** for accessibility and other facilities customization.  
- Features a **hamburger menu** for navigation to other app sections (Feed, Events, Profile, Settings).  
- Zoom controls located at the bottom-right corner for easy map adjustment.

**User Interactions**:
- Tap any **map pin** to view location details.  
- Tap **Filter** to open accessibility options.  
- Use **zoom icons** to navigate the map at different scales.  
- Access additional pages through the **menu icon**.

#### 3.2 Campus Map Filter
![Event Main](ux-design/prototype/NextQuad_CampusMap_Wireframes/Campus_Map_Filter.png)
**Purpose**:  
To allow users to customize the map view based on specific accessibility needs.

**Key Features**:
- Dropdown expands to show **checklist filters** such as:
  - Wheelchair Accessible  
  - Step-Free Routes  
  - Automatic Doors  
  - Elevator Access  
  - Braille Signage  
  - Hearing Loop  
- **Save button** applies selected filters and refreshes the map view.

**User Interactions**:
- Tap on **Filter** to expand or collapse the menu.  
- Select or deselect checkboxes to adjust preferences.  
- Press **Save** to update the displayed locations.  

#### 3.3 Campus Map Location Detail
![Event Main](ux-design/prototype/NextQuad_CampusMap_Wireframes/Campus_Map_Loc_Clicked.png)

**Purpose**:  
To display detailed information about a specific campus location selected from the map.

**Key Features**:
- **Popup card** containing:
  - Location title and address.  
  - Short description of the location.  
  - **“Book Now” button** for reservable spaces.  
- **Close icon (X)** for dismissing the card.  
- Highlighted **purple map pin** indicating the active selection.

**User Interactions**:
- Tap a **map pin** to open the location info card.  
- Tap **Book Now** to proceed to the booking page (external links).  
- Tap the **close (X)** icon to close the info popup and return to the main map.  

#### 3.4 Campus Map Zoom In/Out
![Event Main](ux-design/prototype/NextQuad_CampusMap_Wireframes/Campus_Map_Zoom_In.png)
**Purpose**:  
To let users adjust the map scale for better navigation and focus on specific areas.

**Key Features**:
- **Zoom In (+)** and **Zoom Out (-)** icons located at the bottom-right corner.  
- Automatically adjusts visible pins and map detail based on zoom level.  
- Preserves filter settings during zoom interactions.

**User Interactions**:
- Tap **Zoom In (+)** to magnify campus areas.  
- Tap **Zoom Out (-)** to view a wider section of the map.  
- Combined with panning gestures for full navigation control.

### 4. Events Section

#### 4.1 Event Main (Event Discovery)
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
- Bottom navigation: "RSVPS", "My Event" and "Add Event" buttons

**User Interactions**:
- Tap any event card to view detailed event information
- Tap category filters to show only events of that type
- Use search bar to find events by keyword
- Tap "RSVPS" to view and manage event RSVPs
- Tap "My Event" to view hosted and attended events
- Tap "Add Event" to create a new event


#### 4.2 Event Detail
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
- Tap "RSVP TO EVENT" to register attendance
- View host information
- Navigate back to event list via bottom navigation


#### 4.3 Event RSVP Confirmation
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


#### 4.4 Event Create
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
- Navigate among "RSVPS", "My Event" and "Event Main" tabs


#### 4.5 My Event (Simplified Event Management Dashboard)
![My Event](ux-design/prototype/NextQuad_Events_Wireframes/My%20Events.png)

**Purpose**: Quick overview of user's upcoming and past events.

**Key Features**:

- Upcoming Events: Future events with RSVP counts
    - "View Details" button for each event
- Past Events:
    - "View Stats" button to see event metrics

**User Interactions**:
- Tap "View Details" for upcoming events
- Tap "View Stats" to see comprehensive event analytics


#### 4.6 RSVPS (A Complete View of Event Management Dashboard)
![RSVPS](ux-design/prototype/NextQuad_Events_Wireframes/RSVPs.png)

**Purpose**: Central dashboard for event organizers to manage their events and track engagement.

**Key Features** (More focused on "Attention" section, others remain the same):
- Needs Attention Section: Events requiring immediate action
    - Action buttons: "Check-ins" and "Take Survey"

**User Interactions**:
- Tap "Check-ins" to check in to event
- Tap "Take Survey" to fill in post-event feedback


#### 4.7 Event Check In
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


#### 4.8 Event Survey (Post-Event Feedback)
![Event Survey](ux-design/prototype/NextQuad_Events_Wireframes/Event%20Survey.png)

**Purpose**: Collect feedback from attendees after event completion.

**Key Features**:

- Survey Questions: Overall Rating, Comments, etc.
- Action Buttons:
    - "Submit Feedback" button (primary action)
    - "Skip for now" link (secondary action)

**User Interactions**:
- Enter numeric rating
- Select multiple aspects that were enjoyed
- Choose likelihood of future attendance
- Provide optional written feedback
- Submit survey or skip to complete later (direct back to event main)


#### 4.9 Event Analytics
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


### 5. Profile/Settings Section

**[To be completed]**
