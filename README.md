# Photovenio Organizer Walkthrough

This guide walks through the typical journey of a photoshoot organizer using Photovenio, from initial setup to post-event management.

## 1. Create an Account

### Getting Started
1. Visit photovenio.com and click "Sign Up"
2. Choose your plan:
   - **Free**: Perfect for trying out - up to X contacts, Y event per month
   - **Pro ($19/month)**: Unlimited contacts and events, all core features

## 2. Import Contact List

### Building Your Network
Photovenio makes it easy to centralize all your contacts from various sources.

#### From Spreadsheets
1. Navigate to **Contacts** → **Import**
2. Click "Upload CSV/Excel"
3. Map your columns:
   - Instagram handle (required)
   - Name
   - Phone number
   - Email
   - Type (Model/Photographer/Videographer)
   - Custom tags
4. Preview the import to catch any issues
5. Click "Import Contacts"

#### From Instagram Data Export
1. First, export your Instagram data:
   - Go to Instagram Settings → Privacy → Data Download
   - Request your data (JSON format)
   - Wait for download link in email
2. In Photovenio, select "Import from Instagram"
3. Upload the JSON file
4. Review extracted contacts
5. Confirm import

#### Manual Entry
1. Click "Add Contact" button
2. Fill in details:
   - Instagram handle
   - Contact type
   - Tags
   - Notes about the person

## 3. Organize Contact List

### Tagging and Categorization
1. Use bulk selection to tag multiple contacts at once
2. Create custom tags for:
   - Specialties: "fashion", "streetwear", "editorial", "commercial"
   - Locations: "Las Vegas", "Los Angeles", "etc"
   - Reliability: "always-shows", "flaky", "new"
   - Experience: "beginner", "intermediate", "professional"

### Adding Notes and History
1. Click on any contact to view their profile
2. Add interaction notes:
   - Past shoot experiences
   - Preferences and requirements
   - Scheduling constraints
   - Payment history (if applicable)

### Scoring System
1. Rate contacts 1-5 stars based on:
   - Reliability
   - Quality of work
   - Professionalism
   - Network influence
2. Use scores to prioritize invitations later

## 4. Create an Event

### Event Setup
1. Click **Events** → **Create New Event**
2. Fill in basic details:
   - **Event Name**: "Summer Fashion Shoot" 
   - **Date & Time**: Select date and start time
   - **Duration**: Estimated length (e.g., 3 hours)
   - **Location**: 
     - Address
     - Venue name
     - Parking instructions
3. Set capacity limits:
   - Maximum models (e.g., 20)
   - Maximum photographers (e.g., 10)
   - Maximum videographers (e.g., 3)
4. Choose what information is public and private on the event link

## 5. Fill Out Event Details

### Theme and Requirements
1. Add event theme/concept:
   - Style direction
   - Mood board links
   - Reference images
2. Specify requirements:
   - **For Models**:
     - Wardrobe needs ("bring 3-5 looks")
     - Specific styles ("streetwear", "formal", "swimwear")
     - Physical requirements if any
   - **For Photographers**:
     - Equipment needs
     - Shooting style preferences
3. Add any special instructions:
   - Age restrictions
   - Professional conduct expectations

### Event Settings
1. Configure visibility:
   - Private (invite-only)
   - Public with application
   - Listed on discovery page
2. Set confirmation requirements:
   - Auto-confirm trusted contacts
   - Manual review for new contacts
   - Require re-confirmation 48 hours before

## 6. Set Up Event RSVP Form & Details Page

### Creating the RSVP Form
1. Navigate to **Event** → **Application Form**
2. Choose form fields:
   - Instagram handle (auto-filled)
   - Phone number
   - Portfolio link
   - Availability confirmation
   - Wardrobe options
   - Transportation method
   - Custom questions
3. Set up the public event page:
   - Upload event flyer/mood board
   - Add detailed description
   - Include sample photos from past events
   - List confirmed notable attendees (with permission)

### Generating the Event Link
1. Click "Generate Public Link"
2. Customize the URL slug: `photovenio.com/events/summer-fashion-2024`
3. Share link on:
   - Instagram stories
   - Model/photographer groups
   - Your website

## 7. Create Template Messages for Invites

### Setting Up Message Templates
1. Go to **Templates** → **Create New**
2. Create templates for each stage:

#### Initial Invite Template
```
Hey {name}! 🌟

I'm organizing a {event_theme} photoshoot on {date} at {location}. 

Would love to have you join us! We'll have {photographer_count} photographers and expecting around {model_count} models.

Interested? Let me know! 

Details: {event_link}
```

#### Confirmation Template  
```
Awesome, {name}! You're confirmed for {event_name} ✅

📅 {date}
📍 {location}
⏰ {time}

Please bring:
{requirements}

Reply "YES" to confirm you'll be there!
```

#### Event Details (24 hours before)
```
Tomorrow's the day, {name}! 

🎯 {event_name}
📍 Address: {full_address}
🅿️ Parking: {parking_info}
⏰ {time}

{special_instructions}

See you there! Reply with any questions.
```

#### Follow-up Template
```
Hey {name}, haven't heard back about {event_name} on {date}. 

Still interested? Spots are filling up fast! 

Let me know 🙏
```

3. Save templates with descriptive names
4. Test variable substitution

## 8. DM Models from Contact List

### Smart Invitation Process
1. Go to your event dashboard
2. Click "Invite Contacts"
3. Filter your contact list:
   - Type: Models
   - Tags: "fashion", "reliable"
   - Score: 4+ stars
   - Last attended: Within 3 months
4. Use AI suggestions (Pro/Enterprise):
   - "Likely to attend" based on past behavior
   - "High influence" to attract others
   - "New talent" for fresh faces

### Sending Invitations
1. Select contacts to invite (start with your A-list)
2. Choose your invite template
3. Review personalized messages
4. Loop through the list and send DMs in Instagram
5. Update sent status
6. Update confirmed status as responses come in

## 9. Track RSVPs

### Real-Time Dashboard
Monitor your event status at a glance:
- **Invited**: 45 models, 20 photographers
- **Confirmed**: 28 models, 15 photographers  
- **Declined**: 5 models, 2 photographers
- **No Response**: 12 models, 3 photographers

### Follow-ups
1. Set follow-up rules:
   - Re-confirm 48 hours before event
   - Waitlist when spots open up
2. Track conversion rates:
   - Invite → Confirmation rate
   - Confirmation → Attendance rate

### Managing Capacity
1. Monitor against your limits
2. Waitlist management:
   - Priority waitlist for reliable contacts
3. Predict actual attendance:
   - Allow simple attendance percentages for status (invite sent, confirmed, maybe, re-confirmed)
   - Allow individual contacts to have their own attendance prediction score
   - See "probable attendance" numbers from RSVPs and their statuses

## 10. Send Out Re-confirms

### 48-Hour Re-confirmation
1. Two days before event, system prompts re-confirmation
2. See the list of who needs to have re-confirms sent
3. Track responses:
   - ✅ Re-confirmed: Will attend
   - ⚠️ Maybe: Uncertain
   - ❌ Cancelled: Won't make it
4. Fill cancelled spots from waitlist

### Final Preparations
1. Generate final attendee list
2. Create mention list for social media:
   ```
   @model_jane @photographer_mike @model_sarah @photog_alex
   ```
3. Send final details with:
   - Exact address and parking
   - Weather update
   - Any last-minute changes
   - Your contact number

## 11. Attend the Event and Mark Who Attended

### Day of Event - Check-in Process

#### Pre-Event Setup
1. Open Photovenio mobile app or mobile web
2. Navigate to today's event
3. Access "Check-in Mode"
4. View confirmed attendee list with profile photos

#### Efficient Check-in
1. As people arrive:
   - Search by name or Instagram handle
   - Allow attendees to scan a QR code to mark attendance
   - Tap to mark as "Attended"
2. Track in real-time:
   - ✅ Checked in: 18/28 models
   - ⏰ On the way: 5 models (shared ETA)
   - ❌ No-show: Auto-marked after event

#### Handling Walk-ins
1. Click "Add Walk-in"
2. Quick add their details:
   - Instagram handle
   - Type (Model/Photographer)
   - Quick photo
3. They're automatically added to your contacts

### During the Event
1. Make notes on standout performers
2. Flag any issues or incidents
3. Track content creation:
   - Which photographer shot which model
   - Special moments or setups
   - Behind-the-scenes content

### Post-Event Wrap-up
1. Finalize attendance records
2. Rate attendees:
   - Update reliability scores
   - Add performance notes
   - Tag standouts for future events
3. Generate post-event report:
   - Final attendance: 22/28 models (79%)
   - 2 walk-ins
   - 4 no-shows
   - Overall success rating

## Advanced Features

### Analytics & Insights
After several events, unlock powerful insights:
- Best performing event themes
- Optimal day/time for maximum attendance  
- Most influential contacts (bring others)
- Reliability patterns by contact type
- ROI tracking for paid events

### Content Management
1. Create shared album for event photos
2. Photographers upload their selects
3. Models access and download
4. Auto-generate mention lists for posts

### Building Your Network
1. Cross-promotion with other organizers
2. Build reputation through successful events