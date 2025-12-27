# Groupie Trackers

## Project Overview
Groupie Trackers is a web application that processes data from a music API to create an interactive website displaying information about artists, bands, and their concerts. The project involves manipulating JSON data from multiple API endpoints and presenting it through various data visualizations.

## Project Requirements

### API Structure
The application works with an API consisting of four interconnected parts:

1. **Artists** - Contains information about bands/artists including:
   - Name(s)
   - Image
   - Year activity began
   - Date of first album
   - Members

2. **Locations** - Contains last and upcoming concert locations

3. **Dates** - Contains last and upcoming concert dates

4. **Relation** - Links between all other parts (artists, dates, and locations)

### Core Objectives
- Build a user-friendly website displaying band information
- Implement multiple data visualizations (cards, tables, lists, graphics, etc.)
- Create client-server events where user actions trigger server communication
- Ensure the site never crashes and handles all errors properly
- Write backend in Go using only standard libraries

### Key Requirements
- **Backend Language**: Go (standard packages only)
- **Event System**: Must implement at least one client-server interaction feature
- **Reliability**: No crashes, proper error handling on all pages
- **Code Quality**: Follow Go best practices

### Visualization Examples
- Display artists in blocks, cards, or tables
- Create graphical representations of data
- Implement pagination or list views
- Design creative visual displays for concert information

## Learning Outcomes
This project will help you learn about:
- Data manipulation and storage
- Working with JSON files and formats
- HTML and web interface design
- Event creation and display
- Client-server architecture
- Request-response patterns

## Technical Constraints
- Only standard Go packages allowed
- Server must handle all errors gracefully
- Website must be fully functional at all times
- Client-side actions must communicate with server

## Project Focus
The primary focus is on creating an interactive website where users can explore artist information through various visualizations, with special emphasis on implementing client-server communication through events triggered by user interactions.
