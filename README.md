# Race Results Extractor

Transform messy race results into beautiful, organized data. Supports multiple platforms including:

- **RunHigh**
- **KarmaRush**
- **RunSignup**
- **MileSplit**
- **Athlete Guild**
- **Endurance Splits**
- **MeetPro**

## Features

- 📋 Paste any supported race results format
- ✨ Automatically detects the platform
- 📊 Extracts and formats all runner data
- 📋 Copy results as tab-separated values for Excel/Sheets
- 🎨 Beautiful, responsive interface

## Usage

1. Visit the live site: [Race Results Extractor](https://your-site.vercel.app)
2. Paste your race results into the input area
3. Click "Extract Results"
4. Copy the formatted data to Excel or Google Sheets

## Supported Formats

### RunHigh
Supports the individual results format from runhigh.com

### KarmaRush
Tab-separated format with grade/bib information

### RunSignup
Multi-line format with split name fields

### MileSplit
Results with logo markers and bib numbers

### Athlete Guild
Tab-separated format with Name, Bib, Team, Rank, Time

### Endurance Splits
Format with O'All Place, Score, Bib, Name, Team, Time, Pace

### MeetPro
Tab-separated format with Place, Name (LAST, First), Year, Bib, Team, Score, Time, Gap, Avg. Mile

## Development

To run locally:
```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/race-results.html`

## Debug Mode

Open `race-results-debug.html` for detailed parsing information and debugging.
