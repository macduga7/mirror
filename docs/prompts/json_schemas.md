## JSON Schemas

### OutfitSuggestions
{
  "suggestions": [
    {
      "title": "string",
      "items": [{"type":"top|bottom|dress|shoes|accessory","color":"string","note":"string"}],
      "reason": "string"
    }
  ]
}

### MakeupRoutine
{
  "lookName": "string",
  "steps": [
    {"step": 1, "action":"string", "productType":"string", "tip":"string", "timerSec": 0}
  ]
}

### HairSuggestions
{
  "suggestions": [
    {"title":"string","tools":["string"],"steps":["string"],"upkeepTips":["string"]}
  ]
}
