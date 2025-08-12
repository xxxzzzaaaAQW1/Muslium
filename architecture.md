# Islamic App Architecture

## Overview
Comprehensive Islamic app with elegant black and gold design providing prayer times, Quran, Qibla compass, tasbih, and Hijri calendar.

## Core Features
1. **Home Screen**: Luxurious analog clock with digital time display
2. **Prayer Times**: Accurate prayer times with notification settings
3. **Quran Reader**: Full Quran with search and font scaling
4. **Qibla Compass**: Direction indicator for Mecca
5. **Digital Tasbih**: Counter for dhikr/prayers
6. **Hijri Calendar**: Islamic calendar with important dates
7. **Support Page**: Developer contact and donation info

## File Structure
- `lib/main.dart` - App entry point
- `lib/theme.dart` - Updated with black/gold Islamic theme
- `lib/screens/` - All app screens
- `lib/widgets/` - Reusable components
- `lib/models/` - Data models
- `lib/services/` - Business logic
- `lib/data/` - Static data (Quran, prayers)

## Technical Implementation
- Material 3 with custom black/gold theme
- Local storage for settings and bookmarks
- Mock location services for prayer times
- Responsive design for all screen sizes
- Arabic text support with proper RTL layout

## Dependencies Required
- geolocator: Location services
- shared_preferences: Local storage
- intl: Date/time formatting
- flutter_qiblah: Qibla direction