# IoT Community Events Repository

A centralized repository of IoT community events including conferences, hackathons, workshops, and webinars.

## Repository Structure

```
iotCommunity.space/events/
├── data/
│   └── events.json
└── README.md
```

## Event Data Structure

```json
{
  "title": "Event Title",
  "date": "YYYY-MM-DD",
  "location": "City, Country/Virtual",
  "category": "Conference/Hackathon/Workshop",
  "description": "Brief event description",
  "link": "Event URL"
}
```

## Event Categories
- Conferences
- Hackathons
- Workshops
- Webinars
- Meetups

## Contributing

### Adding Events
1. Fork the repository
2. Add event to `events.json`
3. Ensure all required fields are completed
4. Maintain chronological order
5. Submit pull request

### Event Guidelines
- Provide accurate dates and locations
- Include valid event URLs
- Write clear, concise descriptions
- Categorize events appropriately

## Validation
- JSON structure validation
- Date format verification
- URL accessibility check
- Required fields validation

## Support
- Open an issue for questions
- Join community discussions
- Check existing event submissions

## License
See LICENSE file for terms of use
