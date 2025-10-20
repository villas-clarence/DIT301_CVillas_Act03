# ProfileUI - Android Profile Screen Prototype

## Project Overview
This is a prototype Android application demonstrating UI/UX design principles for a profile screen. The project focuses on layout, styling, and accessibility rather than functionality.

## Features
- **Profile Picture**: Circular ImageView with placeholder icon
- **User Information**: Name and bio text with proper typography
- **Edit Button**: Styled button for profile editing (no functionality)
- **Developer Stats**: Additional information card with statistics
- **Responsive Design**: Optimized layouts for both portrait and landscape orientations
- **Material Design**: Following Material Design 3 guidelines

## Design Choices

### Profile Information
- **Name**: Hannah Lorainne Genandoy
- **Bio**: 3rd year IT student at Polytechnic University of the Philippines-Taguig Campus
- **Interests**: K-pop and western emergency genre of series
- **Student Info**: 3rd Year IT student at PUP-Taguig Campus

### Colors
- **Primary Purple** (#6B46C1): Modern purple for buttons and key elements
- **Accent Pink** (#E91E63): Vibrant pink for secondary accents
- **Accent Coral** (#FF6B6B): Warm coral for highlights and stats
- **Text Primary** (#2C3E50): Sophisticated dark blue-gray for main text
- **Text Secondary** (#7F8C8D): Soft gray for secondary information
- **Background Light** (#F8F9FA): Clean, modern background
- **Card Background** (#FFFFFF): Pure white for content cards

### Typography
- **Profile Name**: 28sp, bold, sans-serif-medium for prominence
- **Bio Text**: 16sp, regular, with proper line spacing for readability
- **Button Text**: 16sp, medium weight for clear call-to-action

### Layout Principles
- **ConstraintLayout**: Used for flexible, responsive layouts
- **CardView**: Elevated cards for content separation and depth
- **Proper Spacing**: Consistent margins and padding using dp units
- **CRAP Model**: Applied Contrast, Repetition, Alignment, and Proximity principles

## Accessibility Features
- **Content Descriptions**: All images have proper content descriptions
- **Text Contrast**: High contrast ratios for text readability
- **Touch Targets**: Adequate button sizes (48dp minimum)
- **Screen Reader Support**: Semantic structure for assistive technologies
- **Responsive Text**: Scalable text sizes using sp units

## Responsive Design
- **Portrait Layout**: Vertical card layout with centered content
- **Landscape Layout**: Horizontal layout with side-by-side cards
- **Flexible Constraints**: Layouts adapt to different screen sizes
- **Consistent Spacing**: Maintained across orientations

## Technical Implementation
- **Minimum SDK**: API 24 (Android 7.0)
- **Target SDK**: API 34 (Android 14)
- **Architecture**: Single Activity with ConstraintLayout
- **Resources**: Proper separation of strings, colors, and styles
- **Themes**: Material Design 3 theme implementation

## Future Improvements
If this were a real application, I would consider:

1. **Functionality**: Add actual profile editing capabilities
2. **Data Persistence**: Implement local storage or backend integration
3. **Image Handling**: Add profile picture upload and cropping
4. **Animations**: Smooth transitions and micro-interactions
5. **Dark Theme**: Implement dark mode support
6. **Accessibility**: Add more accessibility features like TalkBack support
7. **Testing**: Comprehensive unit and UI tests
8. **Performance**: Image optimization and lazy loading
9. **Security**: Data validation and secure storage
10. **Internationalization**: Multi-language support

## Screenshots
Screenshots of the profile screen can be found in the `/activity1/` folder.

## Getting Started
1. Open the project in Android Studio
2. Sync the project with Gradle files
3. Run the app on an emulator or device
4. Test both portrait and landscape orientations

## Author
Created as a prototype to demonstrate Android UI/UX design principles and Material Design implementation.
