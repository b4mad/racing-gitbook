# Platform APIs

## Overview
The B4mad Platform provides a comprehensive set of APIs for building gaming applications across multiple genres:

## Core APIs
### Authentication
```http
POST /api/v1/auth
Content-Type: application/json

{
  "game_id": "string",
  "api_key": "string"
}
```

### Data Collection
```http
POST /api/v1/telemetry
Content-Type: application/json

{
  "game_id": "string",
  "session_id": "string",
  "data": {
    "timestamp": "string",
    "metrics": {}
  }
}
```

## Genre-Specific APIs

### Racing
- Lap timing
- Vehicle telemetry
- Track conditions
- Race classifications

### FPS
- Aim precision
- Movement patterns
- Weapon usage
- Team coordination

### RTS
- Resource management
- Unit production
- Battle analytics
- Build orders

## Integration Examples
```python
from b4mad.sdk import GameClient

# Initialize client
client = GameClient(
    game_id="your_game",
    api_key="your_key"
)

# Start collecting data
session = client.start_session()
session.send_telemetry(metrics)
```

## Rate Limits
- Free tier: 60 requests/minute
- Pro tier: 1000 requests/minute
- Enterprise: Custom limits

## Documentation
- [API Reference](api-reference.md)
- [SDK Documentation](sdk-docs.md)
- [Integration Guide](integration.md)
